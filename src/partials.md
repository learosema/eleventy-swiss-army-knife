---
title: Partials
layout: slide
---

_includes/nav.njk

```njk
<nav><ul>
  <li><a href="/">Home</a></li>
  <li><a href="/about/">About</a></li>
  <li><a href="/contact/">Contact</a></li>
</ul></nav>
```

Include via:

```njk
{% raw %}{% include "nav.njk" %}{% endraw %}
```
