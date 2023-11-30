---
title: Adding Content
layout: slide
---
## Adding content

```sh
cd src
echo "Hello world!" > index.md
echo "Hi! I am Lea" > about.md
echo "[mastodon](https://lea.lgbt/@lea)" > contact.md
cd ..

# Start a dev server
npx @11ty/eleventy --serve
```
