---
title: The 29 Content Connotations of HTML
canonical: https://www.toheeb.com/en/html-content-connotations/
book-hc: 11
---



<header>

  # The 29 Content Connotations of HTML

  A Content Connotation conveys the expression behind a phrase in a [Content Block](/en/html-content-blocks/)

  <nav class="list-to-grid">
  <h2 id="outline">Outline</h2>

  The 29 Content Connotations are as follows:

  - [Quote Connotation](#connotation-quote)

  - [Dormant Connotation](#connotation-dormant)

  - [Deletion Connotation](#connotation-deletion)

  - [Insertion Connotation](#connotation-insertion)

  - [Abbreviation Connotation](#connotation-abbreviation)

  - [Vague Connotation](#connotation-vague)

  - [Idiom Connotation](#connotation-idiom)

  - [Cite Connotation](#connotation-cite)

  - [Hyperlink Connotation](#connotation-hyperlink)

  - [Label Connotation](#connotation-label)

  - [Definiendum Connotation](#connotation-definiendum)

  - [Strong Connotation](#connotation-strong)

  - [Keyword Connotation](#connotation-keyword)

  - [Emphasis Connotation](#connotation-emphasis)

  - [Mark Connotation](#connotation-mark)

  - [Small Connotation](#connotation-small)

  - [Ruby Connotation](#connotation-ruby)

  - [Superscript Connotation](#connotation-superscript)

  - [Subscript Connotation](#connotation-subscript)

  - [Bidirection Connotation](#connotation-bidirection)

  - [Progress Connotation](#connotation-progress)

  - [Input Connotation](#connotation-input)

  - [Time Connotation](#connotation-time)

  - [Data Connotation](#connotation-data)

  - [Meter Connotation](#connotation-meter)

  - [Variable Connotation](#connotation-variable)

  - [Code Connotation](#connotation-code)

  - [Output Connotation](#connotation-output)

  - [General Connotation](#connotation-general)

  </nav>
</header>



<section>
  <h2 id="connotation-quote">Quote Connotation</h2>

  A Quote Connotation conveys a phrase from another source

  The syntax is a `q` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <q></q>
  ```
</section>



<section>
  <h2 id="connotation-dormant">Dormant Connotation</h2>

  A Dormant Connotation conveys a phrase that is currently not relevant or accurate

  The syntax is an `s` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <s></s>
  ```
</section>



<section>
  <h2 id="connotation-deletion">Deletion Connotation</h2>

  A Deletion Connotation conveys a phrase that has been, technically, removed

  The syntax is a `del` element with the following attributes and child elements:

  - Zero or one count for each of the following attributes: [`cite`,](/en/html-content-attributes#attribute-cite) and [`datetime`.](/en/html-content-attributes#attribute-datetime)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <del></del>
  ```
</section>



<section>
  <h2 id="connotation-insertion">Insertion Connotation</h2>

  An Insertion Connotation conveys a phrase that has been technically added

  The syntax is an `ins` element with the following attributes and child elements:

  - Zero or one count for each of the following attributes: [`cite`,](/en/html-content-attributes#attribute-cite) and [`datetime`.](/en/html-content-attributes#attribute-datetime)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <ins></ins>
  ```
</section>



<section>
  <h2 id="connotation-abbreviation">Abbreviation Connotation</h2>

  An Abbreviation Connotation conveys a phrase that is a short form of one or more words

  The syntax is an `abbr` element with the following attributes and child elements:

  - Zero or one count for each [`title` attribute](/en/html-content-attributes/#attribute-title) and other [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <abbr></abbr>
  ```
</section>




<section>
  <h2 id="connotation-vague">Vague Connotation</h2>

  A Vague Connotation conveys a phrase that is unarticulated

  The syntax is an `u` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <u></u>
  ```
</section>




<section>
  <h2 id="connotation-idiom">Idiom Connotation</h2>

  An Idiom Connotation conveys a phrase that has a meaning different from its basic meaning

  The syntax is an `i` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <i></i>
  ```
</section>




<section>
  <h2 id="connotation-cite">Cite Connotation</h2>

  A Cite Connotation conveys a phrase as the title of a work

  The syntax is a `cite` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <cite></cite>
  ```
</section>



<section>
  <h2 id="connotation-hyperlink">Hyperlink Connotation</h2>

  A Hyperlink Connotation conveys a phrase as the label for a resource address

  The syntax is a `a` element with the following attributes and child elements:

  - Zero or one [`href` attribute](/en/html-content-attributes#attribute-href)

  - Zero or one count for each of the following attributes if the `href` attribute is present:
  [`target`](/en/html-content-attributes#attribute-target), 
  [`download`](/en/html-content-attributes#attribute-download), 
  [`ping`](/en/html-content-attributes#attribute-ping), 
  [`rel`](/en/html-content-attributes#attribute-rel), 
  [`hreflang`](/en/html-content-attributes#attribute-hreflang), 
  [`type`](/en/html-content-attributes#attribute-type), and 
  [`referrerpolicy`](/en/html-content-attributes#attribute-referrerpolicy)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each [Phrasing Content Element,](https://html.spec.whatwg.org/#phrasing-content) but the following exceptions:

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/) But exclude the following descendant [interactive contents](https://html.spec.whatwg.org/#interactive-content):

    - Any Content with a [`tabindex` attribute](/en/html-content-attributes/#attribute-tabindex)

    - An [Hyperlink Connotation](/en/html-content-connotation/#connotation-hyperlink) with an [`href` attribute](/en/html-content-attributes#attribute-href)

    - A [Raster Image](/en/html-content-objects/#image-raster) with a [`usemap` attribute](/en/html-content-attributes#attribute-usemap)

    - An [Audio Media](/en/html-content-objects/#media-audio) with a [`controls` attribute](/en/html-content-attributes#attribute-controls)

    - A [Video Media](/en/html-content-objects/#media-video) with a [`controls` attribute](/en/html-content-attributes#attribute-controls)

    - An [Embed Medium](/en/html-content-objects/#medium-embed)

    - A [Web Document](/en/html-content-objects/#document-web)

    - Each [Content Form](/en/html-content-forms/)

    - A [Label Connotation](/en/html-content-connotations/#connotation-label)


  ```html
  <a></a>
  ```

  Note: An Hyperlink Connotation has an equivalent [Hyperlink Card](/en/html-content-cards/#card-hyperlink) for out-of-inline contents
</section>



<section>
  <h2 id="connotation-label">Label Connotation</h2>

  A Label Connotation conveys a phrase as the name for any of the following: 
  
  - [Content Form](/en/html-content-forms/)
  
  - [Progress Connotation](#connotation-progress)
  
  - [Meter Connotation](#connotation-meter)
  
  - [Output Connotation.](#connotation-output)

  The syntax is a `label` element with the following attributes and child elements:

  - One [`for` attribute](/en/html-content-attributes/#attribute-for)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each [phrasing content element](https://html.spec.whatwg.org/#phrasing-content) but the following exceptions:

    - Zero descendants for each [labelable element](https://html.spec.whatwg.org/#category-label) unless it is the control being labelled
    
    - Zero descendant `label` element

  ```html
  <label for="[id]"></label>
  ```
</section>



<section>
  <h2 id="connotation-definiendum">Definiendum Connotation</h2>

  A Definiendum Connotation conveys a defining term as the subject of a definition. 

  The defining term is the first valid item in the following list:

  - The value of a [`title` attribute](/en/html-content-attributes/#attribute-title)

  - The value of the `title` attribute of an only child [`abbr` element](#element-abbr)

  - The inline content

  The syntax is a `dfn` element with the following attributes and child elements:

  - Zero or one count for each [`title` attribute](/en/html-content-attributes/#attribute-title) and other [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/) But, must exclude descendant Definiendum Connotation

  ```html
  <dfn></dfn>
  ```
</section>



<section>
  <h2 id="connotation-strong">Strong Connotation</h2>

  A Strong Connotation conveys a phrase that is the subject of a discussion

  The syntax is a `strong` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <strong></strong>
  ```
</section>




<section>
  <h2 id="connotation-keyword">Keyword Connotation</h2>

  A Keyword Connotation conveys a phrase that is notable in a discussion

  The syntax is a `b` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <b></b>
  ```
</section>




<section>
  <h2 id="connotation-emphasis">Emphasis Connotation</h2>

  An Emphasis Connotation conveys a phrase that is a reassertion

  The syntax is an `em` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <em></em>
  ```
</section>



<section>
  <h2 id="connotation-mark">Mark Connotation</h2>

  A Mark Connotation conveys a phrase that is relevant in another context

  The syntax is a `mark` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <mark></mark>
  ```
</section>




<section>
  <h2 id="connotation-small">Small Connotation</h2>

  A Small Connotation conveys a phrase that is a side comment

  The syntax is a `small` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <small></small>
  ```
</section>



<section>
  <h2 id="connotation-ruby">Ruby Connotation</h2>

  A Ruby Connotation conveys a ruby annotation through the following components:

  <dl>

  <div>
  <dt>
    <p>Ruby Annotation Wrapper</p>
  </dt>
  <dd>

  The Ruby Annotaion Wrapper relates the inline contents to annotate, [Ruby Annotation Texts](#connotation-ruby-text), and [Ruby Annotation Parenthesis](#connotation-ruby-parenthesis).

  The syntax is a `ruby` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Either of the following:

    - One `ruby` element excluding descendant `ruby` elements

    - Zero or more counts for each [Phrasing Content Element.](https://html.spec.whatwg.org/#phrasing-content) But, excluding sibling and descendant `ruby` elements

  - Either of the following:

    - One or more [`rt` element](#element-rt)

    - One [`rp` element](#element-rp) before and after each `rt` element

  ```html
  <ruby></ruby>
  ```
  </dd>
  </div>

  <div>
  <dt id="connotation-ruby-text">
    <p>Ruby Annotation Text</p>
  </dt>
  <dd>

  A Ruby Annotation Text relates the annotation
    
  The syntax is an `rt` element with the following attributes and elements:

  - One parent [`ruby` element](#element-ruby)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <rt></rt>
  ```
  </dd>
  </div>

  <div>
  <dt id="connotation-ruby-parenthesis">
    <p>Ruby Annotation Parenthesis</p>
  </dt>
  <dd>

  A Ruby Annotation Parenthesis relates a text to signify lack of user agent support for Ruby Annotations 

  The syntax is an `rp` element with the following attributes and content:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - A text content

  ```html
  <rp></rp>
  ```
  </dd>
  </div>
  </dl>
</section>




<section>
  <h2 id="connotation-superscript">Superscript Connotation</h2>

  A Superscript Connotation conveys a phrase as an overline for preceding contents

  The syntax is a `sup` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <sup></sup>
  ```
</section>



<section>
  <h2 id="connotation-subscript">Subscript Connotation</h2>

  A Subscript Connotation conveys a phrase as an underline for preceding contents

  The syntax is a `sub` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <sub></sub>
  ```
</section>




<section>
  <h2 id="connotation-bidirection">Bidirection Connotation</h2>

  A Bidirection Connotation conveys a phrase with bidirectional formating

  It can be a Bidirectional Isolation (BDI) or a Bidirectional Override (BDO)


  <section>
  <h3 id="connotation-bdi">BDI Connotation</h3>

  A BDI Connotation isolates inline content from its surroundings with an automatic bidirectional formatting

  The syntax is a `bdi` element with the following attributes and child elements:

  - Zero or one count for each [`dir` attribute](/en/html-content-attributes/#attribute-dir) and other [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <bdi></bdi>
  ```
  </section>



  <section>
  <h3>BDO Connotation</h3>

  A Bi-Directional Override Connotation conveys a phrase with an explicit bidirectional formatting.

  The syntax is a non-void element with the following attributes and child elements:

  - One [`dir` attribute](/en/html-content-attributes/#attribute-dir) and the value must not be an `auto`

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes) except `dir` attribute

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <bdo></bdo>
  ```
  </section>
  
</section>




<section>
  <h2 id="connotation-progress">Progress Connotation</h2>

  A Progress Connotation conveys a phrase as an undergoing computer event

  The syntax is a `progress` element with the following attributes and child elements:

  - Zero or one count for each of the following attributes: [`value`](/en/html-content-attributes#attribute-value), and [`max`](/en/html-content-attributes#attribute-max)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)


  ```html
  <progress></progress>
  ```
</section>



<section>
  <h2 id="connotation-input">Input Connotation</h2>

  An Input Connotation conveys a phrase as a computer input

  The syntax is a `kbd` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <kbd></kbd>
  ```
</section>




<section>
  <h2 id="connotation-time">Time Connotation</h2>

  A Time Connotation conveys a phrase that has a time-readable format

  The syntax is a `time` element with the following attributes and child elements:

  - Zero or one [`datetime` attribute](/en/html-content-attributes#attribute-datetime)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - A text content in a [time syntax](https://html.spec.whatwg.org/#datetime-value) if there's no `datetime` attribute

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/). But, only if there's a `datetime` attribute

  ```html
  <time></time>
  ```
</section>



<section>
  <h2 id="connotation-data">Data Connotation</h2>

  The Data Connotation conveys a phrase that has a machine-readable format

  The syntax is a `data` element with the following attributes and child elements:

  - One [`value` attribute](/en/html-content-attributes#attribute-value)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <data></data>
  ```
</section>




<section>
  <h2 id="connotation-meter">Meter Connotation</h2>

  A Meter Connotation conveys a phrase that is a scalar measurement within a known range

  The syntax is a `meter` element with the following attributes and child elements:

  - Zero or one count for each of the following attributes: 
  [`high`](/en/html-content-attributes#attribute-high), 
  [`low`](/en/html-content-attributes#attribute-low), 
  [`optimum`](/en/html-content-attributes#attribute-optimum), 
  [`max`](/en/html-content-attributes#attribute-max), 
  [`min`](/en/html-content-attributes#attribute-min), 
  [`value`](/en/html-content-attributes#attribute-value), and 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <meter></meter>
  ```
</section>




<section>
  <h2 id="connotation-variable">Variable Connotation</h2>

  A Variable Connotation conveys a phrase with a varying value

  The syntax is a `var` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <var></var>
  ```
</section>



<section>
  <h2 id="connotation-code">Code Connotation</h2>

  A Code Connotation conveys a phrase that is a computer instruction

  The syntax is a `code` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <code></code>
  ```
</section>



<section>
  <h2 id="connotation-output">Output Connotation</h2>

  An Output Connotation conveys a phrase that is the result of a computer instruction

  The following are 2 variants of an Output Connotation depending on the time of output:


  <h3 id="connotation-immediate-output">Immediate Output Connotation</h3>

  An Immediate Output Connotation relates a just-concluded result

  The syntax is an `output` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or one count for each of the following attributes: [`for`](/en/html-content-attributes#attribute-for), [`form`](/en/html-content-attributes#attribute-form), and [`name`](/en/html-content-attributes#attribute-name)
  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <output></output>
  ```
</section>



<section>
  <h3 id="connotation-previous-samp">Previous Output Connotation</h3>

  A Previous Output Connotation relates a previously concluded result

  The syntax is a `samp` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <samp></samp>
  ```
</section>



<section>
<h2 id="connotation-general">General Connotation</h2>

  A General Connotation conveys a phrase with a custom connotation

  The syntax is a `span` element with the following attributes and child elements:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation.](/en/html-content-connotations/)

  ```html
  <span></span>
  ```
</section>
