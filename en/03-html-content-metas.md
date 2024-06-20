---
title: The 33 Content Metas of HTML
canonical: https://www.toheeb.com/en/html-content-metas/
book-hc: 3
---


 
<header>
  <h1 id="metadata">The 33 Content Metas of HTML</h1>

  A Content Meta specify data about the data in [Content Windows](/en/html-content-windows/)

  Each Content Meta must be declared within the [Head Container](#container-head)


  <nav class="list-to-grid" id="outline">
  <h2>Outline</h2>

  The 33 Content Metas are as follows:

  - [Charset Meta](#meta-charset)
  
  - [Title Meta](#meta-title)  
  
  - [URL Meta](#meta-url)

  - [Target Meta](#meta-target)

  - [Canonical Meta](#meta-canonical) 

  - [Icon Meta](#meta-icon)

  - [Description Meta](#meta-description) 

  - [Keywords Meta](#meta-keywords)

  - [Author Meta](#meta-author)

  - [Generator Meta](#meta-generator)

  - [Translation Meta](#meta-translation)

  - [Repurposing Meta](#meta-repurposing)

  - [Next Meta](#meta-next)

  - [Search Meta](#meta-search)

  - [Referrer Meta](#meta-referrer)

  - [Security Meta](#meta-security)

  - [Timeout Meta](#meta-timeout)

  - [Name Meta](#meta-name)

  - [Manifest Meta](#meta-manifest)

  - [Pingback Meta](#meta-pingback)

  - [Feed Meta](#meta-feed)

  - [Theme Meta](#meta-theme)

  - [Scheme Meta](#meta-scheme)

  - [Template Meta](#meta-template)

  - [Font Meta](#meta-font) 

  - [Image Meta](#meta-image)

  - [Media Meta](#meta-media)

  - [Track Meta](#meta-track)

  - [Document Meta](#meta-document)

  - [Stylesheet Meta](#meta-stylesheet)

  - [Script Meta](#meta-script)

  - [Custom-Text Meta](#meta-custom-text)

  - [Custom-Link Meta](#meta-custom-link)

  These Content Metas leverage the following containers: 

  - [Head Container](/en/html-content-metas/#container-head)

  - [Noscript Container](/en/html-content-metas/#container-noscript)

  </nav>
</header>



<section>
<h2 id="meta-charset">Charset Meta</h2>

The Charset Meta specifies the character encoding for a web document.

The syntax is one void [`meta` element](https://html.spec.whatwg.org/#the-meta-element) per document with either of the following attributes:

- One [`charset` attribute](/en/html-content-attributes/#attribute-charset) with the `utf-8` value

- Both of the following attributes:

  - [`http-equiv` attribute](/en/html-content-attributes/#attribute-name) with the `content-type` value 

  - [`content` attribute](/en/html-content-attributes/#attribute-content) with the "text/html; charset=utf-8" value

```html
<meta charset="utf-8">

<!-- or -->

<meta http-equiv="content-type" content="text/html; charset=utf-8">
```

</section>


<section>
<h2 id="meta-title">Title Meta</h2>

The Title Meta specifies an elaboration of the document name. 

A document must have a Title Meta, except for each of the following cases:

- The document is an [`iframe` element](/en/html-content-objects/#element-iframe) with a [`srcdoc` attribute](/en/html-content-attributes/#attribute-srcdoc)

- The title information is available from a higher-level protocol


The syntax is one [`title` element](https://html.spec.whatwg.org/#the-title-element) per document with the following attributes and content:

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- A non-empty text content

```html
<title> [non-empty text] </title>
```

</section>


<section>
<h2 id="meta-url">URL Meta</h2>

The URL Meta specifies a prefix for all non-schemed URLs in a web document. 

This meta must precede elements with attributes that accept URLs.

The syntax is one void [`base` element](https://html.spec.whatwg.org/#the-base-element) per document with the following attributes:

- Zero or one [`href` attribute](/en/html-content-attributes/#attribute-href)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<base href="[URL]">
```

</section>


<section>
<h2 id="meta-target">Target Meta</h2>

The Target Meta specifies the default opening context for all URLs in a web document.

This Meta must precede elements that represent hyperlinks

The syntax is one void [`base` element](https://html.spec.whatwg.org/#the-base-element) per document with the following attributes:

- Zero or one [`target` attribute](/en/html-content-attributes/#attribute-target)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<base href="[navigable-name-or-keyword]">
```

</section>



<section>
<h2 id="meta-canonical">Canonical Meta</h2>

A Canonical Meta specifies the document as a duplicate to an external resource.

The syntax is a one void [`link` element](https://html.spec.whatwg.org/#the-link-element) per document with the following attributes:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) with the `canonical` keyword. 

- One [`href` attribute](/en/html-content-attributes/#attribute-href)

- Zero or one count for each of the following attributes: 
  - [`hreflang`](/en/html-content-attributes/#attribute-hreflang)
  
  - [`media`](/en/html-content-attributes/#attribute-media) 
  
  - [`type`](/en/html-content-attributes/#attribute-type)

- Zero or one count for the [`title` attribute](/en/html-content-attributes/#attribute-title) and each other [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<link rel="canonical" href="[resource-url]">
```
</section>


<section>
<h2 id="meta-icon">Icon Meta</h2>

An Icon Meta specifies a graphic resource that identifies a web document in the browser chrome. 

The syntax is a void [`link` element](https://html.spec.whatwg.org/#the-link-element) with the following attributes:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) with the `icon` keyword

- One [`href` attribute](/en/html-content-attributes/#attribute-href)

- Zero or one count for each of the following attributes: 

  - [`crossorigin`](/en/html-content-attributes/#attribute-crossorigin)
  
  - [`fetchpriority`](/en/html-content-attributes/#attribute-fetchpriority)
  
  - [`hreflang`](/en/html-content-attributes/#attribute-hreflang)
  
  - [`media`](/en/html-content-attributes/#attribute-media)
  
  - [`type`](/en/html-content-attributes/#attribute-type)
  
  - [`referrerpolicy`](/en/html-content-attributes/#attribute-referrerpolicy)
  
  - [`sizes`](/en/html-content-attributes/#attribute-sizes)

- Zero or one count for the [`title` attribute](/en/html-content-attributes/#attribute-title) and each other [Global Attribute](https://html.spec.whatwg.org/#global-attributes)


```html
<link rel="icon" href="[resource-url]">
```
</section>


<section>
<h2 id="meta-description">Description Meta</h2>

The Description Meta summarizes the information in Content Windows.

The syntax is a one void [`meta` element](https://html.spec.whatwg.org/#the-meta-element) per document with the following attributes:

- One [`name` attribute](/en/html-content-attributes/#attribute-name) with the `description` value

- One [`content` attribute](/en/html-content-attributes/#attribute-content)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<meta name="description" content="[value]">
```

 

</section>


<section>
<h2 id="meta-keywords">Keywords Meta</h2>

A Keywords Meta specifies a set of words that represent information in Content Windows.

The syntax is a void [`meta` element](https://html.spec.whatwg.org/#the-meta-element) with the following attributes:

- One [`name` attribute](/en/html-content-attributes/#attribute-name) with the `keywords` value

- One [`content` attribute](/en/html-content-attributes/#attribute-content)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<meta name="keywords" content="[value]">
```
</section>



<section>
<h2 id="meta-author">Author Meta</h2>

An Author Meta specifies the name of the author of a web document.

The syntax is a void [`meta` element](https://html.spec.whatwg.org/#the-meta-element) with the following attributes:

- One [`name` attribute](/en/html-content-attributes/#attribute-name) with the `author` value

- One [`content` attribute](/en/html-content-attributes/#attribute-content)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<meta name="author" content="[value]">
```
</section>


<section>
<h2 id="meta-generator">Generator Meta</h2>

A Generator Meta specifies the name of a software that generates a part or the whole of a web document.

The syntax is a void [`meta` element](https://html.spec.whatwg.org/#the-meta-element) with the following attributes:

- One [`name` attribute](/en/html-content-attributes/#attribute-name) with the `generator` value

- One [`content` attribute](/en/html-content-attributes/#attribute-content)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<meta name="generator" content="[value]">
```
</section>


<section>
<h2 id="meta-translation">Translation Meta</h2>

A Translation Meta specifies a version of the current document in another language.

The syntax is a void [`link` element](https://html.spec.whatwg.org/#the-link-element) with the following attributes:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) with the `alternate` keyword

- One [`href` attribute](/en/html-content-attributes/#attribute-href)

- One [`hreflang`](/en/html-content-attributes/#attribute-hreflang) attribute with a language different from that of the document

- Zero or one count for each of the following attributes: 

  - [`media`](/en/html-content-attributes/#attribute-media)

  - [`type`](/en/html-content-attributes/#attribute-type)  

- Zero or one count for the [`title` attribute](/en/html-content-attributes/#attribute-title) and each other [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<link rel="alternate" hreflang="[not-document-language]" href="[resource-url]">
```
</section>


<section>
<h2 id="meta-repurposing">Repurposing Meta</h2>

A Repurposing Meta specifies a version of the current document in another format.

The syntax is a void [`link` element](https://html.spec.whatwg.org/#the-link-element) with the following attributes:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) with the `alternate` keyword

- One [`href` attribute](/en/html-content-attributes/#attribute-href)

- One [`type` attribute](/en/html-content-attributes/#attribute-type) without the `application/rss+xml` value or the `application/atom+xml` value.

- Zero or one count for each of the following attributes: 

  - [`hreflang`](/en/html-content-attributes/#attribute-hreflang) 

  - [`media`](/en/html-content-attributes/#attribute-media)

- Zero or one count for the [`title` attribute](/en/html-content-attributes/#attribute-title) and each other [Global Attribute](https://html.spec.whatwg.org/#global-attributes)


```html
<link rel="alternate" href="[URL]" type="[valid-MIME-TYPE]">
```
</section>



<section>
<h2 id="meta-next">Next Meta</h2>

A Next Meta specifies a resource that is next in sequence to the current document.

The syntax is a void [`link` element](https://html.spec.whatwg.org/#the-link-element) with the following attributes:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) with the `next` keyword

- One [`href` attribute](/en/html-content-attributes/#attribute-href)

- Zero or one count for each of the following attributes: 

  - [`hreflang`](/en/html-content-attributes/#attribute-hreflang)

  - [`media`](/en/html-content-attributes/#attribute-media) 

  - [`type`](/en/html-content-attributes/#attribute-type)

- Zero or one count for the [`title` attribute](/en/html-content-attributes/#attribute-title) and each other [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<link rel="next" href="[resource-url]">
```
</section>


<section>
<h2 id="meta-search">Search Meta</h2>

A Search Meta relates an external resource to discover the contents of the current document. 

The syntax is a void [`link` element](https://html.spec.whatwg.org/#the-link-element) with the following attributes:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) with the `search` keyword

- One [`href` attribute](/en/html-content-attributes/#attribute-href)

- Zero or one count for each of the following attributes: 

  - [`hreflang`](/en/html-content-attributes/#attribute-hreflang)

  - [`media`](/en/html-content-attributes/#attribute-media) 

  - [`type`](/en/html-content-attributes/#attribute-type)

- Zero or one count for the [`title` attribute](/en/html-content-attributes/#attribute-title) and each other [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<link rel="search" href="[resource-url]">
```
</section>


<section>
<h2 id="meta-referrer">Referrer Meta</h2>

A Referrer Meta specifies the default referrer policy of a web document.

The syntax is a void [`meta` element](https://html.spec.whatwg.org/#the-meta-element) with the following attributes:

- One [`name` attribute](/en/html-content-attributes/#attribute-name) with the `referrer` value

- One [`content` attribute](/en/html-content-attributes/#attribute-content)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<meta name="referrer" content="[value]">
```
</section>


<section>
<h2 id="meta-security">Security Meta</h2>

The Security Meta specifies a policy to secure the content of a web document.

The syntax is one void [`meta` element](https://html.spec.whatwg.org/#the-meta-element) per document with the following attributes:

- One [`http-equiv` attribute](/en/html-content-attributes/#attribute-name) with the `content-security-policy` value

- One [`content` attribute](/en/html-content-attributes/#attribute-content)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<meta http-equiv="content-security-policy" content="[value]">
```

</section>


<section>
<h2 id="meta-timeout">Timeout Meta</h2>

The Timeout Meta specifies the time to redirect a web document.

The syntax is one void [`meta` element](https://html.spec.whatwg.org/#the-meta-element) per document with the following attributes:

- One [`http-equiv` attribute](/en/html-content-attributes/#attribute-name) with the `refresh` value

- One [`content` attribute](/en/html-content-attributes/#attribute-content)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<meta http-equiv="refresh" content="[value]">
```

</section>




<section>
<h2 id="meta-name">Name Meta</h2>

The Name Meta specifies the name of the application in a web document.

The syntax is one void [`meta` element](https://html.spec.whatwg.org/#the-meta-element) per document with the following attributes: 

- One [`name` attribute](/en/html-content-attributes/#attribute-name) with the `application-name` value

- One [`content` attribute](/en/html-content-attributes/#attribute-content)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<meta name="application-name" content="[value]">
```

</section>


<section>
<h2 id="meta-manifest">Manifest Meta</h2>

A Manifest Meta specifies a JSON resource that provides information about the web application in a web document. 

The syntax is a void [`link` element](https://html.spec.whatwg.org/#the-link-element) with the following attributes:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) with a `manifest` keyword. And, an optional `preload` keyword

- One [`href` attribute](/en/html-content-attributes/#attribute-href)

- One [`as` attribute](/en/html-content-attributes/#attribute-as) with a `manifest` value if the `preload` keyword is in the `rel` attribute.

- Zero or one count for each of the following attributes: 

  - [`crossorigin`](/en/html-content-attributes/#attribute-crossorigin)

  - [`fetchpriority`](/en/html-content-attributes/#attribute-fetchpriority)

  - [`hreflang`](/en/html-content-attributes/#attribute-hreflang)

  - [`media`](/en/html-content-attributes/#attribute-media)

  - [`referrerpolicy`](/en/html-content-attributes/#attribute-referrerpolicy)

  - [`type`](/en/html-content-attributes/#attribute-type)

- Zero or one [`integrity` attribute](/en/html-content-attributes/#attribute-integrity) if the `preload` keyword is in the `rel` attribute

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<link rel="manifest" href="[url]">
```
</section>



<section>
<h2 id="meta-pingback">Pingback Meta</h2>

A Pingback Meta relates a server resource to handle pingbacks to a web document

The syntax is a void [`link` element](https://html.spec.whatwg.org/#the-link-element) with the following attributes:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) with the `pingback` keyword

- One [`href` attribute](/en/html-content-attributes/#attribute-href)

- Zero or one count for each of the following attributes: 

  - [`crossorigin`](/en/html-content-attributes/#attribute-crossorigin)

  - [`fetchpriority`](/en/html-content-attributes/#attribute-fetchpriority)

  - [`hreflang`](/en/html-content-attributes/#attribute-hreflang)

  - [`media`](/en/html-content-attributes/#attribute-media)

  - [`referrerpolicy`](/en/html-content-attributes/#attribute-referrerpolicy)

  - [`type`](/en/html-content-attributes/#attribute-type)

- Zero or one count for the [`title` attribute](/en/html-content-attributes/#attribute-title) and each other [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<link rel="pingback" href="[url]">
```
</section>


<section>
<h2 id="meta-feed">Feed Meta</h2>

A Feed Meta relates an external resource to syndicate the contents of a web document to aggregators

The syntax is a void [`link` element](https://html.spec.whatwg.org/#the-link-element) with the following attributes:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) with the `alternate` keyword

- One [`href` attribute](/en/html-content-attributes/#attribute-href) 

- One [`type` attribute](/en/html-content-attributes/#attribute-type) with a MIME Type value but not the following keywords: `application/rss+xml` and `application/atom+xml`.

- Zero or one count for each of the following attributes: 

  - [`hreflang`](/en/html-content-attributes/#attribute-hreflang)

  - [`media`](/en/html-content-attributes/#attribute-media)

- Zero or one count for the [`title` attribute](/en/html-content-attributes/#attribute-title) and each other [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<link rel="alternate" type="application/rss+xml" href="[resource-url]">
<!-- or -->
<link rel="alternate" type="application/atom+xml" href="[resource-url]">
```
</section>


<section>
<h2 id="meta-theme">Theme Meta</h2>

A Theme Meta relates the color to customize the interface of the user agent.

The syntax is a void [`meta` element](https://html.spec.whatwg.org/#the-meta-element) with the following attributes:

- One [`name` attribute](/en/html-content-attributes/#attribute-name) with the `theme-color` value

- One [`content` attribute](/en/html-content-attributes/#attribute-content)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<meta name="theme-color" content="[value]">
```
</section>


<section>
<h2 id="meta-scheme">Scheme Meta</h2>

The Scheme Meta relates the color scheme to use as default for a web document.

The syntax is one void [`meta` element](https://html.spec.whatwg.org/#the-meta-element) per document with the following attributes:

- One [`name` attribute](/en/html-content-attributes/#attribute-name) with the `color-scheme` value

- One [`content` attribute](/en/html-content-attributes/#attribute-content)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<meta name="color-scheme" content="[value]">
```

</section>



<section>
<h2 id="meta-template">Template Meta</h2>

A Template Meta specifies a fragment of an HTML document with optional [placeholders](#wrapper-slot)

The syntax is a [`template` element](https://html.spec.whatwg.org/#the-template-element) with the following attributes and contents:

- Zero or one count for each of the following attributes: 

  - [`shadowrootmode`](/en/html-content-attributes/#attribute-shadowrootmode) 

  - [`shadowrootdelegatesfocus`](/en/html-content-attributes/#attribute-shadowrootdelegatesfocus) 

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- Zero or more counts for each [Flow Content Element.](https://html.spec.whatwg.org/#flow-content)

```html
<template>

</template>
```

</section>



<section>
<h2 id="meta-font">Font Meta</h2>

A Font Meta relates a font resource to be loaded in advance for use within a content window.

The syntax is a void [`link` element](https://html.spec.whatwg.org/#the-link-element) with the following keywords:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) with a `preload` keyword. 

- One [`as` attribute](/en/html-content-attributes/#attribute-as) with a `font` value

- One count for each of the following attributes: 

  - [`href`](/en/html-content-attributes/#attribute-href) 

  - [`crossorigin`](/en/html-content-attributes/#attribute-crossorigin) 

- Zero or one count for each of the following attributes: 

  - [`fetchpriority`](/en/html-content-attributes/#attribute-fetchpriority)

  - [`hreflang`](/en/html-content-attributes/#attribute-hreflang)

  - [`integrity`](/en/html-content-attributes/#attribute-integrity)

  - [`media`](/en/html-content-attributes/#attribute-media)

  - [`referrerpolicy`](/en/html-content-attributes/#attribute-referrerpolicy)

  - [`type`](/en/html-content-attributes/#attribute-type) 

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)



```html
<link rel="preload" as="font" href="[URL]" crosorigin>
```
</section>

<section>
<h2 id="meta-image">Image Meta</h2>

An Image Meta relates an image resource to be loaded in advance for use within a content window

The syntax is a void [`link` element](https://html.spec.whatwg.org/#the-link-element) with the following attributes:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) with a `preload` keyword. 

- One [`as` attribute](/en/html-content-attributes/#attribute-as) with an `image` value

- One or both of the following attributes: 

  - [`href`](/en/html-content-attributes/#attribute-href)

  - [`imagesrcset`](/en/html-content-attributes/#attribute-imagesrcset) 

- Zero or one `imagesizes` attribute if the `imagesrscet` attribute has a value that includes a width descriptor

- Zero or one count for each of the following attributes: 

  - [`crossorigin`](/en/html-content-attributes/#attribute-crossorigin)

  - [`fetchpriority`](/en/html-content-attributes/#attribute-fetchpriority)

  - [`hreflang`](/en/html-content-attributes/#attribute-hreflang)

  - [`integrity`](/en/html-content-attributes/#attribute-integrity)

  - [`media`](/en/html-content-attributes/#attribute-media)

  - [`referrerpolicy`](/en/html-content-attributes/#attribute-referrerpolicy)

  - [`type`](/en/html-content-attributes/#attribute-type) 

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<link rel="preload" as="image" href="[URL]" imagesrcset="[IMS]">
```
</section>


<section>
<h2 id="meta-media">Media Meta</h2>

A Media Meta relates an `audio` or a `video` resource to be loaded in advance for use within a content window

The syntax is a void [`link` element](https://html.spec.whatwg.org/#the-link-element) with the following keywords:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) with a `preload` keyword. 

- One [`as` attribute](/en/html-content-attributes/#attribute-as) with an `audio` value or `video` value

- One [`href` attribute](/en/html-content-attributes/#attribute-href)

- Zero or one count for each of the following attributes: 

  - [`crossorigin`](/en/html-content-attributes/#attribute-crossorigin)

  - [`fetchpriority`](/en/html-content-attributes/#attribute-fetchpriority)

  - [`hreflang`](/en/html-content-attributes/#attribute-hreflang)

  - [`integrity`](/en/html-content-attributes/#attribute-integrity)

  - [`media`](/en/html-content-attributes/#attribute-media)

  - [`referrerpolicy`](/en/html-content-attributes/#attribute-referrerpolicy)

  - [`type`](/en/html-content-attributes/#attribute-type) 

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<link rel="preload" as="[audio|video]" href="[URL]">
```
</section>

<section>
<h2 id="meta-track">Track Meta</h2>

A Track Meta relates a text track resource to be loaded in advance for use within a content window.

The syntax is a void [`link` element](https://html.spec.whatwg.org/#the-link-element) with the following keywords:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) with a `preload` keyword. 

- One [`as` attribute](/en/html-content-attributes/#attribute-as) with `track` value.

- One [`href` attribute](/en/html-content-attributes/#attribute-href)

- Zero or one count for each of the following attributes: 

  - [`crossorigin`](/en/html-content-attributes/#attribute-crossorigin)

  - [`fetchpriority`](/en/html-content-attributes/#attribute-fetchpriority)
  
  - [`hreflang`](/en/html-content-attributes/#attribute-hreflang)

  - [`integrity`](/en/html-content-attributes/#attribute-integrity)

  - [`media`](/en/html-content-attributes/#attribute-media)

  - [`referrerpolicy`](/en/html-content-attributes/#attribute-referrerpolicy) 

  - [`type`](/en/html-content-attributes/#attribute-type) 

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<link rel="preload" as="track" href="[URL]">
```
</section>


<section>
<h2 id="meta-document">Document Meta</h2>

A Document Meta relates a document to be loaded in advance for an [`iframe`](/en/html-content-objects/#element-iframe), [`object`](/en/html-content-objects/#element-object), or [`embed`](/en/html-content-objects/#element-embed) element in a content window.

The syntax is a void [`link` element](https://html.spec.whatwg.org/#the-link-element) with the following keywords:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) with a `preload` keyword. 

- One [`as` attribute](/en/html-content-attributes/#attribute-as) with one of the following values: 

  - `document`

  - `object`

  - `embed`

- One [`href` attribute](/en/html-content-attributes/#attribute-href)

- Zero or one count for each of the following attributes: 

  - [`crossorigin`](/en/html-content-attributes/#attribute-crossorigin) 

  - [`fetchpriority`](/en/html-content-attributes/#attribute-fetchpriority)

  - [`hreflang`](/en/html-content-attributes/#attribute-hreflang) 

  - [`integrity`](/en/html-content-attributes/#attribute-integrity)

  - [`media`](/en/html-content-attributes/#attribute-media)

  - [`referrerpolicy`](/en/html-content-attributes/#attribute-referrerpolicy)

  - [`type`](/en/html-content-attributes/#attribute-type) 

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<link rel="preload" as="[document|object|embed]" href="[URL]">
```
</section>


<section>
<h2 id="meta-stylesheet">Stylesheet Meta</h2>

A Stylesheet Meta specifies a set of CSS Rules on a web document for presentational purposes. 


<section>
<h2 id="meta-stylesheet-usage-scenarios">Usage Scenario</h2>

There are the following 3 ways to which CSS Rules apply to a web document

- [External Stylesheet](#meta-stylesheet-external)

- [Embedded Stylesheet](#meta-stylesheet-embedded)

- [Inline Stylesheet](#meta-stylesheet-inline)

All 3 create a Persistent Stylesheet on Content Windows. 

Meanwhile, setting a `title` attribute on an external or embedded stylesheet creates a design variation for user's choice. Each variation becomes a set of Alternate Stylesheets

The initial variation to style the Content Windows is provided by a [Default Stylesheet](#meta-stylesheet-default)

</section>


<section>
<h3 id="meta-stylesheet-external">External Stylesheet</h3>

An External Stylesheet relate CSS Rules applicable to one or more web pages.

The syntax is a void [`link` element](https://html.spec.whatwg.org/#the-link-element) with the following attributes:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) with the `stylesheet` keyword.

  It may include a `preload` keyword to load the stylesheet in advance.

- One [`href` attribute](/en/html-content-attributes/#attribute-href)

- One [`as` attribute](/en/html-content-attributes/#attribute-as) with a `style` value if there's a `preload` keyword in the `rel` attribute

- Zero or one count for each of the following attributes: 

  - [`blocking`](/en/html-content-attributes/#attribute-blocking)

  - [`crossorigin`](/en/html-content-attributes/#attribute-crossorigin)

  - [`disabled`](/en/html-content-attributes/#attribute-disabled)

  - [`fetchpriority`](/en/html-content-attributes/#attribute-fetchpriority)

  - [`hreflang`](/en/html-content-attributes/#attribute-hreflang)

  - [`integrity`](/en/html-content-attributes/#attribute-integrity)
  
  - [`media`](/en/html-content-attributes/#attribute-media)

  - [`referrerpolicy`](/en/html-content-attributes/#attribute-referrerpolicy)

  - [`type`](/en/html-content-attributes/#attribute-type) 

- Zero or one count for the [`title` attribute](/en/html-content-attributes/#attribute-title) and each other [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

</section>


<section>
<h3 id="meta-stylesheet-embedded">Embedded Stylesheet</h3>
  
An Embedded Stylesheet relate CSS Rules applicable to only one web page

The syntax is a `style` element with the following attributes and content:

- Zero or one count for each of the following attributes: 
  
  - [`blocking`](#style-blocking-attribute)
  - [`media`](#style-media-attribute) 

- Zero or one count for the [`title` attribute](/en/html-content-attributes/#attribute-title) and each other [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- A text content that gives a [conformant style sheet](https://drafts.csswg.org/css-syntax/#conform-classes)

```html
<style>
  /* text that is style conformant */
</style>
```

</section>


<section>
<h3 id="meta-stylesheet-inline">Inline Stylesheet</h3>

An Inline Stylesheet relate CSS declarations applicable to only one HTML element.

The syntax is a [`style` attribute](/en/html-content-attributes/#attribute-style) with a value conforming to a [conformant style sheet](https://drafts.csswg.org/css-syntax/#conform-classes)


</section>

<aside>
<h3>Appendix</h3>

<section>
  <h4 id="meta-stylesheet-default">Default Stylesheet</h4>

  The default stylesheet identifies a design variation to use pending a user's preference.

  This declaration must precede all [stylesheet declarations](#meta-stylesheet-usage-scenarios)

  A design variation is a set of external and embedded stylesheets with the same [`title` attribute](/en/html-content-attributes/#attribute-title) value

  The syntax is one void [`meta` element](https://html.spec.whatwg.org/#the-meta-element) per document with the following attributes:

    - One [`http-equiv` attribute](/en/html-content-attributes/#attribute-name) with the `default-style` value

    - One [`content` attribute](/en/html-content-attributes/#attribute-content) with the value of the `title` attribute for the chosen design variation

  ```html
  <meta http-equiv="default-style" content="[text]">
  ```

</section>

</aside>

</section>


<section>
<h2 id="meta-script">Script Meta</h2>

A Script Meta specifies javascript instructions on a web document for dynamic contents. 

<section>
<h3>External Javascript</h3>

An External Javascript relate instructions applicable to one or more web web pages

It can be a Classic Script or a Preloaded Script. An External Classic Script loads and runs a javascript resource. A Preloaded External Script loads but not run the javascript resource. The latter helps with performance optimizations

<div id="meta-script-external-classic">

The syntax for an External Classic Script is a [`script` element](https://html.spec.whatwg.org/#the-script-element) with the following attributes and content:

- One [`src` attribute](/en/html-content-attributes/#attribute-src)

- Zero or one count for each of the following attributes: 

  - [`async`](/en/html-content-attributes/#element-async) 

  - [`blocking`](/en/html-content-attributes/#attribute-blocking) 

  - [`crossorigin`](/en/html-content-attributes/#attribute-crossorigin) 

  - [`defer`](/en/html-content-attributes/#element-defer) 

  - [`fetchpriority`](/en/html-content-attributes/#attribute-fetchpriority) 
  
  - [`integrity`](/en/html-content-attributes/#element-defer)

  - [`nomodule`](/en/html-content-attributes/#attribute-nomodule)  

  - [`referrerpolicy`](/en/html-content-attributes/#attribute-referrerpolicy) 

  - [`type`](/en/html-content-attributes/#attribute-type)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- An optional text content matching [script content restrictions](https://html.spec.whatwg.org/#restrictions-for-contents-of-script-elements) and conforming to a [script documentation](https://html.spec.whatwg.org/#inline-documentation-for-external-scripts)


```html
<script src="[valid-URL]"></script>
```
</div>


<div id="meta-script-external-preloaded">

The syntax for an External Preloaded Script is a void [`link` element](https://html.spec.whatwg.org/#the-link-element) with the following attributes:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) with a `preload` keyword. 

- One [`as` attribute](/en/html-content-attributes/#attribute-as) with one of the following values: 

  - `audioworklet`

  - `paintworklet`

  - `serviceworker`

  - `sharedworker`

  - `worker`

  - `script`

  - `json`

- One [`href` attribute](/en/html-content-attributes/#attribute-href)

- Zero or one count for each of the following attributes: 

  - [`crossorigin`](/en/html-content-attributes/#attribute-crossorigin)

  - [`fetchpriority`](/en/html-content-attributes/#attribute-fetchpriority)

  - [`hreflang`](/en/html-content-attributes/#attribute-hreflang)

  - [`integrity`](/en/html-content-attributes/#attribute-integrity)

  - [`media`](/en/html-content-attributes/#attribute-media) 

  - [`referrerpolicy`](/en/html-content-attributes/#attribute-referrerpolicy)

  - [`type`](/en/html-content-attributes/#attribute-type) 


```html
<link rel="preload" as="[audioworklet|paintworklet|serviceworker|sharedworker|worker|script|json]" href="[URL]">
```
</div>

</section>


<section>
<h3 id="meta-script-embedded">Embedded Javascript</h3>

An Embedded Javascript relate instructions applicable to only one web page

The syntax is a [`script` element](https://html.spec.whatwg.org/#the-script-element) with the following attributes and content:

- Zero or one count for each of the following attributes: 

  - [`blocking`](/en/html-content-attributes/#attribute-blocking) 

  - [`crossorigin`](/en/html-content-attributes/#attribute-crossorigin) 

  - [`fetchpriority`](/en/html-content-attributes/#attribute-fetchpriority) 

  - [`nomodule`](/en/html-content-attributes/#attribute-nomodule)  

  - [`referrerpolicy`](/en/html-content-attributes/#attribute-referrerpolicy)

  - [`type`](/en/html-content-attributes/#attribute-type) 


- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

- A text content matching [script content restrictions](https://html.spec.whatwg.org/#restrictions-for-contents-of-script-elements) and conforming to the value of the `type` attribute

```html
<script>

</script>
```

</section>


<section>
<h3>Inline Javascript</h3>

An Inline Javascript relate instructions to only one HTML element

The syntax is an event handler content attribute with applicable values.

</section>


<aside>
<h3>Script Meta Utilities</h3>

An External, Embedded, or Inline Javascript may further be managed with [Modules](script-meta-js-modules), [Module Maps](#script-meta-js-module-maps), and [Data Blocks](#script-meta-js-data-blocks)


<section>
<h4 id="meta-script-module">Javascript Module</h4>

A Javascript Module enables reuse of an external or embedded javascript

The syntax on an [External Classic Script](#meta-script-external-classic) or on an [Embedded Javascript](#meta-script-embedded) expects the [`script` element](https://html.spec.whatwg.org/#the-script-element) with the following conditions:

- One [`type` attribute](/en/html-content-attributes/#attribute-type) with a `module` value

- Zero count for each of the following attributes:

  - [`defer`](/en/html-content-attributes/#element-defer) 

  - [`nomodule`](/en/html-content-attributes/#element-nomodule) 


```html
<script type="module">

</script>
```

<div>

Meanwhile, the syntax on an [External Preloaded Script](#meta-script-external-preloaded) expects the [`link` element](https://html.spec.whatwg.org/#the-link-element) with a `rel` attribute having the `modulepreload` value

```html
<link rel="modulepreload">
```

</div>
</section>

<section>
<h4>Import Maps</h4>

An Import Map specifies a JSON resource to resolve [Javascript Modules](#meta-script-modules)

The syntax is one [`script` element](https://html.spec.whatwg.org/#the-script-element) per document with the following attributes and content:

- One [`type` attribute](/en/html-content-attributes/#attribute-type) with an `importmap` value

- A text content that conforms to the [import map authoring requirements](https://html.spec.whatwg.org/#import-map-authoring-requirements)

```html
<script type="importmap"></script>
```

</section>

<section>
<h4>Data Block</h4>

A Data Block specifies data for use in Javascript Instructions. A Data Block can be preloaded or, straight up, executed.

The syntax to preload a Data Block is a void [`link` element](https://html.spec.whatwg.org/#the-link-element) with the following attributes:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) with a `preload` keyword. 

- One [`as` attribute](/en/html-content-attributes/#attribute-as) with `json` value.

- One [`href` attribute](/en/html-content-attributes/#attribute-href)

- Zero or one count for each of the following attributes: 
[`crossorigin`](/en/html-content-attributes/#attribute-crossorigin), 
[`fetchpriority`](/en/html-content-attributes/#attribute-fetchpriority), 
[`hreflang`](/en/html-content-attributes/#attribute-hreflang), 
[`integrity`](/en/html-content-attributes/#attribute-integrity), 
[`media`](/en/html-content-attributes/#attribute-media), 
[`referrerpolicy`](/en/html-content-attributes/#attribute-referrerpolicy), and 
[`type`](/en/html-content-attributes/#attribute-type) 

```html
<link rel="preload" as="json" href="[URL]">
```

The syntax to execute a Data Block is a [`script` element](https://html.spec.whatwg.org/#the-script-element) with the following attributes and content:

- One [`type` attribute](/en/html-content-attributes/#attribute-type) with a [MIME Type](https://www.iana.org/assignments/media-types/media-types.xhtml) value other than the `text/javascript` value

- A text content that satisfy the following 2 conditions:

  - matches [script content restrictions](https://html.spec.whatwg.org/#restrictions-for-contents-of-script-elements)

  - conforms to the value of the `type` attribute  

```html
<script type="[mime-type-but-not-text/javascript]"></script>
```

</section>

</aside>



</section>




<section>
<h2 id="meta-custom-link">Custom Link Meta</h2>

A Custom Link Meta specifies a non-standard metadata keyword whose value must be a URL to a resource

The syntax is a void [`link` element](https://html.spec.whatwg.org/#the-link-element) with the following attributes:

- One [`rel` attribute](/en/html-content-attributes/#attribute-rel) but it must have an [extension link type keyword](https://microformats.org/wiki/existing-rel-values#HTML5_link_type_extensions)

- One [`href` attribute](/en/html-content-attributes/#attribute-href)

- Zero or one for the following attributes if the extension link type is an [external resource link](https://html.spec.whatwg.org/#external-resource-link):
[`crossorigin`](/en/html-content-attributes/#attribute-crossorigin)
[`fetchpriority`](/en/html-content-attributes/#attribute-fetchpriority), and 
[`referrerpolicy`](/en/html-content-attributes/#attribute-referrerpolicy)

- Zero or one count for each of the following attributes:  
[`hreflang`](/en/html-content-attributes/#attribute-hreflang), 
[`media`](/en/html-content-attributes/#attribute-media), and 
[`type`](/en/html-content-attributes/#attribute-type) 

- Zero or one [`color` attribute](/en/html-content-attributes/#attribute-color) if `rel` attribute has a `mask-icon`

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<link rel="[extension-link-type-keyword]" href="[URL]">
```
</section>


<section>
<h2 id="meta-custom-text">Custom Text Meta</h2>

A Custom Text Meta specifies a non-standard metadata keyword whose value must not be a URL to a resource

The syntax is a void [`meta` element](https://html.spec.whatwg.org/#the-meta-element) with the following attributes:

- One [`name` attribute](/html-content-attributes/#attribute-name) whose value must be a [Meta Name Extension](https://wiki.whatwg.org/wiki/MetaExtensions)

- One [`content` attribute](/html-content-attributes/#attribute-content)

- Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

```html
<meta name="[meta-name-extension]" value="[value]">
```
</section>




<aside>
<h2>Appendix</h2>

The following utilities applies to Content Metas

<section>
  <h3 id="container-head">Head Container</h3>

  The Head Container specifies a collection of [Content Metas](/en/html-content-metas/) to User Agents for processing

  The syntax is an [`head` element](https://html.spec.whatwg.org/#the-head-element) with the following attributes and contents:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for most [Content Metas](#outline) 

  ```html
  <head>
    <!-- Content Metas -->
  </head>
  ```
</section>

<section>
  <h3 id="container-noscript">Noscript Container</h3>

  A Noscript Container in a [Meta Container](#container-meta) relates Content Metas to User Agents that doesn't support scripting functionality on a web document.

  The syntax is a [`noscript` element](https://html.spec.whatwg.org/#the-noscript-element) with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Content Metas except the following:
    <span class="i-grid-wrapper">
      <span><a href="#meta-title">Title Meta</a>, </span>
      <span><a href="#meta-url">Url Meta</a>, </span>
      <span><a href="#meta-target">Target Meta</a>, </span>
      <span><a href="#meta-template">Template Meta</a>, and </span>
      <span>loaded (not preloaded) <a href="#meta-script">Script Meta</a></span>
    </span>

  ```html
  <noscript>

  </noscript>
  ```
</section>

<section>
<h3 id="wrapper-slot">Slot Wrapper</h3>

A Template Placeholder specifies a replaceable part within a [reusable markup](#meta-template)

The syntax is a [`slot` element](https://html.spec.whatwg.org/#the-slot-element) with the following attributes and contents:

- Zero or one [`slot` attribute](/en/html-content-attributes/#attribute-slot)

- Zero or one count for each [Global Attribute](/en/html-content-attributes/#attribute-global-list)

- Zero or one count for each element allowed in the parent element

```html
<slot></slot>
```
</section>

</aside>
