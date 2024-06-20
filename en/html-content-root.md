---
title: The Content Root of HTML
canonical: https://www.toheeb.com/en/html-content-root/
book-hc: 2
---



<h1 id="root-content">The Content Root of HTML</h1>

The Content Root provides an environment for the [Content Metas](/en/html-content-metas) and [Content Windows](/en/html-content-windows) of a web document

The syntax is an [`html` element](https://html.spec.whatwg.org#the-html-element) with the following attributes and elements:

- Zero or one count for each [Global Attribute](/en/html-content-attributes#global-list)

- The following order of elements:
  
  - One [`head` element](/en/html-content-metas#container-head)

  - One [`body` element](/en/html-content-windows#window-primary)

For legacy reasons, the [DOCTYPE construct](https://html.spec.whatwg.org#the-doctype) should precede the `html` element.

```html
<!DOCTYPE html>
<html>
  <head>

  </head>
  <body>
    
  </body>
</html>
```

