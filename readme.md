# cssman

cssPath from the [Chrome devtools](https://chromium.googlesource.com/chromium/blink/+/master/Source/devtools/front_end/components/DOMPresentationUtils.js) as a node module. Copy-pasted this gist: https://gist.github.com/asfaltboy/8aea7435b888164e8563

```javascript
var csspath = require('cssman');
console.log(csspath(someElement));
```

```
html > body > header > h1
```
