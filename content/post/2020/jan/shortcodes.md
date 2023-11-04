---
title: Hugo Shortcodes
date: 2020-01-01
tags: ["hugo"]
image : "/img/posts/img-2.jpg"
Description  : "Hugo is using markdown for content format, but there are times when Markdown falls short. Often we are forced to use the raw HTML...."
---
Hugo is using markdown for content format, but there are times when Markdown falls short. Often we are forced to use the raw HTML, to overcome these limitations Hugo created **shortcodes**.

### What is a shortcode?
A shortcode is a simple snippet inside the content file that Hugo will render using a predifened template. You can find the below readily availablw shortcodes in this theme:

#### Figure

This adds an image with caption.

{{< figure src="/img/posts/img-3.jpg" caption="With caption." attrlink="" >}}


#### Details

This simply adds the html5 detail attribute, supported on all *modern* browsers. Use it like this:


{{< details "This is the details title (click to expand)" >}}
This is the content (hidden until clicked).
{{< /details >}}
 

#### Split

This adds a two column side-by-side environment (will turn into 1 col for narrow devices):


{{< columns >}}
This is column 1.
{{< column >}}
This is column 2.
{{< endcolumns >}}

