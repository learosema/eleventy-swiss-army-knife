---
title: Create Layouts
layout: slide
---

_layout/base.njk

```html
{% raw %}<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>{{ title }} – {{ site.name }}</title>
  </head>
  <body>
    {% block content %}
      {{ content | safe }}
    {% endblock %}
  </body>
</html>{% endraw %}
```
