---
title: Advanced Tooling
layout: slide
---

```js
module.exports = (eleventyConfig) => {
  eleventyConfig.addTemplateFormats('js');

  eleventyConfig.addExtension('js', {
    outputFileExtension: 'js',
    compile: async (content, fullPath) => {
      return async () => {
        return await doSomething(content);
      };
    },
  });
};
```
