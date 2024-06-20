---
title: The 2 Content Windows of HTML
canonical: https://www.toheeb.com/en/html-content-windows/
book-hc: 4
---



<header>
  <h1 id="content-window">The 2 Content Windows of HTML</h1>

  A Content Window relates a viewport of [Content Parts](/en/html-content-parts/) to users.

  <nav>
  <h2>Outline</h2>

  The 2 Content Windows are as follows:

  - [Primary Window](#window-primary)

  - [Secondary Window](#window-secondary)

  </nav>
</header>



<section>
  <h2 id="window-primary">Primary Window</h2>

  The Primary Window represents the default Content Window

  The syntax is one [`body` element](https://html.spec.whatwg.org/#the-body-element) per document with the following attributes and contents:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each of the following parts: [Main Part](/en/html-content-parts/#view-main), [Content Section,](/en/html-content-parts/#content-sections) [Header Part,](/en/html-content-parts/#part-header) and [Footer Part](/en/html-content-parts/#part-footer)

  ```html
  <body></body>
  ```
</section>


<section>
  <h2 id="window-secondary">Secondary Window</h2>

  A Secondary Window defines a temporary Content Window

  The syntax is a [`dialog` element](https://html.spec.whatwg.org/#the-dialog-element) with the following attributes and child elements:

  - Zero or one [`open` attribute](/en/html-content-attributes#open)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each of the following parts: [Content Section,](/en/html-content-parts/#content-sections) [Header Part,](/en/html-content-parts/#part-header) and [Footer Part](/en/html-content-parts/#part-footer)

  ```html
  <dialog>
    
  </dialog>
  ```
</section>

<aside>
  <h3 id="view-main">Main View</h3>

  A Main View relates a set of [Content Sections](#content-sections), [Header Parts](#part-header), and [Footer Parts](#part-footer) for the viewport of a [Primary Content Window](/en/html-content-windows/#window-primary)

  The syntax is a [`main` element](https://html.spec.whatwg.org/#the-main-element) with the following attributes and child elements:

  - Zero or one count for each [`hidden` attribute](/en/html-content-attributes/#attribute-hidden) and other [Global Attribute](https://html.spec.whatwg.org/#global-attributes) 

    By the way, the `hidden` attribute must apply to all but one Main Part in the Primary Window

  - Zero or more [Content Parts](#outline) excluding [Content Segments](#content-segments)

  ```html
  <main>

  </main>
  ```
</aside>

