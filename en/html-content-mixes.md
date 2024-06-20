---
title: The 13 Content Mixes of HTML
canonical: https://www.toheeb.com/en/html-content-mixes/
book-hc: 6
---


<header>

  <h1>The 13 Content Mixes of HTML</h1>

  A Content Mix specifies a set of [Content Blocks,](/en/html-content-blocks/) called passage, for a [Content Part.](/en/html-content-parts/) 

  A simple Content Mix is a Content Card while a compound Content Mix is a Content Layer


  <nav class="list-to-grid">
  <h2>Outline</h2>

  The 13 Content Mixes in 2 groups are as follows:

  - Content Cards

    - [General Card](#card-general)

    - [Anchor Card](#card-anchor)

    - [Quote Card](#card-quote)

    - [Address Card](#card-address)

    - [Deletion Card](#card-deletion)

    - [Insertion Card](#card-insertion)

    - [Figure Card](#card-figure)

    - [Map Card](#card-map)

    - [Search Card](#card-search)

    - [Form Card](#card-form)

  - Content Layers

    - [Enumeration Layer](#layer-enumeration)

    - [Description Layer](#layer-description)

    - [Tabular Layer](#layer-tabular)

  </nav>
</header>




<section>
<h2 id="card-general">General Card</h2>

A General Card represents a passage with no initial purpose

The syntax is a [`div` element](https://html.spec.whatwg.org/#the-div-element) with the following attributes and child elements:

- Zero or one count for each [Global Attribute](/en/html-content-attributes#global-list)

- The following order of elements if the General Card is a child of an [Description Layer](#layer-description):

  1. One or more [Association Titles](/en/html-content-blocks/#title-association)

  2. One or more [Association Segments](/en/html-content-parts/#segment-association)

- Zero or more counts for each  and  if the Span Card is not a child of an [Description Layer](#layer-description)

- Zero or more counts for each [Content Block](/en/html-content-blocks/) and [Content Mix.](/en/html-content-mixes/) But, if the General Card is not a child of an Description Layer

```html
<div>

</div>
```
</section>



<section>
<h2 id="card-anchor">Anchor Card</h2>

An Anchor Card represents a passage that is a label for an hyperlink

The syntax is an [`a` element](https://html.spec.whatwg.org/#the-a-element) with the following attributes and child elements:

- Zero or one [`href` attribute](/en/html-content-attributes#attribute-href)

- Zero or one count for each of the following attributes if the `href` attribute is present:

  - [`target`](/en/html-content-attributes#attribute-target)

  - [`download`](/en/html-content-attributes#attribute-download)

  - [`ping`](/en/html-content-attributes#attribute-ping)

  - [`rel`](/en/html-content-attributes#attribute-rel)

  - [`hreflang`](/en/html-content-attributes#attribute-hreflang)

  - [`type`](/en/html-content-attributes#attribute-type)

  - [`referrerpolicy`](/en/html-content-attributes#attribute-referrerpolicy)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more counts for each [Content Block](/en/html-content-blocks/) and [Content Mix.](/en/html-content-mixes/) But, it must exclude a [Details Title](/en/html-content-blocks/#title-details), an Anchor Card, and any Content with a [`tabindex` attribute](/en/html-content-attributes/#attribute-tabindex)

  Moreso, Each Content Block must exclude the following descendant [interactive contents](https://html.spec.whatwg.org/#interactive-content):


  - An [Hyperlink Connotation](/en/html-content-connotation/#connotation-hyperlink) with an [`href` attribute](/en/html-content-attributes#attribute-href)

  - A [Raster Image](/en/html-content-objects/#image-raster) with a [`usemap` attribute](/en/html-content-attributes#attribute-usemap)

  - An [Audio Media](/en/html-content-objects/#media-audio) with a [`controls` attribute](/en/html-content-attributes#attribute-controls)

  - A [Video Media](/en/html-content-objects/#media-video) with a [`controls` attribute](/en/html-content-attributes#attribute-controls)

  - An [Embed Medium](/en/html-content-objects/#medium-embed)

  - A [Web Document](/en/html-content-objects/#document-web)

  - Each [Content Form](/en/html-content-forms/)

  - A [Label Connotation](/en/html-content-connotations/#connotation-label)


```html
<a>

</a>
```
</section>



<section>
<h2 id="card-quote">Quote Card</h2>

A Quote Card represents a passage from another source

The syntax is a [`blockquote` element](https://html.spec.whatwg.org/#the-blockquote-element) with the following attributes and child elements:

- Zero or one [`cite` attribute](/en/html-content-attributes#attribute-cite).

- Zero or one count for each [Global Attribute](/en/html-content-attributes#global-list)

- Zero or more counts for each [Content Block](/en/html-content-blocks/) and [Content Mix.](/en/html-content-mixes/)

```html
<blockquote>

</blockquote>
```
</section>



<section>
<h2 id="card-address">Address Card</h2>

An Address Card represents a passage of contact information for authors of the nearest ancestor [Article Section.](/en/html-content-parts/#section-article) If no such ancestor, it's for authors of the web document

The syntax is an [`address` element](https://html.spec.whatwg.org/#the-address-element) with the following attributes and child elements:

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more counts for each [Content Block](/en/html-content-blocks/) and [Content Mix.](/en/html-content-mixes/) But, an Address Card must exclude an [Heading Block](/en/html-content-blocks/#block-headings) and an Address Card

- Zero or more counts for each [Content Block](/en/html-content-blocks/) and [Content Mix.](/en/html-content-mixes/) But, it must exclude descendants of each [Content Division](/en/html-content-parts/#content-divisions)


```html
<address>

</address>
```
</section>




<section>
<h2 id="card-deletion">Deletion Card</h2>

A Deletion Card represents a passage with a removal hint

The syntax is a [`del` element](https://html.spec.whatwg.org/#the-del-element) with the following attributes and child elements:

- Zero or one count for each of the following attributes: 

  - [`cite`](/en/html-content-attributes#attribute-cite)
  
  - [`datetime`](/en/html-content-attributes#attribute-datetime)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more counts for each [Content Block](/en/html-content-blocks/) and [Content Mix.](/en/html-content-mixes/)

```html
<del>

</del>
```
</section>


<section>
<h2 id="card-insertion">Insertion Card</h2>

An Insertion Card represents a passage with an addition hint

The syntax is an [`ins` element](https://html.spec.whatwg.org/#the-ins-element) with the following attributes and child elements:

- Zero or one count for each of the following attributes: 

  - [`cite`](/en/html-content-attributes#attribute-cite) 
  
  - [`datetime`](/en/html-content-attributes#attribute-datetime)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more counts for each [Content Block](/en/html-content-blocks/) and [Content Mix.](/en/html-content-mixes/)

```html
<ins>

</ins>
```
</section>




<section>
<h3 id="card-figure">Figure Card</h3>

A Figure Card represents a passage with no running text.

The syntax is a [`figure` element](https://html.spec.whatwg.org/#the-figure-element) with the following attributes and child elements:

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more counts for each [Content Block](/en/html-content-blocks/) and [Content Mix.](/en/html-content-mixes/)

- Zero or One [Figure Caption Card.](#card-figure-caption) But, as the first or last content of a Figure Card.

```html
<figure>

</figure>
```
</section>






<section>
<h2 id="card-map">Map Card</h2>

A Map Card represents a passage with a set of [area coordinates](#card-map-area) for managing regions of a [raster image](/en/html-content-objects/#image-raster). 

The syntax is a [`map` element](https://html.spec.whatwg.org/#the-map-element) with the following attributes and child elements:

- One [`name` attribute](/en/html-content-attributes/#attribute-name)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more counts for each [Content Block](/en/html-content-blocks/) and [Content Mix.](/en/html-content-mixes/)

```html
<map name="[identifier]">

</map>
```
</section>




<section>
<h2 id="card-search">Search Card</h2>

A Search Card represents a passage with a set of [Content Forms](/en/html-content-forms/) for discovering information

The syntax is a [`search` element](https://html.spec.whatwg.org/#the-search-element) with the following attributes and child elements:

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more counts for each [Content Block](/en/html-content-blocks/) and [Content Mix.](/en/html-content-mixes/) 

```html
<search>

</search>
```
</section>



<section>
<h2 id="card-form">Form Card</h2>

A Form Card represents an hyperlink to submit associated [Content Forms.](/en/html-content-forms/) A Content Form associates to a Form Card as a child content or by targeting the Card's ID

The syntax is a [`form` element](https://html.spec.whatwg.org/#the-form-element) with the following attributes and child elements:

- Zero or one count for each of the following attributes: 
[`accept-charset`](/en/html-content-attributes/#attribute-accept-charset), 
[`action`](/en/html-content-attributes/#attribute-action), 
[`autocomplete`](/en/html-content-attributes/#attribute-autocomplete), 
[`enctype`](/en/html-content-attributes/#attribute-enctype), 
[`method`](/en/html-content-attributes/#attribute-method), 
[`name`](/en/html-content-attributes/#attribute-name), 
[`novalidate`](/en/html-content-attributes/#attribute-novalidate), 
[`target`](/en/html-content-attributes/#attribute-target), and 
[`rel`](/en/html-content-attributes/#attribute-rel).

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more counts for each [Content Block](/en/html-content-blocks/) and [Content Mix.](/en/html-content-mixes/) 

```html
<form>

</form>
```
</section>




<section>
<h2 id="layer-enumeration">Enumeration Layer</h2>

An Enumeration Layer represents a passage as an item in an ordered list (`ol`), unordered list (`ul`), or unordered command list (`menu`)

The syntax is an [`ol` element](https://html.spec.whatwg.org/#the-ol-element), [`ul` element](https://html.spec.whatwg.org/#the-ul-element), or [`menu` element](https://html.spec.whatwg.org/#the-menu-element) with the following attributes and child elements

- Zero or one count for each of the following attributes if it's an `ol` element: 
[`reversed`](/en/html-content-attributes/#attribute-reversed),
[`start`](/en/html-content-attributes/#attribute-start), and 
[`type`](/en/html-content-attributes/#attribute-type).

- Zero or more [List Items](#list-item)


```html
<!-- ordered list -->
<ol>

</ol>

<!-- unordered list -->
<ul>

</ul>

<!-- unordered command list -->
<menu>

</menu>
```
</section>



<section>
<h2 id="layer-description">Description Layer</h2>

An Description Layer represents a passage and its title as an item in an unordered term-description list

The syntax is a [`dl` element](https://html.spec.whatwg.org/#the-dl-element) with the following attributes and child elements:

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more groups of the following elements:

  1. One or more [Association Titles](/en/html-content-blocks/#title-association)

  2. One or more [Association Segments](/en/html-content-parts/#segment-association)

  Note: Each group can be explicitly marked up with a [General Card](#card-general)

```html
<dl>

</dl>
```
</section>




<section>
<h2 id="layer-tabular">Tabular Layer</h2>

A Tabular Layer represents a passage as a cell in a 2 dimensional content

The syntax is a [`table` element]((https://html.spec.whatwg.org/#the-table-element)) with the following attributes and child elements:

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- The following order of elements optionally intermixed with [script-supporting content](https://html.spec.whatwg.org/#script-supporting-elements)

  1. Zero or one [Table Caption](#table-caption)

  2. Zero or more [Table Column Group](#table-column-group)

  3. Zero or one [Table Head](#table-head)

  4. Either of the following elements:

      - Zero or more [Table Body](#table-body)

      - Zero or more [Table Rows](#table-row)

  5. Zero or one [Table Foot](#table-foot)


```html
<table>

</table>
```
</section>







<aside>
<h2>Utilities</h2>



<section>
<h3 id="card-figure-caption">Figure Caption Card</h3>

A Figure Caption Card provides the running text that describes the content of a [Figure Card](#card-figure)

The syntax is a [`figcaption` element](https://html.spec.whatwg.org/#the-figcaption-element) with the following attributes and elements:

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more counts for each [Content Block](/en/html-content-blocks/) and [Content Mix.](/en/html-content-mixes/)

```html
<figcaption>

</figcaption>
```
</section>



<section>
<h3 id="card-map-area">Map Area</h3>

A Map Area specifies the coordinates of a region on a [raster image](/en/html-content-objects/#image-raster) within a [Map Card](#card-map)

The syntax is a void [`area` element](https://html.spec.whatwg.org/#the-area-element) with the following attributes and elements:

- An ancestor [`map` element](#card-map)

- Zero or one count for each of the following attributes: 
[`coords`](/en/html-content-attributes/#attribute-coords),
[`href`](/en/html-content-attributes/#attribute-href), and 
[`shape`](/en/html-content-attributes/#attribute-shape).

- One [`alt` attribute](/en/html-content-attributes/#attribute-alt) if the `href` attribute is present.

- Zero or one count for each of the following attributes if the `href` attribute is present: 
[`download`](/en/html-content-attributes/#attribute-download), 
[`ping`](/en/html-content-attributes/#attribute-ping), 
[`rel`](/en/html-content-attributes/#attribute-rel), 
[`referrerpolicy`](/en/html-content-attributes/#attribute-referrerpolicy), and 
[`target`](/en/html-content-attributes/#attribute-target). 

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<map name="[ID]">
  <area>
</map>
```  
</section>



<section>
<h3 id="list-item">List Item</h3>

A List Item represents a unit of passage in an [Enumeration Layer](#layer-enumeration)

The syntax is an [`li` element](https://html.spec.whatwg.org/#the-li-element) with the following attributes and child elements:

- Zero or one [`value` attribute.](/en/html-content-attributes#attribute-value) But, the parent must be an `ol` element.

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more counts for each [Content Block](/en/html-content-blocks/) and [Content Mix.](/en/html-content-mixes/)

```html
<li>

</li>
```
</section>



<section>
<h3 id="table-caption">Table Caption</h3>

A Table Caption describes the contents of a [Tabular Layer](#layer-tabular)

The syntax is a [`caption` element](https://html.spec.whatwg.org/#the-caption-element) with the following attributes and child elements:

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more counts for each [Content Block](/en/html-content-blocks/) and [Content Mix.](/en/html-content-mixes/) But, it must exclude descendant Tabular Layers


```html
<caption>

</caption>
```
</section>



<section>
<h3 id="table-column-group">Table Column Group</h3>
A Table Column Group targets one or more columns in a [Tabular Layer](#layer-tabular)

The syntax is a [`colgroup` element](https://html.spec.whatwg.org/#the-colgroup-element) with the following attributes and child elements:

- Zero or one [`span` attribute](/en/html-content-attributes#attribute-span)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more [Table Column Items](#table-column-item) if there's no `span` attribute

```html
<colgroup></colgroup>
```
</section>



<section>
<h3 id="table-column-item">Table Column Item</h3>

A Table Column Item targets a column in a [Column Group](#table-column-group)

The syntax is a void [`col` element](https://html.spec.whatwg.org/#the-col-element) with the following attributes:

- Zero or one [`span` attribute](/en/html-content-attributes#attribute-span)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<col>
```
</section>


<section>
<h3 id="table-head">Table Head</h3>

A Table Head identifies a set of rows of [Column Titles](/en/html-content-blocks/#title-column) in a [Tabular Layer](#layer-tabular)

The syntax is a [`thead` element](https://html.spec.whatwg.org/#the-thead-element) with the following attributes and child elements:

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more counts for [Table Rows](#table-row)

```html
<thead>

</thead>
```
</section>



<section>
<dt id="table-body">Table Body</dt>

A Table Body identifies a set of rows of [Cell Segments](/en/html-content-parts/#segment-cell) in a [Tabular Layer](#layer-tabular)

The syntax is a [`tbody` element](https://html.spec.whatwg.org/#the-tbody-element) with the following attributes and child elements:

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more counts for [Table Rows](#table-row)

```html
<tbody>

</tbody>
```
</section>


<section>
<h3 id="table-foot">Table Foot</h3>

A Table Foot identifies a set of rows of supplementary [Cell Segments](/en/html-content-parts/#segment-cell) in a [Tabular Layer](#layer-tabular)

The syntax is a [`tfoot` element](https://html.spec.whatwg.org/#the-tfoot-element) that expects the following attributes and child elements:

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more counts for [Table Rows](#table-row)

```html
<tfoot></tfoot>
```  
</section>


<section>
<dt id="table-row">Table Row</dt>

A Table Row identifies a set of [Column Titles](/en/html-content-blocks/#title-column) or [Cell Segments](/en/html-content-parts/#segment-cell) in a [Tabular Layer](#layer-tabular)

The syntax is a [`tr` element](https://html.spec.whatwg.org/#the-tr-element) that expects the following attributes and child elements:

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more counts of [Column Titles](/en/html-content-blocks/#title-column) or [Cell Segments](/en/html-content-parts/#segment-cell)

```html
<tr></tr>
```
</section>


</aside>