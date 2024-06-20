---
title: 2 Content Guides for writing HTML
canonical: https://www.toheeb.com/en/html-content-guides/
book-hc: 13
---


# 2 Content Guides for writing HTML

HTML is declarative.

It won't warn you of a bad markup talkless of a potential bad markup. 

This style guide aims to help you avoid issues on the long run. 

<section>
  <h2>Avoid nesting Content Windows</h2>

  Content Windows are mutually exclusive. Only one can be active at a time even if it has descendants. Hence, it's redundant to nest content windows.

  <figure>

  ```html
  <body>
    <dialog> <!-- -->
      <dialog></dialog>
    </dialog>
  </body>
  ``` 

  <figcaption>

  The markup above is unsemantic to how it functions. A Primary Window (`body` element) parents a Secondary Window (`dialog` element) which parents another Secondary Window.
  </figcaption>
  </figure>

  <figure>

  ```html
  <body>
    <div></div> <!-- represents primary window -->
    <dialog></dialog>
    <dialog><dialog>
  </body>
  ```
  <figcaption>
    
    The markup above is semantic to how it functions. It introduce a `div` element to represent the primary window since the `body` element doubles as the root of all non-meta contents. In addition, no secondary windows are nested.  
  </figcaption>
  </figure>
</section>



<section>
<h2 id="boilerplate">Start with this 7-content boilerplate</h2>

Every web document should begin with the following 7 contents because of their respective purposes.

- [Content Root](/en/html-content-root/)

- [Charset Meta](/en/html-content-metas/#meta-charset)

- [Viewport Meta](/en/html-content-metas/#meta-custom-text)

- [Title Meta](/en/html-content-metas/#meta-title)

- [Base Stylesheet](/en/prose/)

- [Primary Window](/en/html-content-windows/#window-primary)

- [Main View](/en/html-content-windows/#view-main)


In code, you'll be using the following:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><!-- Document Title --></title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@toheeb/prose@0.0.0/index.min.css">

    <!-- More Content Metas -->
  </head>
  <body>
    <div class="window-primary">
      <main>
        <!-- Content -->
      </main>
      <!-- Hidden Main Views -->
    </div>
    <!-- Secondary Windows -->
  </body>
</html>
```

<details>
<summary>Expectations</summary>

It is expected that you'll do the following:

- Change the value of the `lang` attribute on the `html` element to the primary language of the page

- Specify an appropriate Document Title

- Add more [Content Metas](/en/html-content-metas/) as you wish

- Add [Secondary Windows](/en/html-content-windows/#window-secondary) if need be

- Add hidden [Main Views](/en/html-content-windows/#view-main) if you so wish

- Write [Content Blocks,](/en/html-content-blocks/) optionally through [Content Mixes,](/en/html-content-mixes) within the [Main View.](/en/html-content-windows/#view-main)
</details>


</section>
