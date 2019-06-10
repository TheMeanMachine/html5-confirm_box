# Confirm Box
## Creates a confirm box in HTML5 using Javascript

It's fully customisable! The buttons, title, content and actions on either button can be all changed.
![example of confirm box](https://i.imgur.com/0fqY2cc.png)

### Demo
Go to the below codepen link to see a demo of the confirmation box
https://codepen.io/TheMeanMachine/pen/GaVVve

### How to implement:

- Step 1: download both the confirm.css and confirm.js

- Step 2: add the following tags to your HTML:
```html
<!--Google material icons-->
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet"> 

<link rel="stylesheet" type="text/css" href="path/to/confirm.css">
<script src="path/to/confirm.js"></script>
```
### How to use:

Implement the javascript below and it will create a confirm box.

```javascript
confirmThis("Title here", "Content here","CANCEL", "CONTINUE",function(){
    //Continue code here
    
},function(){
    //Cancel code here
    
});
```
#### Notes

Google Material icons are needed. This is only used for the 'X' close button on the top left. Should you wish to remove this, and dependancy on Google Material icons, the line needed to be removed is line 47:

```javascript
cfTop.appendChild(cfclose);
```
