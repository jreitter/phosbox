# Phosbox Lightbox

Phosbox is a minimalistic, easy-to-use and responsive jQuery lightbox plugin

## Demo

http://jreitter.com/github/demo/phosbox/

## HOW TO USE PHOSBOX

1. Include the the phosbox.css stylesheet in your `<head>`   
```<link rel="stylesheet" href="path/to/phosbox.css" />```

2.Include jQuery and Phosbox right before your `</body>` tag:
```
<script src="path/to/jquery.js"></script>
<script src="path/to/phosbox.js"></script>
```

3. Phosbox works with a link that referrs to an image. In order for the plugin to work, your link must have a specific class assigned to it:
```
<a class="your-class" href="path/to/image">
   <img src="path/to/thumbnail">
</a>
```

Your markup could also look like this:   
```<a class="your-class" href="path/to/image">Awsome Photo!</a>```

4. Simply call the plugin and you're done. Phosbox is ready to work.
```
$(document).ready(function(){
   $('.your-class').phosbox();
});
```


## License

MIT License
