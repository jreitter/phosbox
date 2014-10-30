# Phosbox Lightbox 1.0

Phosbox is a minimalistic, simple, easy-to-use and responsive lightbox plugin

## Demo

tba

## Author

Johannes Reitter   
www.jreitter.com

## Usage

Using Phosbox is simple. The plugin requires a <a class="YourClassName"></a> link that referrs to an image in order to work.

In most cases your markup will be like this:
```html
<a class="YourClassName" href="PathToImgSrc"><img src="PathToDisplayedImgSrc"></a>
```
It can also be like:

```html
<a class="YourClassName" href="PathToImgSrc">Click this awsome link to open Phosbox</a>
```

Phosbox requires jQuery in order to work. Add jQuery and Phosbox right before your `</body>` tag:

```html
<script scr="path/to/jquery.js"></script> 
<script src="path/to/phosbox.js"></script>
```

Initialize the plugin:

```js
$(document).ready(function(){
  $('.YourClassName').phosbox();
});
```

## License

MIT License
