# smoothscroll.js

Polyfill for
* window.scroll({ left, top, behavior });
* window.scrollTo({ left, top, behavior });
* window.scrollBy({ left, top, behavior });

* element.scrollIntoView(ScrollOptions); (incomplete)

## Use

`bower install --save smoothscroll`

This depends upon `requestAnimationFrame`. As such you can use either
dist/smoothscroll.js if you have a raf polyfill already included (or are
supporting only raf-enabled browsers), or use dist/smoothscroll.raf.js
to use a version bundled with a polyfill (batteries included version).

Browser Support
---------------

This has been tested successfully in the following browsers:

* Safari 6+, iOS 6+
* Firefox
* Chrome
* Opera Next

Size
----

**787 bytes** minified and gzipped


Standards documentation
-----------------------

* http://dev.w3.org/csswg/cssom-view
* http://lists.w3.org/Archives/Public/www-style/2013Mar/0314.html
