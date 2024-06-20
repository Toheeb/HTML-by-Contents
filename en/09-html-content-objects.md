---
title: The 9 Content Objects of HTML
canonical: https://www.toheeb.com/en/html-content-objects/
book-hc: 9
---


<header>

  <h1>The 9 Content Objects of HTML</h1>

  A Content Object inserts non-textual information within a [Content Block](/en/html-content-blocks/)

  <nav class="list-to-grid">
  <h2>Outline</h2>

  The 9 Content Objects are as follows:

  - [Vector Image](#image-vector)

  - [Raster Image](#image-raster)

  - [Audio Media](#media-audio)

  - [Video Media](#media-video)

  - [Text Track](#text-track)

  - [Math Document](#document-math)

  - [Web Document](#document-web)

  - [General Document](#document-general)

  - [Embed Medium](#medium-embed)

  </nav>
</header>



<section>
  <h2 id="image-vector">Vector Image</h2>

  A Vector Image embeds a scalable graphic resource

  The syntax is an `svg` element with the following attributes and child elements:

  - Zero or one count for each attribute defined in the [SVG namespace.](https://infra.spec.whatwg.org/#svg-namespace)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each element defined in the [SVG namespace.](https://infra.spec.whatwg.org/#svg-namespace)

  ```html
  <svg></svg>
  ```
</section>



<section>
  <h2 id="image-raster">Raster Image</h2>

  A Raster Image inserts an unscalable graphic resource

  The syntax is a void [`img` element]((https://html.spec.whatwg.org/#the-img-element)) with the following attributes:

  - One [`src` attribute](/en/html-content-attributes/#attribute-src)

  - Zero or one count for each of the following attributes: 
  [`alt`](/en/html-content-attributes/#attribute-alt), 
  [`crossorigin`](/en/html-content-attributes/#attribute-crossorigin), 
  [`decoding`](/en/html-content-attributes/#attribute-decoding), 
  [`fetchpriority`](/en/html-content-attributes/#attribute-fetchpriority), 
  [`height`](/en/html-content-attributes/#attribute-height)
  [`loading`](/en/html-content-attributes/#attribute-loading), 
  [`referrerpolicy`](/en/html-content-attributes/#attribute-referrerpolicy), 
  [`sizes`](/en/html-content-attributes/#attribute-sizes), 
  [`srcset`](/en/html-content-attributes/#attribute-srcset), 
  [`usemap`](/en/html-content-attributes/#attribute-usemap), and 
  [`width`](/en/html-content-attributes/#attribute-width).

  - One `sizes` attribute if the `srcset` attribute has a value that includes a width descriptor

  - Zero or one `sizes` attribute with an `auto` value if the following conditions are met:

    - There's no `srcset` attribute

    - The `loading` attribute has a `lazy` value

  - Zero or one [`ismap`](/en/html-content-attributes/#attribute-ismap) if there's an ancestor `a` element with an [`href`](/en/html-content-attributes/#attribute-href) attribute.

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <img src="[url]">
  ```

  Note: Each Raster Image may have a set of alternatives via a [`picture` element](#element-picture) or a set of clickable areas via a [Map Card](/en/html-content-mixes/#card-map)
</section>




<section>
  <h2 id="media-audio">Audio Media</h2>

  An Audio Media inserts a sound resource

  The syntax is an [`audio` element]((https://html.spec.whatwg.org/#the-audio-element)) with the following attributes and child elements:

  - Zero or one count for each of the following attributes: 
  [`autoplay`](/en/html-content-attributes/#attribute-autoplay), 
  [`controls`](/en/html-content-attributes/#attribute-controls).
  [`crossorigin`](/en/html-content-attributes/#attribute-crossorigin), 
  [`muted`](/en/html-content-attributes/#attribute-muted), 
  [`loop`](/en/html-content-attributes/#attribute-loop), 
  [`preload`](/en/html-content-attributes/#attribute-preload), and  
  [`src`](/en/html-content-attributes/#attribute-src).

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - The following order of elements:

    1. Zero or more [`source` elements](#element-source) if there is no `src` attribute

    2. Any order of the following element variants:

        - Zero or one [`track` element](#element-track) with a [`default` attribute](/en/html-content-attributes/#attribute-default) and a [`kind` attribute](/en/html-content-attributes/#attribute-kind) having a `captions` keyword or a `chapters` keyword

        - Zero or one `track` element with a `default` attribute and a `kind` attribute having a `descriptions` keyword

        - Zero or one `track` element with a `default` attribute and a `kind` attribute having a `chapters` keyword

        - Zero or more `track` elements

    3. Zero or one count for each element allowed in the parent of this [`audio` element.](#media-audio) But, it must exclude descendant of each of the following elements: `audio` and [`video`.](#media-video) Those elements acts as fallback content when the `audio` element is not supported by a user agent

    

  ```html
  <audio></audio>
  ```
</section>



<section>
  <h2 id="media-video">Video Media</h2>

  A Video Media insert moving images with or without a sound resource

  The syntax is a [`video` element]((https://html.spec.whatwg.org/#the-video-element)) with the following attributes and child elements:

  - Zero or one count for each of the following attributes: 

  - Zero or one count for each of the following attributes: 
  [`autoplay`](/en/html-content-attributes/#attribute-autoplay), 
  [`controls`](/en/html-content-attributes/#attribute-controls).
  [`crossorigin`](/en/html-content-attributes/#attribute-crossorigin), 
  [`height`](/en/html-content-attributes/#attribute-height), attributes.
  [`loop`](/en/html-content-attributes/#attribute-loop), 
  [`muted`](/en/html-content-attributes/#attribute-muted), 
  [`playsinline` attribute](/en/html-content-attributes/#attribute-playsinline), 
  [`poster` attribute](/en/html-content-attributes/#attribute-poster), 
  [`preload`](/en/html-content-attributes/#attribute-preload), and  
  [`src`](/en/html-content-attributes/#attribute-src).
  [`width`](/en/html-content-attributes/#attribute-width), and 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - The following order of elements:

    1. Zero or more [`source` elements](#element-source) if there is no `src` attribute

    2. Any order of the following element variants:

        - Zero or one [`track` element](#element-track) with a [`default` attribute](/en/html-content-attributes/#attribute-default) and a [`kind` attribute](/en/html-content-attributes/#attribute-kind) having a `captions` keyword or a `chapters` keyword

        - Zero or one `track` element with a `default` attribute and a `kind` attribute having a `descriptions` keyword

        - Zero or one `track` element with a `default` attribute and a `kind` attribute having a `chapters` keyword

        - Zero or more `track` elements

    3. Zero or more counts for each element allowed in the parent of this [`video` element.](#media-video) But, it must exclude descendant of each of the following elements: [`audio`](#media-audio) and `video`. Those elements acts as fallback content when the `audio` element is not supported by a user agent
    

  ```html
  <video></video>
  ```
</section>





<section>
  <h2 id="document-math">Math Document</h2>

  A Math Document embed mathematical notations

  The syntax is a [`math` element]((https://html.spec.whatwg.org/#the-math-element)) with the following attributes and child elements:

  - Zero or one count for each attribute defined in the [Math namespace.](https://infra.spec.whatwg.org/#svg-namespace)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each element defined in the [Math namespace.](https://infra.spec.whatwg.org/#svg-namespace)

  ```html
  <math></math>
  ```
</section>




<section>
  <h2 id="document-web">Web Document</h2>

  A Web Document inserts a navigable resource

  The syntax is an [`iframe` element](https://html.spec.whatwg.org/#the-iframe-element) with the following attributes and child elements:

  - Zero or one count for each of the following attributes: 
  [`allow`](/en/html-content-attributes/#attribute-allow), 
  [`allowfullscreen`](/en/html-content-attributes/#attribute-allowfullscreen), 
  [`height`](/en/html-content-attributes/#attribute-height), 
  [`loading`](/en/html-content-attributes/#attribute-loading), 
  [`referrerpolicy`](/en/html-content-attributes/#attribute-referrerpolicy), 
  [`srcdoc`](/en/html-content-attributes/#attribute-srcdoc), 
  [`sandbox`](/en/html-content-attributes/#attribute-sandbox),
  [`src`](/en/html-content-attributes/#attribute-src), and 
  [`width`](/en/html-content-attributes/#attribute-width). 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <iframe></iframe>
  ```
</section>




<section>
  <h2 id="document-general">General Document</h2>

  A General Document inserts other document types but as image if not supported by the user agent

  An Object Document relates a resource other than a [Raster Image](#image-raster), an [Audio Media](#media-audio), a [Video Media](#media-video), or a [Web Document](#document-web)

  The syntax is an [`object` element](https://html.spec.whatwg.org/#the-object-element) with the following attributes and child elements:

  - One [`data` attribute](/en/html-content-attributes/#attribute-data)

  - Zero or one count for each of the following attributes: 
  [`form`](/en/html-content-attributes/#attribute-form), 
  [`height`](/en/html-content-attributes/#attribute-height)
  [`name`](/en/html-content-attributes/#attribute-name), 
  [`type`](/en/html-content-attributes/#attribute-type), and 
  [`width`](/en/html-content-attributes/#attribute-width). 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or one count for each element allowed in the parent of this `object` element

  ```html
  <object data="[URL]"></object>
  ```
</section>




<section>
  <h2 id="medium-embed">Embed Medium</h2>

  An Embed Medium provides an integration point for plugins to insert a document

  The syntax is an [`embed` element]((https://html.spec.whatwg.org/#the-embed-element)) with the following attributes: 

  - Zero or one count for each of the following attributes: 
  [`height`](/en/html-content-attributes/#attribute-height),
  [`src`](/en/html-content-attributes/#attribute-src), 
  [`type`](/en/html-content-attributes/#attribute-type), and 
  [`width`](/en/html-content-attributes/#attribute-width). 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <embed>
  ```
</section>




<aside>
<h2>Utilities</h2>

A Content Object may use one or more of the following utility contents

<section>
  <h3 id="text-track">Text Track</h3>

  A Text Track inserts a moving text as an alternative for sounds in an [Audio Media](#media-audio) or in a [Video Media](#video-media)

  The syntax is a [`track` element]((https://html.spec.whatwg.org/#the-track-element)) with the following elements and attributes:

  - One of the following parent elements: `audio`, or `video`

  - One [`src` attribute](/en/html-content-attributes/#attribute-src)

  - Zero or one count for each of the following attributes: 
  [`default`,](/en/html-content-attributes/#attribute-default)
  [`kind`,](/en/html-content-attributes/#attribute-kind)  
  [`label`,](/en/html-content-attributes/#attribute-label) and 
  [`srclang`.](/en/html-content-attributes/#attribute-srclang)

  - One `srclang` attribute if the `kind` attribute has the `subtitles` keyword.

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <audio>
    <track src="[URL]">
  </audio>

  <!-- or -->

  <video>
    <track src="[URL]">
  </video>
  ```
</section>


<section>
  <h3 id="element-picture">Picture Wrapper</h3>

  A Picture Wrapper provide alternatives for a [Raster Image](#image-raster)

  The syntax is a `picture` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - The following order of child elements, optionally intermixed with [script-supporting content](https://html.spec.whatwg.org/#script-supporting-elements): 

    1. Zero or more [`source` elements](#element-source) 

    2. One [`img` element](#image-raster)
  
  ```html
  <picture>
    <img src="">
  </picture>
  ```
</section>


<section>
  <h3 id="element-source">Source Component</h3>

  A Source Component specifies an alternative [Raster Image](#image-raster), [Audio Media](#media-audio), or [Video Media.](#media-video)

  The syntax is a [`source` element](https://html.spec.whatwg.org/#the-source-element) with the following attributes:

  - One [`src` attribute](/en/html-content-attributes/#attribute-src) if the parent element is an Audio Media or a Video Media

  - Zero or one count for each of the following attributes. But, one or both if the parent is a [Picture Container](#container-picture) and it has a sibling Source Component or Raster Image with a `srcset` attribute

    - [`type` attribute](/en/html-content-attributes/#attribute-type)

    - [`media` attribute](/en/html-content-attributes/#attribute-media)

  - One [`srcset` attribute](/en/html-content-attributes/#attribute-srcset) if the parent is a Picture Container

  - Zero or one count for each of the following attributes if the parent is a Picture Container

    - [`width` attribute](/en/html-content-attributes/#attribute-width)

    - [`height` attribute](/en/html-content-attributes/#attribute-height)

  - One [`sizes` attribute](/en/html-content-attributes/#attribute-sizes) if all of the following conditions are met. But, optional, if only the first option is met.

    1. The `srcset` attribute has a value that includes a width descriptor

    2. The sibling `img` element does not allow the following [auto-sizing attributes](https://html.spec.whatwg.org/#allows-auto-sizes) and values:
 
       - One `loading` attribute with a `lazy` value

       - One `sizes` attribute with an "auto" value or starts with an "auto, " value
 
  ```html
  <picture>
    <source srcset="[IMS]">
  </picture>
  
  <audio>
    <source src="[URL]">
  </audio>

  <video>
    <source src="[URL]">
  </video>
  ```
</section>

</aside>
