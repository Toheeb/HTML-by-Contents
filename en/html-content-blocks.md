---
title: The 14 Content Blocks of HTML
canonical: https://www.toheeb.com/en/html-content-blocks/
book-hc: 7
---


<header>
<h1 id="content-block">The 14 Content Blocks of HTML</h1>

A Content Block builds a [Content Window](/en/html-content-windows/) with Topics and Paragraphs. Each Topic or Paragraph use a set of Text, [Objects,](/en/html-content-objects/) and [Forms,](/en/html-content-forms/) [Breaks,](/en/html-content-breaks/) and [Connotations.](/en/html-content-connotations/)


A Topic Block is either a Heading Block or a Title Block. Heading Blocks contribute to the document outline while Title Blocks don't. As a result, both Title Blocks and Paragraph Blocks follow an Heading Block in a [Content Part,](/en/html-content-parts/) optionally through a [Content Mix.](/en/html-content-mixes/)


<nav class="list-to-grid">
  <h2>Outline</h2>
    
  The 14 Content Blocks in 4 groups are as follows:

  - <span id="block-headings">Heading Blocks</span>

    - [L1 Heading](#heading-l1)

    - [L2 Heading](#heading-l2)

    - [L3 Heading](#heading-l3)

    - [L4 Heading](#heading-l4)

    - [L5 Heading](#heading-l5)

    - [L6 Heading](#heading-l6)


  - <span id="block-headings-secondary">Secondary Headings</span>

    - [Kicker Block](#block-kicker)

    - [Subheading Block](#block-subheading)


  - <span id="block-titles">Title Blocks</span>

    - [Details Title](#title-details)

    - [Fieldset Title](#title-fieldset)

    - [Column Title](#title-column)

    - [Association Title](#title-description)
    
  - <span id="block-paragraphs">Paragraph Blocks</span>

    - [Plain Paragraph](#paragraph-plain)

    - [Preformatted Paragraph](#paragraph-preformatted)

  Besides, two or more Plain Paragraphs can leverage a [Paragraph Separator](#paragraph-separator)

  Meanwhile, each Content Block can leverage the following utilities within or outside the block:

  - [Bitmap Version](#version-bitmap)

  - [Noscript Version](#version-noscript)
  
</nav>

</header>




<section>
  <h2 id="heading-l1">L1 Heading</h2>

  A Level One (L1) Heading creates a first-level [Content Section](/en/html-content-parts/#content-sections) with a topic

  The syntax is an [`h1` element](https://html.spec.whatwg.org/#the-h1,-h2,-h3,-h4,-h5,-and-h6-elements) with the following attributes and contents:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation](/en/html-content-connotations/)

  ```html
  <h1>

  </h1>
  ```
</section>



<section>
  <h2 id="heading-l2">L2 Heading</h2>

  A Level Two (L2) Heading creates a second-level [Content Section](/en/html-content-parts/#content-sections) with a topic

  The syntax is a [`h2` element](https://html.spec.whatwg.org/#the-h1,-h2,-h3,-h4,-h5,-and-h6-elements) with the following attributes and contents:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation](/en/html-content-connotations/)

  ```html
  <h2>

  </h2>
  ```
</section>



<section>
  <h2 id="heading-l3">L3 Heading</h2>

  A Level Three (L3) Heading creates a third-level [Content Section](/en/html-content-parts/#content-sections) with a topic

  The syntax is a [`h3` element](https://html.spec.whatwg.org/#the-h1,-h2,-h3,-h4,-h5,-and-h6-elements) that expects the following contents:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation](/en/html-content-connotations/)

  ```html
  <h3>

  </h3>
  ```
</section>



<section>
  <h2 id="heading-l4">L4 Heading</h2>

  A Level Four (L4) Heading creates a fourth-level [Content Section](/en/html-content-parts/#content-sections) with a topic

  The syntax is an [`h4` element](https://html.spec.whatwg.org/#the-h1,-h2,-h3,-h4,-h5,-and-h6-elements) with the following attributes and contents:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation](/en/html-content-connotations/)

  ```html
  <h4>

  </h4>
  ```
</section>



<section>
  <h2 id="heading-l5">L5 Heading</h2>

  A Level Five (L5) Heading creates a fifth-level [Content Section](/en/html-content-parts/#content-sections) with a topic

  The syntax is an [`h5` element](https://html.spec.whatwg.org/#the-h1,-h2,-h3,-h4,-h5,-and-h6-elements) with the following attributes and contents:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation](/en/html-content-connotations/)

  ```html
  <h5>

  </h5>
  ```
</section>



<section>
  <h2 id="heading-l6">L6 Heading</h2>

  A Level Six (h6) Heading creates a sixth-level [Content Section](/en/html-content-parts/#content-sections) with a topic

  The syntax is an [`h6` element](https://html.spec.whatwg.org/#the-h1,-h2,-h3,-h4,-h5,-and-h6-elements) with the following attributes and contents:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation](/en/html-content-connotations/)

  ```html
  <h6>

  </h6>
  ```
</section>






<section>
  <h2 id="block-kicker">kicker Block</h2>

  A kicker Block specifies a brief for an [Heading Block](#block-headings) 

  The syntax is an [`hgroup` element](https://html.spec.whatwg.org/#the-hgroup-element) with the following attributes and contents:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - The following order of elements  

    - One or more [Plain Paragraphs](#paragraph-plain) as kickers

    - One [Heading Block](#block-headings)

  ```html
  <hgroup>
    <p>

    </p>
    <h1>

    </h1>
  </hgroup>
  ```
</section>



<section>
  <h2 id="block-subheading">Subheading Block</h2>

  A Subheading Block specifies an elaboration for an [Heading Block](#block-headings) 

  The syntax is an [`hgroup` element](https://html.spec.whatwg.org/#the-hgroup-element) with the following attributes and contents:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - The following order of elements  

    - One [Heading Block](#block-headings)

    - One or more [Plain Paragraphs](#paragraph-plain) as Subheadings

  ```html
  <hgroup>
    <h1>

    </h1>
    <p>

    </p>
  </hgroup>
  ```
</section>






<section>
  <h2 id="title-details">Details Title</h2>

  A Details Title specifies a topic for a set of [additional contents](/en/html-content-parts/#segment-details) within a [section](/en/html-content-parts/#content-sections)

  The syntax is a [`summary` element](https://html.spec.whatwg.org/#the-summary-element) with the following attributes and contents:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation](/en/html-content-connotations/)

  ```html
  <summary>

  </summary>
  ```
</section>





<section>
  <h2 id="title-fieldset">Fieldset Title</h2>

  A Fieldset Title specifies a topic for a [segment](/en/html-content-parts/#segment-fieldset) of [forms](/en/html-content-forms/) in a [section](/en/html-content-parts/#content-sections)

  The syntax is a [`legend` element](https://html.spec.whatwg.org/#the-legend-element) with the following attributes and contents:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation](/en/html-content-connotations/)

  ```html
  <legend>

  </legend>
  ```
</section>






<section>
  <h2 id="title-column">Column Title</h2>

  A Column Title specifies a topic for subsequent [cells](/en/html-content-parts/#segment-cell) of a column in a [Tabular Layer](/en/html-content-mixes/#layer-tabular)

  The syntax is a [`th` element](https://html.spec.whatwg.org/#the-th-element) with the following attributes and contents:

  - Zero or one count for each of the following attributes: 
  [`abbr`,](/en/html-content-attributes#attribute-abbr)
  [`colspan`,](/en/html-content-attributes#attribute-colspan) 
  [`headers`,](/en/html-content-attributes#attribute-headers) 
  [`rowspan`,](/en/html-content-attributes#attribute-rowspan) and 
  [`scope`.](/en/html-content-attributes#attribute-scope)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation](/en/html-content-connotations/)

  ```html
  <th>

  </th>
  ```
</section>



<section>
  <h2 id="title-description">Association Title</h2>

  A Description Title specifies a topic for subsequent [descriptions](/en/html-content-parts/#segment-description) in a [Description Layer](/en/html-content-mixes/#layer-description)

  The syntax is a [`dt` element](https://html.spec.whatwg.org/#the-dt-element) with the following attributes and contents:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation](/en/html-content-connotations/)

  ```html
  <dt>

  </dt>
  ```
</section>



<section>
  <h2 id="paragraph-plain">Plain Paragraph</h2>

  A Plain Paragraph explains an [Heading Block](#block-headings) or a [Title Block](#block-titles) with contents that have <b>no</b> preserved spacings and line-breaks

  The syntax is a [`p` element](https://html.spec.whatwg.org/#the-p-element) with the following attributes and contents:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation](/en/html-content-connotations/)

  ```html
  <p>

  </p>
  ```
</section>



<section>
  <h2 id="paragraph-preformatted">Preformatted Paragraph</h2>

  A Preformatted Paragraph explains an [Heading Block](#block-headings) or a [Title Block](#block-titles) with contents that have preserved spacings and line-breaks

  The syntax is a [`pre` element](https://html.spec.whatwg.org/#the-pre-element) with the following attributes and contents:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation](/en/html-content-connotations/)

  ```html
  <pre>

  </pre>
  ```
</section>





<aside>
<h2>Utilities</h2>


<section>
  <h3 id="paragraph-separator">Paragraph Separator</h3>

  A Paragraph Separator represents a thematic change between [paragraphs](/en/html-content-blocks/#block-paragraph)

  The syntax is a void [`hr` element](https://html.spec.whatwg.org/#the-hr-element) with the following attributes:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <hr>
  ```
</section>


<section>
  <h3 id="version-bitmap">Bitmap Version</h3>

  A Bitmap Version relates a live image representation of contents

  The syntax is a [`canvas` element](https://html.spec.whatwg.org/#the-canvas-element) with the following attributes and contents:

  - Zero or one count for each of the following attributes: 
  
    - [`height`](/en/html-content-attributes/#attribute-height)

    - [`width`](/en/html-content-attributes/#attribute-width) 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more count for each element allowed in the parent element. But, no decendants of interactive elements except for the following: 

    - An [`a` element](/en/html-content-connotations/#card-a)

    - A [`button` element](/en/html-content-connotations/#card-button)

    - An [`img` element](#rimage-raster) with a [`usemap` attribute](/en/html-content-attributes/#attribute-usemap)

    - An [`input` element](/en/html-content-forms/#single-line-text) whose [`type` attribute](/en/html-content-attributes/#attribute-type) is one of the following values: 
    `button`,
    `checkbox`, 
    `image`, 
    `radio`, 
    `reset`, and 
    `submit`. 

    - A [`select` element](/en/html-content-forms/#multi-option-text) with a [`multiple` attribute](/en/html-content-attributes/#attribute-multiple) or a [`size` attribute](/en/html-content-attributes/#attribute-size) greater than 1


  ```html
  <canvas>
    
  </canvas>
  ```
</section>


<section>
  <h3 id="version-noscript">Noscript Version</h3>

  A Noscript Version specify alternate contents for a web document with no scripting functionality

  The syntax is a [`noscript` element](https://html.spec.whatwg.org/#the-noscript-element) with the following attributes and contents:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more count for each element allowed in the parent element. But, no descendant `noscript` elements.

  ```html
  <noscript>

  </noscript>
  ```
</section>

</aside>
