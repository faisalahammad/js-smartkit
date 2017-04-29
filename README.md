# js-smartkit
JavaScript complicated solution in just few links code. &lt;3

### CHANGE HTML TAG
    $('span').each(function() {
      $(this).replaceWith($('<div>' + this.innerHTML + '</div>'));
    });​

    => Replace "span" with your targeted tag, replace "<div>" with your own tag.

### ADD HTML CODE BEFORE SPECIFIC TAG
    jQuery(document).ready(function( $ ){
        $( ".class" ).before( "<img src='name.png' alt='image' class='img-responsive center-block'>" );
    });

    => Replace with your Class, HTML code there.