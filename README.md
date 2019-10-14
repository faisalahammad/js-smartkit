<<<<<<< HEAD
# JS SMARTKIT
JavaScript complicated solution in just few lines code. Don't forgot to put your code inside
```javascript
jQuery(document).ready(function( $ ){
    // Put your code there
});
```

---
=======
# JS-SMARTKIT

JavaScript complicated solution in just few links code. &lt;3
>>>>>>> c025a46c876b7ea60b223b00f4423c8c3d839b70

### CHANGE HTML TAG

```javascript
$('span').each(function() {
  $(this).replaceWith($('<div>' + this.innerHTML + '</div>'));
});​
```

**Replace `span` with your targeted tag, replace `<div>` with your own tag.**

<<<<<<< HEAD
---
=======
<hr>
>>>>>>> c025a46c876b7ea60b223b00f4423c8c3d839b70

### ADD HTML CODE BEFORE SPECIFIC TAG

```javascript
jQuery(document).ready(function($) {
  $(".class").before(
    "<img src='name.png' alt='image' class='img-responsive center-block'>"
  );
});
```

**Replace with your Class, HTML code there.**

<<<<<<< HEAD
---
=======
<hr>
>>>>>>> c025a46c876b7ea60b223b00f4423c8c3d839b70

### WORK WITH SPECIFIC SCREEN SIZE

After you have added jQuery you can use the following code in your custom javascript file. You may change the **"739"** to a different number depending on the device resolution you are targeting.

```javascript
if ($(window).width() > 739) {
  //Use < or >
  //Add your javascript for large screens here
} else {
  //Add your javascript for small screens here
}
```

<<<<<<< HEAD
---
=======
<hr>
>>>>>>> c025a46c876b7ea60b223b00f4423c8c3d839b70

### CHANGE HTML INLINE STYLE

```javascript
jQuery(document).ready(function($) {
  $(".x-gap").css({ margin: "200px 0 0 0" });
});
```

<<<<<<< HEAD
---
=======
<hr>
>>>>>>> c025a46c876b7ea60b223b00f4423c8c3d839b70

### REPLACE HTML CONTENT

```Javascript
jQuery(document).ready(function( $ ){
   $('.class or #id').html('Our <strong>HTML</strong> Content.');
});
```

<<<<<<< HEAD
---
=======
<hr>
>>>>>>> c025a46c876b7ea60b223b00f4423c8c3d839b70

### CHANGE HREF / URL

```javascript
$("a").attr("href", "http://www.google.com/");
```

<<<<<<< HEAD
---

### OPEN URL ON NEW TAB
```javascript
$(".class a").attr("target", "_blank");
```

---
=======
<hr>
>>>>>>> c025a46c876b7ea60b223b00f4423c8c3d839b70

### SET WIDTH

```javascript
document.getElementById("header").style.width = "50%";
// or
$("#id").width("30%");
// or
$("#id").css("width", "50%");
```

<<<<<<< HEAD
---

### How to dynamically select option in dropdown menu

```javascript
// Using the value:
$('#id/.class').val( 3 );

// Using the text:
$('#id/.class option').filter(function() { 
    return ($(this).text() == 'Blue'); //To select Blue
}).prop('selected', true);
```

---

### Redirect User to another website 
=======
<hr>

### Find Current & Next Month

```javascript
function monthsList() {
  var month = new Array();
  month[0] = "January";
  month[1] = "February";
  month[2] = "March";
  month[3] = "April";
  month[4] = "May";
  month[5] = "June";
  month[6] = "July";
  month[7] = "August";
  month[8] = "September";
  month[9] = "October";
  month[10] = "November";
  month[11] = "December";

  var d = new Date();
  var nowMonth = month[d.getMonth()]; // Current Month
  var nextMonth = month[d.getMonth() + 1]; // Next Month
  // Show on frontend
  document.getElementById("nowMonth").innerHTML = nowMonth;
  document.getElementById("nextMonth").innerHTML = nextMonth;
}
monthsList();
```

Create 2 id `nowMonth & nextMonth` to display on the frontend.

<hr>

### Redirect User to another website

>>>>>>> c025a46c876b7ea60b223b00f4423c8c3d839b70
<strong>JavaScript</strong>

```html
<script type="text/javascript">
  window.location.href = "http://example.com";
</script>
```

<strong>HTML</strong>

```html
<meta http-equiv="refresh" content="0; url=http://example.com/" />
```
