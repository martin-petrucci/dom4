DOM4
====

This is a [fully tested](http://webreflection.github.io/dom4/test/) and covered polyfill for [new DOM Level 4 entries](https://dvcs.w3.org/hg/domcore/raw-file/tip/Overview.html#interface-element)

  * Element#prepend()
  * Element#append()
  * Element#before()
  * Element#after()
  * Element#replace()
  * Element#remove()

The [implemented test](test/dom4.js) is conform to [current specifications](https://dvcs.w3.org/hg/domcore/raw-file/tip/Overview.html#dom-rootnode-prepend).

Latest version includes tested specs for [classList](http://www.w3.org/TR/dom/#domtokenlist), included forced fixes for iOS 5.1 and Nokia ASHA Xpress Browser and early implementations plus [CustomEvent](http://www.w3.org/TR/dom/#customevent) constructor for all browsers.

The **DOM4** license is Mit Style

If you need other polyfills too [have a look at another DOM-shim repo](https://github.com/Raynos/DOM-shim).

### Compatibility
Theoretically compatible with all browsers you know that are truly used these days, here a list:

  * Android 2.1+
  * Safari Mobile since iOS 3.0
  * Opera Mobile
  * Midori and probably any WebKit based
  * Chrome Mobile and Desktop
  * Firefox Mobile and Desktop
  * IE8+ for Desktop and IE Mobile 9 or greater.
  * Nokia Xpress Browser for ASHA Platform
  * Silk Browser - Fire OS 3.0

It's way easier if you tell me which browser in a current relevant market share is not supported :-)

For **IE8** only it's recommended to include [ie8](https://github.com/WebReflection/ie8#ie8) script before `dom4` or `CustomEvent`, `addEventListener`, and `dispatchEvent` won't work as expected.

### Which File
The [minified version is here](build/dom4.js), while the [max one here](build/dom4.max.js). If you want to test directly [try this page](http://webreflection.github.com/dom4/test/), it should be green.