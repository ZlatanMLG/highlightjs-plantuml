# plantuml - a language grammar for highlight.js

## Usage

Simply include the Highlight.js library in your webpage or Node app, then load this module.

### Static website or simple usage

Simply load the module after loading Highlight.js.  You'll use the minified version found in the `dist` directory.  This module is just a CDN build of the language, so it will register itself as the Javascript is loaded.

```html
<script type="text/javascript" src="/path/to/highlight.min.js"></script>
<script type="text/javascript" src="/path/to/plantuml.min.js"></script>
<script type="text/javascript">
  hljs.highlightAll();
</script>
```

### Author

Valentyn Zhelepa <neokek1@gmail.com>
