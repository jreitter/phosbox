# Phosbox Lightbox

Phosbox is a minimalistic, simple, easy-to-use and responsive lightbox plugin

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

The MIT License (MIT)
Copyright (c) 2014 Johannes Reitter (jreitter)
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
