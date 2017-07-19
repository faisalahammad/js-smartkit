# JS-SMARTKIT
JavaScript complicated solution in just few links code. &lt;3

### CHANGE HTML TAG
```javascript
$('span').each(function() {
  $(this).replaceWith($('<div>' + this.innerHTML + '</div>'));
});​
```
**Replace `span` with your targeted tag, replace `<div>` with your own tag.**

### ADD HTML CODE BEFORE SPECIFIC TAG
```javascript
jQuery(document).ready(function( $ ){
    $( ".class" ).before( "<img src='name.png' alt='image' class='img-responsive center-block'>" );
});
```
**Replace with your Class, HTML code there.**

### WORK WITH SPECIFIC SCREEN SIZE
After you have added jQuery you can use the following code in your custom javascript file. You may change the __"739"__ to a different number depending on the device resolution you are targeting.
```javascript
if ( $(window).width() > 739) {
    //Use < or > 
    //Add your javascript for large screens here 
} 
else {
  //Add your javascript for small screens here 
}
```

### CHANGE HTML INLINE STYLE
```javascript
jQuery(document).ready(function( $ ){
  $(".x-gap").css({ "margin": "200px 0 0 0" });
});
```

### REPLACE HTML CONTENT
```Javascript
jQuery(document).ready(function( $ ){
   $('.class or #id').html('Our <strong>HTML</strong> Content.');
});
```

### Redirect User to another website 
<strong>JavaScript</strong>
```js
window.location.href = "http://example.com";
```
<strong>HTML</strong>
```html
<meta http-equiv="refresh" content="0; url=http://example.com/" />
```