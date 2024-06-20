---
title: The 3 Content Breaks of HTML
canonical: https://www.toheeb.com/en/html-content-breaks/
book-hc: 8
---


<header>
  <h1>The 3 Content Breaks of HTML</h1>

  A Content Break relates a change in composition within a [Content Block](/en/html-content-blocks/) 


  <nav class="list-to-grid">
  <h2>Outline</h2>

  The 3 Content Breaks are as follows:

  - [Word Break](#break-word)

  - [Text Break](#break-text)

  - [Option Break](#break-option)

  </nav>

</header>

<section>
  <h2 id="break-word">Word Break</h2>

  A Word Break hints at a change within a text composition

  The syntax is a void `wbr` element with the following attributes:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <wbr>
  ```
</section>



<section>
  <h2 id="break-text">Text Break</h2>

  A Text Break enforces a change within a text composition

  The syntax is a void `br` element with the following attributes:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <br>
  ```
</section>



<section>
  <h2 id="break-option">Option Break</h2>

  An Option Break enforce a change between [options](/en/html-content-forms/#form-select-option) of a [Select Form](/en/html-content-forms/#form-select)

  The syntax is a void `hr` element with the following attributes:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <hr>
  ```
</section>

