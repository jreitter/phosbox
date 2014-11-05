# Phosbox Lightbox

Phosbox is a minimalistic, easy-to-use and responsive jQuery lightbox plugin

## Demo

http://jreitter.com/demo/phosbox/

## HOW TO USE PHOSBOX

Include the the phosbox.css stylesheet in your `<head>`   
```html
<link rel="stylesheet" href="path/to/phosbox.css" />
```

Include jQuery and Phosbox right before your `</body>` tag:
```html
<script src="path/to/jquery.js"></script>
<script src="path/to/phosbox.js"></script>
```

Phosbox works with a link that referrs to an image. In order for the plugin to work, your link must have a specific class assigned to it:
```html
<a class="your-class" href="path/to/image">
   <img src="path/to/thumbnail">
</a>
```

Your markup could also look like this:   
```html
<a class="your-class" href="path/to/image">Awsome Photo!</a>
```

Simply call the plugin and you're done. Phosbox is ready to work.
```js
$(document).ready(function(){
   $('.your-class').phosbox();
});
```

Default Options:
```js
$('.your-class').phosbox({
   fadeInSpeed: 300,
   fadeOutSpeed: 300
});


## License

MIT License
