---
title: How to use this Hugo theme ?
date: 2021-02-02
tags: ["hugo","blog"]
image : "/img/posts/img-3.jpg"
Description  : "After downloding the theme, uzip the file and go to the'lightbi-hugo-master' folder. Open the folder in you editor..."
featured: true
---

Install Hugo and create a new site. See [the Hugo documentation](https://gohugo.io/getting-started/quick-start/) for details.

```
hugo new site <name of site>
cd <name of site>
git init
git submodule add https://github.com/binokochumolvarghese/lightbi-hugo themes/lightbi-hugo
echo "theme = 'lightbi-hugo'" >> config.toml
hugo server
```

Your website has started to build and it will normally available at 'http://localhost:1313/'.

<!--Photo by Robert Katzki on Unsplash-->
