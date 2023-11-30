---
title: Basic bundling
layout: slide
---

css.njk

```njk
{% raw %}---
permalink: bundle.css
---
{% include "_reset.css" %}
{% include "_components.css" %}
{% include "_utils.css" %}
{% endraw %}
```
