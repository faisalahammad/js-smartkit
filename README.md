# js-smartkit
JavaScript complicated solution in just few links code. &lt;3

### CHANGE HTML TAG
    $('span').each(function() {
      $(this).replaceWith($('<div>' + this.innerHTML + '</div>'));
    });​