---
title: Eleventy Config
layout: slide
---

Create an `eleventy.config.js` file:

```js
module.exports = function (eleventyConfig) {
  return {
    dir: {
      output: 'dist',
      input: 'src',
      includes: '_includes',
      layouts: '_layouts',
    },
  };
}
```
