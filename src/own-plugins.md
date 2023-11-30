---
title: Own plugins
layout: slide
---
Plugins are also functions that take an eleventyConfig object:

```js
// my-eleventy-plugin.js
module.exports = function (eleventyConfig) {

  // do stuff, like adding plugins
  eleventyConfig.addPlugin(syntaxHighlightPlugin);
}
```

You can use that to organize your configuration.
