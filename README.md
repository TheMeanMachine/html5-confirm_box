# Confirm Box
## Creates a confirm box in HTML5 using Javascript

It's fully customisable! The buttons, title, content and actions on either button can be all changed.
![example of confirm box](https://i.imgur.com/0fqY2cc.png)

### How to implement:

- Step 1: download both the confirm.css and confirm.js

- Step 2: add the following tags to your HTML:
```html
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
