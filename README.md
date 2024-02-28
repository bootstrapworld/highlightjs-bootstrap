# highlightjs-bootstrap

![version](https://badgen.net/npm/v/highlightjs-4d)

## Description

Pyret - a language grammar for highlightjs
Scheme - a language grammar for highlightjs

### Static website or simple usage

```html
<script type="text/javascript" src="/path/to/highlight.min.js"></script>
<script type="text/javascript" charset="UTF-8"
  src="/path/to/highlightjs-bootstrap/dist/pyret.min.js"></script>
<script type="text/javascript" charset="UTF-8"
  src="/path/to/highlightjs-bootstrap/dist/scheme.min.js"></script>
<script type="text/javascript">
  hljs.highlightAll();
</script>
```

### With Node or another build system

If you're using Node / Webpack / Rollup / Browserify, etc, simply require the language module, then register it with Highlight.js.

```javascript
var hljs = require('highlightjs');
var {pyret, scheme} = require('highlightjs-bootstrap');

hljs.registerLanguage("pyret", pyret);
hljs.registerLanguage("scheme", scheme);
hljs.highlightAll();
```
