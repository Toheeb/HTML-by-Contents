---
title: The 8 Content Parts of HTML
canonical: https://www.toheeb.com/en/html-content-parts/
book-hc: 5
---


<header>

  # The 8 Content Parts of HTML

  A Content Part associates a set of [Content Mixes](/en/html-content-mixes/) to a [Topic Block](/en/html-content-blocks/#topic-blocks)

  When the Topic Block is a [Heading Block](/en/html-content-blocks/#block-headings), the Content Part is specifically a Content Section. Otherwise, when it's a [Title Block](/en/html-content-blocks/#block-titles), the Content Part is a respective Content Segment.

  Since a Title Block do not create a document outline, a Content Segment belongs to a parent Content Section. So: each Content Section, and the set of Header and Footer Parts they initiate, is a division of a [Content Window](/en/html-content-windows/) or another Content Section. 


  <nav class="list-to-grid">
  <h2 id="outline"> Outline </h2>
    
  The 8 Content Parts in 2 groups are as follows:

  - <span id="content-segments">Content Segments</span>

    - [Cell Segment](#segment-cell)
    
    - [Association Segment](#segment-association)

    - [Details Segment](#segment-details)
    
    - [Fieldset Segment](#segment-fieldset)


  - <span id="content-sections">Content Sections</span>

    - [General Section](#section-general)
    
    - [Article Section](#section-article)
    
    - [Aside Section](#section-aside)

    - [Navigation Section](#section-navigation) 


  Each of Article Section, Aside Section and Navigation Section is a specific type of the General Section. 

  Moreover, the presence of a [Content Section](#content-sections) allows for the inclusion of the following parts:

  - [Header Part](#part-header)

  - [Footer Part](#part-footer)

  Furthermore, the sections and the parts above can be contextualize with a [Main Part](#part-main)

  </nav>
</header>




<section>
  <h2 id="segment-cell">Cell Segment</h2>

  A Cell Segment bound contents for a row under a [Column Title](/en/html-content-blocks/#title-column) in a [Tabular Layer](/en/html-content-cards/#layer-tabular)

  The syntax is a [`td` element](https://html.spec.whatwg.org/#the-td-element) with the following attributes and child elements:

  - Zero or one count for each of the following attributes: 
  [`colspan`,](/en/html-content-attributes#attribute-colspan) 
  [`headers`,](/en/html-content-attributes#attribute-headers) and 
  [`rowspan`.](/en/html-content-attributes#attribute-rowspan)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more [Content Mixes.](/en/html-content-mixes/)

  ```html
  <td></td>
  ```
</section>



<section>
  <h2 id="segment-association">Association Segment</h2>

  An Association Segment bound contents describing an [Association Title](/en/html-content-blocks/#title-description) in an [Description Layer](/en/html-content-cards/#layer-description)

  The syntax is a [`dd` element](https://html.spec.whatwg.org/#the-dd-element) with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more [Content Mixes.](/en/html-content-mixes/)

  ```html
  <dd></dd>
  ```
</section>




<section>
  <h2 id="segment-details">Details Segment</h2>

  A Details Segment bounds a [Details Title](/en/html-content-blocks/#title-details) and its contents.

  The syntax is a [`details` element](https://html.spec.whatwg.org/#the-details-element) with the following attributes and child elements:

  - Zero or one [`name` attribute](/en/html-content-attributes/#attribute-name) with unique value to that of any ancestor `details` element

  - Zero or one [`open` attribute.](/en/html-content-attributes/#attribute-open) unique in a [details name group](https://html.spec.whatwg.org/#details-name-group)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - The following order of child elements  

    - One [`summary` element](/en/html-content-blocks/#title-details) 

    - Zero or more [Content Mixes.](/en/html-content-mixes/)

  ```html
  <details>
    <summary>[title]</summary>

  </details>
  ```
</section>



<section>
  <h2 id="segment-fieldset">Fieldset Segment</h2>

  A Fieldset Segment bounds a [Fieldset Title](/en/html-content-blocks/#title-fieldset) and its contents

  The syntax is a [`fieldset` element](https://html.spec.whatwg.org/#the-fieldset-element) with the following attributes and child elements:

  - Zero or one count for each of the following attributes: 
  [`disabled`,](/en/html-content-attributes/#attribute-disabled) 
  [`form`,](/en/html-content-attributes/#attribute-form) and 
  [`name`.](/en/html-content-attributes/#attribute-name) 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)
  
  - The following order of child elements  

    - Zero or one [`legend` element](/en/html-content-blocks/#title-fieldset) 

    - Zero or more [Content Mixes.](/en/html-content-mixes/)

  ```html
  <fieldset>

  </fieldset>
  ```
</section>



<section>
<h2 id="section-general">General Section</h2>

A General Section bounds an [Heading Block](/en/html-content-blocks/#block-heading) and its contents

It becomes a Region Landmark if it has an accessible name via one of the following attributes: `aria-label`, `aria-labelledby`, and `title`.

The syntax is a [`section` element](https://html.spec.whatwg.org/#the-section-element) with the following attributes and child elements:

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more [Content Mixes.](/en/html-content-mixes/)

```html
<section>

</section>
```

</section>




<section>
  <h2 id="section-article">Article Section</h2>

  An Article Section relates a [section](#section-general) independent to the surrounding sections.

  The syntax is an [`article` element](https://html.spec.whatwg.org/#the-article-element) with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more [Content Mixes.](/en/html-content-mixes/)

  ```html
  <article>

  </article>
  ```
</section>



<section>
  <h2 id="section-aside">Aside Section</h2>

  An Aside Section relates an additional [section](#section-general) that completes one or more surrounding sections.

  It becomes a Complementary Landmark when in the direct context of a [Content Window](/en/html-content-windows/)

  The syntax is an [`aside` element](https://html.spec.whatwg.org/#the-aside-element) with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more [Content Mixes.](/en/html-content-mixes/)

  ```html
  <aside>

  </aside>
  ```
</section>



<section>
  <h2 id="section-navigation">Navigation Section</h2>

  A Navigation Section relates a [section](#section-general) whose contents focus on a set of links to surrounding or descendant sections

  It becomes a Navigation Landmark when in the direct context of a [Content Window.](/en/html-content-windows/) In such context, the links should go to Content Windows outside of a web page

  The syntax is a [`nav` element](https://html.spec.whatwg.org/#the-nav-element) with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more [Content Mixes.](/en/html-content-mixes/)

  ```html
  <nav>

  </nav>
  ```
</section>



<aside>
<h2>Appendix</h2>

<section>
<h3 id="part-header"> Header Part </h3>

  An Header Part relate introductory contents to one or more surrounding [Content Sections](#content-sections)

  It becomes a Banner Landmark when in the direct context of a [Content Window.](/en/html-content-windows/) In this context, the contents should be site-specific and not page specific

  The syntax is a [`header` element](https://html.spec.whatwg.org/#the-header-element) with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more [Content Mixes](/en/html-content-mixes/) excluding descendant [Content Sections](/en/html-content-parts/#content-sections)

  ```html
  <header>

  </header>
  ```

</section>


<section>
  <h3 id="part-footer">Footer Part</h3>

  A Footer Part relate supplementary contents to one or more surrounding [Content Sections](#content-sections)

  It becomes a ContentInfo Landmark when in the direct context of a [Content Window.](/en/html-content-windows/) In this context, the contents should be site-specific and not page specific

  The syntax is a [`footer` element](https://html.spec.whatwg.org/#the-footer-element) with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more [Content Mixes](/en/html-content-mixes/) excluding descendant [Content Sections](/en/html-content-parts/#content-sections)


  ```html
  <footer>

  </footer>
  ```

</section>




</aside>




