---
title: The 132 Content Attributes of HTML
canonical: https://www.toheeb.com/en/html-content-attributes/
book-hc: 12
---

<header>

  # The 132 Content Attributes of HTML

  In HTML, an attribute modifies its element. The element's start tag specifies the set of space-separated attributes that modify the element's content. Each attribute always has a name part and most times a value part.

  <nav class="list-to-grid">
  <h2>Outline</h2>

  The 132 Content Attributes are as follows:

  - [`class`](#attribute-class)

  - [`id`](#attribute-id)

  - [`lang`](#attribute-lang)

  - [`charset`](#attribute-charset)

  - [`dir`](#attribute-dir)

  - [`translate`](#attribute-translate)

  - [`title`](#attribute-title)

  - [`rel`](#attribute-rel)

  - [`type`](#attribute-type)

  - [`hreflang`](#attribute-hreflang)

  - [`as`](#attribute-as)

  - [`blocking`](#attribute-blocking)

  - [`nonce`](#attribute-nonce)

  - [`fetchpriority`](#attribute-fetchpriority)
  
  - [`crossorigin`](#attribute-crossorigin)

  - [`referrerpolicy`](#attribute-referrerpolicy)

  - [`integrity`](#attribute-integrity)

  - [`async`](#attribute-async)

  - [`defer`](#attribute-defer)

  - [`nomodule`](#attribute-nomodule)
  
  - [`media`](#attribute-media)

  - [`color`](#attribute-color)

  - [`http-equiv`](#attribute-http-equiv)

  - [`content`](#attribute-content)

  - [`shadowrootmode`](#attribute-shadowrootmode)

  - [`shadowrootdelegatefocus`](#attribute-shadowrootdelegatefocus)
  
  - [`is`](#attribute-is)

  - [`slot`](#attribute-slot)

  - [`data-*`](#attribute-data-*)

  - [`usemap`](#attribute-usemap)

  - [`ismap`](#attribute-ismap)

  - [`srcset`](#attribute-srcset)

  - [`imagesrcset`](#attribute-imagesrcset)

  - [`src`](#attribute-src)

  - [`data`](#attribute-data)

  - [`loading`](#attribute-loading)

  - [`decoding`](#attribute-decoding)
  
  - [`shape`](#attribute-shape)

  - [`width`](#attribute-width)

  - [`imagesizes`](#attribute-imagesizes)

  - [`sizes`](#attribute-sizes)

  - [`height`](#attribute-height)

  - [`coords`](#attribute-coords)

  - [`alt`](#attribute-alt)

  - [`poster`](#attribute-poster)

  - [`preload`](#attribute-preload)

  - [`autoplay`](#attribute-autoplay)

  - [`loop`](#attribute-loop)

  - [`muted`](#attribute-muted)

  - [`playsinline`](#attribute-playsinline)

  - [`srclang`](#attribute-srclang)
  
  - [`default`](#attribute-default)

  - [`controls`](#attribute-controls)

  - [`kind`](#attribute-kind)

  - [`label`](#attribute-label)

  - [`srcdoc`](#attribute-srcdoc)

  - [`sandbox`](#attribute-sandbox)

  - [`allowfullscreen`](#attribute-allowfullscreen)

  - [`allow`](#attribute-allow)

  - [`draggable`](#attribute-draggable)

  - [`contenteditable`](#attribute-contenteditable)

  - [`for`](#attribute-for)

  - [`name`](#attribute-name)

  - [`dirname`](#attribute-dirname)

  - [`form`](#attribute-form)

  - [`accept-charset`](#attribute-accept-charset)

  - [`action`](#attribute-action)

  - [`formaction`](#attribute-formaction)

  - [`enctype`](#attribute-enctype)

  - [`formenctype`](#attribute-formenctype)

  - [`method`](#attribute-method)

  - [`formmethod`](#attribute-formmethod)

  - [`novalidate`](#attribute-novalidate)

  - [`formnovalidate`](#attribute-formnovalidate)

  - [`target`](#attribute-target)

  - [`formtarget`](#attribute-formtarget)

  - [`autofocus`](#attribute-autofocus)

  - [`tabindex`](#attribute-tabindex)

  - [`accesskey`](#attribute-accesskey)

  - [`enterhintkey`](#attribute-enterhintkey)

  - [`inputmode`](#attribute-inputmode)

  - [`spellcheck`](#attribute-spellcheck)

  - [`autocomplete`](#attribute-autocomplete)

  - [`list`](#attribute-list)

  - [`autocapitalize`](#attribute-autocapitalize)

  - [`wrap`](#attribute-wrap)

  - [`disabled`](#attribute-disabled)
  
  - [`readonly`](#attribute-readonly)

  - [`required`](#attribute-required)

  - [`multiple`](#attribute-multiple)

  - [`checked`](#attribute-checked)

  - [`selected`](#attribute-selected)

  - [`maxlength`](#attribute-maxlength)

  - [`minlength`](#attribute-minlength)

  - [`size`](#attribute-size)

  - [`pattern`](#attribute-pattern)

  - [`placeholder`](#attribute-placeholder)

  - [`value`](#attribute-value)

  - [`min`](#attribute-min)

  - [`step`](#attribute-step)

  - [`max`](#attribute-max)

  - [`low`](#attribute-low)

  - [`high`](#attribute-high)

  - [`optimum`](#attribute-optimum)

  - [`accept`](#attribute-accept)

  - [`start`](#attribute-start)

  - [`reversed`](#attribute-reversed)

  - [`abbr`](#attribute-abbr)

  - [`scope`](#attribute-scope)

  - [`headers`](#attribute-headers)

  - [`cols`](#attribute-cols)

  - [`span`](#attribute-span)

  - [`colspan`](#attribute-colspan)

  - [`rows`](#attribute-rows)

  - [`open`](#attribute-open)

  - [`href`](#attribute-href)

  - [`download`](#attribute-download)

  - [`ping`](#attribute-ping)

  - [`cite`](#attribute-cite)
  
  - [`datetime`](#attribute-datetime)

  - [`inert`](#attribute-inert)

  - [`hidden`](#attribute-hidden)

  - [`itemscope`](#attribute-itemscope)

  - [`itemtype`](#attribute-itemtype)

  - [`itemid`](#attribute-itemid)

  - [`itemprop`](#attribute-itemprop)

  - [`itemref`](#attribute-itemref)

  - [`popover`](#attribute-popover)

  - [`popovertarget`](#attribute-popovertarget)

  - [`popovertargetaction`](#attribute-popovertargetaction)

  - [`popovertargetaction`](#attribute-popovertargetaction)

  </nav>

</header>


<section>
  <h2 id="attribute-class"><code>class</code> attribute</h2>

  The `class` attribute relates an identifier to an HTML element

  The value must be a set of space-separated identifiers.

  ```html
  <html-element class="[ID ID etc]">
  ```
</section>


<section>
  <h2 id="attribute-id"><code>id</code> attribute</h2>

  The `id` attribute relates a unique identifier on an HTML element

  The `id` attribute relates an identifier that is unique to the document on an HTML element

  The value must be a non-empty unique identifier

  ```html
  <html-element id="attribute-[ID]">
  ```
</section>



<section>
  <h2 id="attribute-lang"><code>lang</code> attribute</h2>

  The `lang` attribute relates the primary content language on an HTML element. It's recommended to specify a `lang` atribute on the [Content Root](/en/html-content-root/)

  The value must be either a valid [BCP 47 language tag](https://www.rfc-editor.org/info/bcp47) or an empty string. The empty string indicates an unknown language

  ```html
  <html-element lang="['' | BCP-47-language-tag]">
  ```
</section>




<section>
  <h2 id="charset-attribute"><code>charset</code> attribute</h2>

  The `charset` attribute relates the document character encoding on a [`meta` element](/en/html-content-metas/#element-meta)

  The value must be "utf-8".

  ```html
  <meta charset="utf-8">
  ```
</section>



<section>
  <h2 id="attribute-dir"><code>dir</code> attribute</h2>

  The `dir` attribute relates the content direction on an HTML element

  The value is one of the following keywords:

  <dl>
    <div>
      <dt><code>ltr</code></dt>
      <dd>
        <p>The <code>ltr</code> keyword isolates a text with a left-to-right direction</p>
      </dd>
    </div>
    <div>
      <dt><code>rtl</code></dt>
      <dd>
        <p>The <code>rtl</code> keyword isolates a text with a right-to-left direction</p>
      </dd>
    </div>
    <div>
      <dt id="attribute-bdi-auto"><code>auto</code></dt>
      <dd>
        <p>The <code>auto</code> keyword isolates a text with an auto-generated direction</p>
      </dd>
    </div>
  </dl>

  The default value on a `bdi` element is the [`auto` value.](#attribute-bdi-auto)

  The default for both missing value and invalid value is the <code>undefined</code> state

  ```html
  <html-element dir="[ltr|rtl|auto]">
  ```
</section>


<section>
  <h2 id="attribute-translate"><code>translate</code> attribute</h2>

  The `translate` attribute relates the content translatable status on an HTML element

  The value is one of the following keywords:

  <dl>
    <div>
      <dt><code>yes</code></dt>
      <dd>
        <p>The <code>yes</code> keyword enables the translation of content and applicable attributes</p>
      </dd>
    </div>
    <div>
      <dt><code>no</code></dt>
      <dd>
        <p>The <code>no</code> keyword disables translation on content and translatable attributes</p>
      </dd>
    </div>
  </dl>

  The default for both missing value and invalid value are inherited from a parent or a user agent default.

  ```html
  <html-element translate="[yes|no]">
  ```
</section>




<section>
  <h2 id="attribute-title"><code>title</code> attribute</h2>

  The `title` attribute relates the following:

  - The subject of a definition on a [`dfn` element](/en/html-content-connotations/#element-dfn)

    The value must be a text

    ```html
    <dfn title="[text]"></dfn>
    ```

  - The subject of a definition on an [`abbr` element](/en/html-content-connotations/#element-abbr). But, the element must be the only child to a [`dfn` element](/en/html-content-connotations/#element-dfn) that has no `title` attribute

    The value must be a text

    ```html
    <dfn>
      <abbr title="[text]"></abbr>
    </dfn>
    ```

  - An expansion of an abbreviation on an [`abbr` element](/en/html-content-connotations/#element-abbr)

    The value must be a text

    ```html
    <abbr title="[expansion-text]"></abbr>
    ```

  - The name of a CSS set on the following elements: [`link`,](/en/html-content-metas/#element-link) and [`style`](/en/html-content-metas/#element-style)

    Note: The `title` attribute on a `link` element requires the [`rel` attribute](#attribute-rel) to contain the `stylesheet` keyword

    The value must be a text

    ```html
    <style title="[CSS-set-name]"></style>
    ```

  - The description of a pattern on an [`input` element](/en/html-content-forms/#element-input) with a [`pattern` attribute](#attribute-pattern)

    The value must be a text

    ```html
    <input pattern="[regex]" title="[description]"]>
    ```

  - An advisory information on other HTML elements

    The value must be a text.

    ```html
    <other-html-element title="[advisory-information]">
    ```
</section>
    



<section>
  <h2 id="attribute-rel"><code>rel</code> attribute</h2>

  The `rel` attribute relates a [resource connection type](https://html.spec.whatwg.org/#linkTypes) on the following elements: 
  [`link`,](/en/html-content-metas/#element-link) 
  [`a`,](/en/html-content-connotations/#element-a) 
  [`area`,](/en/html-content-objects/#element-area) and 
  [`form`.](/en/html-content-forms/#element-form)

  The value must be a set of unique space-separated tokens. Each token is based on an element as follows:

  - The supported tokens on: an [`a` element](/en/html-content-connotations/#element-a), an [`area` element](/en/html-content-objects/#element-area), and a [`form` element](/en/html-content-forms/#element-form); are as follows:

    <dl>
      <div>
        <dt><code>noferrer</code></dt>
        <dd>The <code>noreferrer</code> token avoids sending referrer information to the external resource</dd>
      </div>
      <div>
        <dt><code>noopener</code></dt>
        <dd>The <code>noopener</code> token removes the auxiliary browsing context of a new window that opens the external resource</dd>
      </div>
      <div>
        <dt><code>opener</code></dt>
        <dd>The <code>opener</code> token includes the auxiliary browsing context of a new window that opens the external resource</dd>
      </div>
    </dl>

    ```html
    <applicable-html-element rel="[token token etc.]">
    ```

  - The [supported `rel` tokens on a `link` element](https://html.spec.whatwg.org/#the-link-element:attr-link-rel-9) are of 2 groups. 

    The following first set of tokens extends a [`link` element](/en/html-content-metas/#element-link): 
    `alternate`, `next`, `search`, `icon`, `manifest`, `pingback`, `stylesheet`, `preload`, and `modulepreload`

    The following second set of follows applies to `icon`, `manifest`, `pingback`, and `stylesheet` tokens.
    <dl>
      <div>
        <dt><code>dns-prefetch</code></dt>
        <dd>
          <p>
            The <code>dns-prefetch</code> token relates for an early DNS lookup on the resource.
          </p>
        </dd>
      </div>
      <div>
        <dt><code>preconnect</code></dt>
        <dd>
          <p>
            The <code>preconnect</code> token relates for an early connection to the resource.
          </p>
        </dd>
      </div>
      <div>
        <dt><code>prefetch</code></dt>
        <dd>
          <p>
            The <code>prefetch</code> token relates at fetching the resource for future navigations.
          </p>
        </dd>
      </div>
    </dl>

    ```html
    <link rel="[dns-prefetch|preconnect|prefetch] [icon|stylesheet|manifest|pingback|icon]" href="[URL]">
    ```
</section>



<section>
  <h2 id="attribute-type"><code>type</code> attribute</h2>

  The `type` attribute relates the following:

  - Resource format on the following elements:
    <a href="/en/html-content-metas/#element-link"><code>link</code>,</a> 
    <a href="/en/html-content-connotations/#element-a"><code>a</code>,</a> 
    <a href="/en/html-content-objects/#element-embed"><code>embed</code>,</a> 
    <a href="/en/html-content-objects/#element-object"><code>object</code>,</a> and 
    <a href="/en/html-content-objects/#element-source"><code>source</code>.</a>

    <details>
      <summary>Notes</summary>

      - On a `source` element whose parent is a `picture` element, the `type` attribute helps a user agent skip to the next `source` element if it does not support the given format

      - On a `source` element whose parent element is an `audio` element or a `video` element, it helps a user agent determine if it can play the media before fetching it
    </details>

    The value must be a MIME Type

    ```html
    <applicable-html-element type="[MIME Type]">
    ```

  - List Marker on an [`ol` element](/en/html-content-layers/#element-ol)

    The value is one of the following keywords:
    <dl>
      <div id="attribute-type-ol-one">
        <dt><code>1</code></dt>
        <dd>
          <p>The number one character keyword specifies decimal numbers as the marker type for an ordered list.</p>
        </dd>
      </div>
      <div>
        <dt><code>a</code></dt>
        <dd>
          <p>The lowercase letter a character keyword specifies the lowercase Latin alphabet as the marker type for an ordered list</p>
        </dd>
      </div>
      <div>
        <dt><code>A</code></dt>
        <dd>
          <p>The uppercase letter A character keyword specifies an uppercase Latin alphabet as the marker type for an ordered list</p>
        </dd>
      </div>
      <div>
        <dt><code>i</code></dt>
        <dd>
          <p>The lowercase letter i character keyword specifies a lowercase Roman numerals as the marker type for an ordered list</p>
        </dd>
      </div>
      <div>
        <dt><code>I</code></dt>
        <dd>
          <p>The uppercase letter I character keyword specifies an uppercase roman numerals as the marker type for an ordered list</p>
        </dd>
      </div>
    </dl>

    The default for both missing value and invalid value is the [number 1 character keyword](#attribute-type-ol-one)

    ```html
    <ol type="[1|a|A|i|I]"></ol>
    ```

  - Data Type on an [`input` element](/en/html-content-forms/#element-input)

    The value is one of the following keywords: 
    [`hidden`,](/en/html-content-forms/#sort-hidden-form) 
    [`text`,](/en/html-content-forms/#sort-text-form) 
    [`search`,](/en/html-content-forms/#sort-search-form) 
    [`tel`,](/en/html-content-forms/#sort-telephone-form) 
    [`url`,](/en/html-content-forms/#sort-url-form) 
    [`email`,](/en/html-content-forms/#sort-email-form) 
    [`password`,](/en/html-content-forms/#sort-sensitive-form) 
    [`date`,](/en/html-content-forms/#sort-date-form) 
    [`month`,](/en/html-content-forms/#sort-month-form) 
    [`week`,](/en/html-content-forms/#sort-week-form) 
    [`time`,](/en/html-content-forms/#sort-time-form) 
    [`datetime-local`,](/en/html-content-forms/#sort-local-datetime-form) 
    [`number`,](/en/html-content-forms/#sort-number-form) 
    [`range`,](/en/html-content-forms/#sort-range-form) 
    [`color`,](/en/html-content-forms/#sort-color-form) 
    [`checkbox`,](/en/html-content-forms/#sort-checkbox-form) 
    [`radio`,](/en/html-content-forms/#sort-radio-button-form) 
    [`file`,](/en/html-content-forms/#sort-file-form) 
    [`submit`,](/en/html-content-forms/#sort-void-submit-button-form) 
    [`image`,](/en/html-content-forms/#sort-image-button-form) 
    [`reset`,](/en/html-content-forms/#sort-void-reset-button-form) and 
    [`button`.](/en/html-content-forms/#sort-void-custom-button-form) 

    The default for both missing value and invalid value is the `text` keyword

    ```html
    <input type="[keyword]">
    ```

  - Button Type on a [`button` element](/en/html-content-forms/#element-button)

    The value is one of the following keywords:
    [`submit`,](/en/html-content-forms/#sort-non-void-submit-button-form)
    [`reset`,](/en/html-content-forms/#sort-non-void-reset-button-form)
    [`button`,](/en/html-content-forms/#sort-non-void-custom-button-form)

    The default for both missing value and invalid value is the `submit` keyword

  - Script Type on a [`script` element.](/en/html-content-metas/#element-script)

    The value must be one of the following keywords: `module`, `importmap`, and a MIME type

    ```html
    <script type="[module|importmap|MIME-Type]"></script>
    ```
</section>



<section>
  <h2 id="attribute-hreflang"><code>hreflang</code> attribute</h2>

  The `hreflang` attribute relates the language of a resource on the following elements: [`link`,](/en/html-content-metas/#element-link) and [`a`.](/en/html-content-connotations/#element-a)

  The value must be a valid [BCP-47 language tag](https://www.rfc-editor.org/info/bcp47)

  ```html
  <applicable-html-element hreflang="[BCP-47-language-tag]">
  ```
</section>



<section>
  <h2 id="attribute-as"><code>as</code> attribute</h2>

  The `as` attribute relates a preloaded resource on a [`link` element.](/en/html-content-metas/#element-link)

  The value is one of the following tokens: `fetch`, `audio`, `audioworklet`, `document`, `embed`, `font`, `frame`, `iframe`, `image`, `json`, `manifest`, `object`, `paintworklet`, `report`, `script`, `serviceworker`, `sharedworker`, `style`, `track`, `video`, `webidentity`, `worker`, and `xslt`.

  The default for both missing value and invalid value is an error state. But, The default missing value of a `link` element with a `rel` attribute having `modulepreload` keyword is the `script` value.

  ```html
  <link as="[resource-model]">
  ```
</section>



<section>
  <h2 id="attribute-blocking"><code>blocking</code> attribute</h2>

  The `blocking` relates a blocked operation while fetching a resource on the following elements:
  <a href="/en/html-content-metas/#element-link"><code>link</code>,</a>
  <a href="/en/html-content-metas/#element-style"><code>style</code>,</a> and 
  <a href="/en/html-content-metas/#element-script"><code>script</code>.</a>

  The value must be the `render` keyword.

  ```html
  <applicable-html-element blocking="render">
  ```
</section>



<section>
  <h2 id="attribute-nonce"><code>nonce</code> attribute</h2>

  The `nonce` attribute relates a one-time number to allow a fetch operation on an HTML element

  The value must be a text

  ```html
  <html-element nonce="[text]">
  ```
</section>



<section>
  <h2 id="attribute-fetchpriority"><code>fetchpriority</code> attribute</h2>

  The `fetchpriority` attribute relates a fetch priority hint for the resource on the following elements:
  <a href="/en/html-content-metas/#element-link"><code>link</code>,</a> 
  <a href="/en/html-content-metas/#element-script"><code>script</code>,</a> and 
  <a href="/en/html-content-objects/#element-img"><code>img</code>.</a>

  The value is one of the following keywords:

  <dl>
    <div>
      <dt><code>high</code></dt>
      <dd>
        <p>The <code>high</code> keyword signals a high-priority fetch relative to other resources with the same destination</p>
      </dd>
    </div>
    <div>
      <dt><code>low</code></dt>
      <dd>
        <p>The <code>low</code> keyword signals a low-priority fetch relative to other resources with the same destination</p>
      </dd>
    </div>
    <div id="attribute-fetchpriority-auto">
      <dt><code>auto</code></dt>
      <dd>
        <p>The <code>auto</code> keyword signals an auto-priority fetch relative to other resources with the same destination</p>
      </dd>
    </div>
  </dl>

  The default for both missing value and invalid values is the [`auto` keyword](#attribute-fetchpriority-auto)

  ```html
  <applicable-html-element fetchpriority="[auto|low|high]">
  ```
</section>



<section>
  <h2 id="attribute-crossorigin"><code>crossorigin</code> attribute</h2>

  The `crossorigin` attribute relates the status of cross-origin sharings on the following elements:
  [`script`,](/en/html-content-metas/#element-script) 
  [`link`,](/en/html-content-metas/#element-link)
  [`img`,](/en/html-content-objects/#element-img)
  [`audio`,](/en/html-content-objects/#element-audio) and
  [`video`.](/en/html-content-objects/#element-audio)

  The value is one of the following keywords:

  <dl>
    <div id="attribute-crossorigin-anonymous">
      <dt><code>anonymous</code></dt>
      <dd>
        <p>The <code>anonynous</code> keyword sends a cross-origin request without a credential</p>
      </dd>
    </div>
    <div>
      <dt><code>use-credentials</code></dt>
      <dd>
        <p>The <code>use-credentials</code> keyword sends a cross-origin request with a credential.</p>
      </dd>
    </div>
  </dl>

  The default missing value is the No CORS state. And, the default invalid value is the [`anonymous` keyword.](#attribute-crossorigin-anonymous)

  ```html
  <applicable-html-element crossorigin="[anonymous|use-credentials]">
  ```
</section>



<section>
  <h2 id="attribute-referrerpolicy"><code>referrerpolicy</code> attribute</h2>

  The `referrerpolicy` relates a referrer for the following:

  - fetching a resource on the following elements:
    [`link`,](/en/html-content-metas/#element-link) 
    [`script`,](/en/html-content-metas/#element-script) and
    [`iframe`.](/en/html-content-objects/#element-iframe)

  - following a hyperlink on the following elements: [`a`,](/en/html-content-connotations/#element-a) and [`area`.](/en/html-content-objects/#element-area)

  The value is one following keywords called policies:

  <dl>
    <div id="attribute-referrerpolicy-no-referrer">
      <dt><code>no-referrer</code></dt>
      <dd>
        <p>The `no-referrer` policy sends no Referrer URL along with any request</p>
      </dd>
    </div>
    <div id="attribute-referrerpolicy-unsafe-url">
      <dt><code>unsafe-url</code></dt>
      <dd>
        <p>The <code>unsafe-url</code> policy sends a Referrer URL along with any request</p>
      </dd>
    </div>
    <div id="attribute-referrerpolicy-no-referrer-when-downgrade">
      <dt><code>no-referrer-when-downgrade</code></dt>
      <dd>
        <p>The <code>no-referrer-when-downgrade</code> policy does either of the following:</p>
        <ul>
          <li>
            <p><a href="#attribute-referrerpolicy-no-referrer"><code>no-referrer</code> policy</a> to less secured protocols</p>
          </li>
          <li>
            <p><a href="#attribute-referrerpolicy-unsafe-url"><code>unsafe-url</code> policy</a> to equal or more secure protocols</p>
          </li>
        </ul>
      </dd>
    </div>
    <div id="attribute-referrerpolicy-origin">
      <dt><code>origin</code></dt>
      <dd>
        <p>The <code>origin</code> policy sends a URL origin along with any request</p>
      </dd>
    </div>
    <div>
      <dt><code>strict-origin</code></dt>
      <dd>
        <p>This origin does either of the following:</p>
        <ul>
          <li>
            <p><a href="#attribute-referrerpolicy-origin"><code>origin</code> policy</a> to equal or more secure protocols</p>
          </li>
          <li>
            <p><a href="#attribute-referrerpolicy-no-referrer"><code>no-referrer</code> policy</a> to less secured protocols</p>
          </li>
        </ul>
      </dd>
    </div>
    <div>
      <dt><code>same-origin</code></dt>
      <dd>
        <p>This policy sends either of the following:</p>
        <ul>
          <li>
            <p>A Referrer URL along with same-origin requests</p>
          </li>
          <li>
            <p>No Referrer URL along with cross-origin requests</p>
          </li>
        </ul>
      </dd>
    </div>
    <div id="attribute-referrerpolicy-origin-when-cross-origin">
      <dt><code>origin-when-cross-origin</code></dt>
      <dd>
        <p>This policy sends either of the following:</p>
        <ul>
          <li>
            <p>A Referrer URL along with same-origin requests</p>
          </li>
          <li>
            <p>A URL origin along with cross-origin request</p>
          </li>
        </ul>
      </dd>
    </div>
    <div>
      <dt><code>strict-origin-when-cross-origin</code></dt>
      <dd>
        <p>The <code>strict-origin-when-cross-origin</code> policy does the <a href="#attribute-referrerpolicy-origin-when-cross-origin"><code>origin-when-cross-origin</code> policy</a> to equal or more secure protocols.</p>
      </dd>
    </div>
    <div id="attribute-referrerpolicy-">
      <dt><code>""</code></dt>
      <dd>
        <p>The empty string policy sends an inherited referrer policy. If none, it does the <a href="#attribute-referrerpolicy-no-referrer-when-downgrade"><code>no-referrer-when-downgrade</code> policy.</a></p>
      </dd>
    </div>
  </dl>

  Note: A Referrer URL is a URL without the following: fragment, username, and password

  The default for both missing value and invalid value is the [empty string policy](#attribute-referrerpolicy-)

  ```html
  <applicable-html-element referrerpolicy="[policy-token]">
  ```
</section>



<section>
  <h2 id="attribute-integrity"><code>integrity</code> attribute</h2>

  The `integrity` attribute relates a manipulation check on the following elements: [`link`,](/en/html-content-metas/#element-link) and [`script`.](/en/html-content-metas/#element-script)

  The value must be a text

  ```html
  <applicable-html-element integrity="[text]">
  ```
</section>



<section>
  <h2 id="attribute-async"><code>async</code> attribute</h2>

  The `async` boolean attribute relates an execution of a script when it's available on a [`script` element](/en/html-content-metas/#element-script)

  ```html
  <script async></script>
  ```
</section>



<section>
  <h2 id="attribute-defer"><code>defer</code> attribute</h2>

  The `defer` boolean attribute relates an execution of a script when the DOM is ready on a [`script` element](/en/html-content-metas/#element-script)

  ```html
  <script defer></script>
  ```
</section>



<section>
  <h2 id="attribute-nomodule"><code>nomodule</code> attribute</h2>

  The `nomodule` boolean attribute relates a module fallback on a [`script` element](/en/html-content-metas/#element-script)

  ```html
  <script nomodule></script>
  ```
</section>



<section>
  <h2 id="attribute-media"><code>media</code> attribute</h2>

  The `media` attribute relates a device restriction on the following elements:
  [`link`,](/en/html-content-metas/#element-link) 
  [`style`,](/en/html-content-metas/#element-style) 
  [`meta`,](/en/html-content-metas/#element-meta) and
  [`source`.](/en/html-content-objects/#element-source)

  The value must be a valid [media query list](https://w3c.github.io/csswg-drafts/mediaqueries/)

  ```html
  <applicable-html-element media="[media-query-list]"]>
  ```
</section>



<section>
  <h2 id="attribute-color"><code>color</code> attribute</h2>

  The `color` attribute relates an icon color for launchers on a [`link` element.](/en/html-content-metas/#element-link)

  The value must be a [CSS color production](https://drafts.csswg.org/css-color/#typedef-color).

  ```html
  <link color=[css-color-value]>
  ```
</section>



<section>
  <h2 id="attribute-http-equiv"><code>http-equiv</code> attribute</h2>

  The `http-equiv` attribute relates a [pragma directive key on a `meta` element](/en/html-content-metas/#element-meta)

  The value is one of the following keywords: 
  [`content-type`,](/en/html-content-metas/#sort-charset) 
  [`default-style`,](/en/html-content-metas/#sort-stylesheet-default) 
  [`refresh`,](/en/html-content-metas/#sort-timeout) and 
  [`content-security-policy`.](/en/html-content-metas/#sort-security-policy)

  ```html
  <meta http-equiv="[keyword]">
  ```
</section>



<section>
  <h2 id="attribute-content"><code>content</code> attribute</h2>

  The `content` attribute relates the value of a [document metadata key](#attribute-name-element-meta) or [pragma directive key](#attribute-http-equiv) on a [`meta` element](/en/html-content-metas/#element-meta) 

  The value must be one of the following for the respective key:

  - A free-form string for each of the following keys: 
  [`name="application-name"`](/en/html-content-metas/#sort-app-name), 
  [`name="author"`](/en/html-content-metas/#sort-author), 
  [`name="description"`](/en/html-content-metas/#sort-description), and 
  [`name"generator"`](/en/html-content-metas/#sort-generator)

    ```html
    <meta name="[application-name|author|description|generator]" content="free-form-string">
    ```

  - A set of comma-separated strings for the [`name="keywords"`](/en/html-content-metas/#sort-keywords) key

    ```html
    <meta name="keywords" content="[comma-separated-strings]">
    ```

  - A [Referrer Policy](https://w3c.github.io/webappsec-referrer-policy/#referrer-policy) for the [`name="referrer"`](/en/html-content-metas/#sort-referrer) key

    ```html
    <meta name="refferer" content="[referrer-policy]">
    ```

  - A string that matches the [CSS color production](https://drafts.csswg.org/css-color/#typedef-color) for the [`name="theme-color"`](/en/html-content-metas/#sort-theme-color) key

    ```html
    <meta name="theme-color" content="[CSS-color-production]">
    ```

  - A string that matches the [CSS color-scheme property value](https://drafts.csswg.org/css-color-adjust/#color-scheme-prop) for the [`name="color-scheme"`](/en/html-content-metas/#sort-color-scheme) key

    ```html
    <meta name="color-scheme" content="[color-scheme-value]">
    ```

  - The string "text/html; charset=utf-8" for the  [`http-equiv="content-type"`](/en/html-content-metas/#sort-charset) key

    ```html
    <meta http-equiv="content-type" content="text/html; charset=utf-8">
    ```

  - The value of the `title` attribute of a `link` element or a `style` element for the [`http-equiv="default-style"`](/en/html-content-metas/#sort-stylesheet-default) key

    ```html
    <meta http-equiv="default-style" content="[title-attribute-value]">
    ```

  - Either of the following for the [`http-equiv="refresh"`](/en/html-content-metas/#sort-timeout) key:
    - A valid non-negative integer
    - A valid non-negative integer, semi-colon, whitespace, "URL=", and a URL address

    ```html
    <meta http-equiv="refresh" content="300">

    <!-- or -->

    <meta http-equiv="refresh" content="300; URL=example.com/page">
    ```

  - A valid [content security policy](https://w3c.github.io/webappsec-csp/#grammardef-serialized-policy) for the [`http-equiv="content-security-policy"`](/en/html-content-metas/#sort-security-policy) key. But, the policy must exclude the following directives: `report-uri`, `frame-ancestors`, or `sandbox`

    ```html
    <meta http-equiv="content-security-policy" content="[policy]">
    ```
</section>




<section>
  <h2 id="attribute-shadowrootmode"><code>shadow<wbr>root<wbr>mode</code> attribute</h2>

  The `shadowrootmode` attribute relates access to declarative shadow root on a [`template` element](/en/html-content-metas/#element-template)

  The value is one of the following keywords:

  <dl>
    <div>
      <dt><code>open</code></dt>
      <dd>
        <p>The <code>open</code> keyword relates the <code>template</code> element as an open declarative shadow root</p>
      </dd>
    </div>
    <div><code>closed</code></div>
    <dd>
      <p>The <code>closed</code> keyword relates the <code>template</code> element as a closed declarative shadow root</p>
    </dd>
  </dl>

  The default for both missing value and invalid value is a none state.

  ```html
  <template shadowrootmode="[open|closed]"></template>
  ```
</section>



<section>
  <h2 id="attribute-shadowrootdelegatesfocus"><code>shadow<wbr>root<wbr>delegates<wbr>focus</code> attribute</h2>

  The `shadowrootdelegatesfocus` boolean attribute relates a focus delegation to a [declarative shadow root](#attribute-shadowrootmode) on a [`template` element.](/en/html-content-metas/#element-template)

  ```html
  <template shadowrootdelegatesfocus></template>
  ```
</section>



<section>
  <h2 id="attribute-is"><code>is</code> attribute</h2>

  The `is` attribute relates an [extended custom element](https://html.spec.whatwg.org/#customized-built-in-element) on a standard HTML element

  The value must be the [name](#attribute-name) of an extended custom element

  ```html
  <standard-html-element is="[name-of-extended-custom-element]">
  ```
</section>  




<section>
  <h2 id="attribute-slot"><code>slot</code> attribute</h2>

  The `slot` attribute relates a [`slot` element](/en/html-content-metas/#element-slot) on an HTML element

  The value must be the [name](#attribute-name) of a `slot` element

  ```html
  <html-element slot="[valid-slot-element-name]">
  ```
</section>



<section>
  <h2 id="attribute-style"><code>style</code> attribute</h2>

  The `style` attribute relates CSS declarations on an HTML element

  The value must be a text content that gives a [conformant style sheet](https://drafts.csswg.org/css-syntax/#conform-classes)

  ```html
  <html-element style="[css-declarations]">
  ```
</section>



<section>
  <h2 id="attribute-data-*"><code>data-*</code> attribute</h2>

  The `data-*` attribute relates a simple data store on an HTML element

  The value must be a text content that conforms to the data type.

  ```html
  <html-element data-[name]="[text-value]">
  ```
</section>



<section>
  <h2 id="attribute-usemap"><code>usemap</code> attribute</h2>

  The `usemap` attribute relates a [`map` element](/en/html-content-objects/#element-map) on an [`img` element](/en/html-content-objects/#element-img)

  The value must be the [hash-name](https://html.spec.whatwg.org/#valid-hash-name-reference) of a `map` element

  ```html
  <img usemap="#[name]">
  ```
</section>



<section>
  <h2 id="attribute-ismap"><code>ismap</code> attribute</h2>

  The `ismap` boolean attribute relates access to a server-side image map on an [`img` element](/en/html-content-objects/#element-img)

  ```html
  <img ismap>
  ```
</section>



<section>
  <h2 id="attribute-srcset"><code>srcset</code> attribute</h2>

  The `srcset` attribute relates an address of a responsive image resource on the following elements: [`source`,](/en/html-content-objects/#element-source) and [`img`.](/en/html-content-objects/#element-img)

  The value must be one or more comma-separated Image Candidate Strings (IMS). Each IMS specifies a space-separation of the following:

  - An image address that must be a valid URL address
  - Either of the following unique descriptor
    - A width descriptor composed of both an integer number greater than zero and a small letter "w" character. An example is 1w or 3w.

    - A pixel-density descriptor composed of both a floating-point number greater than zero and a small letter "x" character. An example is 1x and 5.8x    

  ```html
  <applicable-html-element srcset="[IMS, IMS, etc.]">
  ```
</section>



<section>
  <h2 id="attribute-imagesrcset"><code>imagesrcset</code> attribute</h2>

  The `imagesrcset` attribute is a synonym of the [`srcset` attribute](#attribute-srcset) but on a [`link` element](/en/html-content-metas/#element-link)

  ```html
  <form imagesrcset="[IMS, IMS, etc.]"></form>
  ```
</section>



<section>
  <h2 id="attribute-src"><code>src</code> attribute</h2>

  The `src` attribute relates an address of the resource on the following elements:
  <a href="/en/html-content-forms/#element-input"><code>input</code>,</a> 
  <a href="/en/html-content-objects/#element-img"><code>img</code>,</a> 
  <a href="/en/html-content-objects/#element-audio"><code>audio</code>,</a> 
  <a href="/en/html-content-objects/#element-video"><code>video</code>,</a> 
  <a href="/en/html-content-objects/#element-source"><code>source</code>,</a> 
  <a href="/en/html-content-objects/#element-track"><code>track</code>,</a> 
  <a href="/en/html-content-objects/#element-iframe"><code>iframe</code>,</a> 
  <a href="/en/html-content-objects/#element-embed"><code>embed</code>,</a> and 
  <a href="/en/html-content-metas/#element-script"><code>script</code></a>

  The value must be a valid URL address.

  ```html
  <applicable-html-element src="[valid-url]">
  ```
</section>



<section>
  <h2 id="attribute-data"><code>data</code> attribute</h2>

  The `data` attribute relates the address of a generic object resource on an [`object` element](/en/html-content-objects/#element-object)

  The value must be a valid URL address.

  ```html
  <object data=""></object>
  ```
</section>



<section>
  <h2 id="attribute-loading"><code>loading</code> attribute</h2>

  The `loading` attribute relates a loading mechanism on the following elements when out of the viewport: [`img`,](/en/html-content-objects/#element-img) and [`iframe`.](/en/html-content-objects/#element-iframe)

  The value is either of the following keywords:

  <dl>
    <div>
      <dt><code>lazy</code></dt>
      <dd>The <code>lazy</code> keyword fetches a resource on conditions</dd>
    </div>
    <div id="attribute-loading-eager">
      <dt><code>eager</code></dt>
      <dd>The <code>eager</code> keyword fetches a resource immediately</dd>
    </div>
  </dl>

  The default for both missing value and invalid value is the [`eager` keyword](#attribute-loading-eager)

  ```html
  <applicable-html-element loading="[lazy|eager]">
  ```
</section>




<section>
  <h2 id="attribute-decoding"><code>decoding</code> attribute</h2>

  The `decoding` attribute relates an image decoding hint on an [`img` element](/en/html-content-objects/#element-img)

  The value is one of the following keywords:

  <dl>
    <div>
      <dt><code>sync</code></dt>
      <dd>
        <p>The <code>sync</code> keyword decodes an image synchronously for atomic presentation with other content</p>
      </dd>
    </div>
    <div>
      <dt><code>asyc</code></dt>
      <dd>
        <p>The <code>async</code> keyword decodes an image asynchronously to avoid delaying the presentation of other content</p>
      </dd>
    </div>
    <div id="attribute-decoding-auto">
      <dt><code>auto</code></dt>
      <dd>
        <p>The <code>auto</code> keyword relates no decoding preference</p>
      </dd>
    </div>
  </dl>

  The default for both missing value and invalid value is the [`auto` keyword](#attribute-decoding-auto)

  ```html
  <img decoding="[auto|sync|async]">
  ```
</section>



<section>
  <h2 id="attribute-shape"><code>shape</code> attribute</h2>

  The `shape` attribute relates a shape model on an [`area` element](/en/html-content-objects/#element-area)

  The value is one of the following keywords: 

  <dl>
    <div>
      <dt><code>poly</code></dt>
      <dd>
        <p>The <code>poly</code> keyword relates a polygonal shape for an image map area</p>
      </dd>
    </div>
    <div id="attribute-shape-rect">
      <dt><code>rect</code></dt>
      <dd>
        <p>The <code>rect</code> keyword relates a rectangular shape for an image map area</p>
      </dd>
    </div>
    <div>
      <dt><code>circle</code></dt>
      <dd>
        <p>The <code>circle</code> keyword relates a circular shape for an image map area</p>
      </dd>
    </div>
    <div>
      <dt><code>default</code></dt>
      <dd>
        <p>The <code>default</code> keyword relates the whole shape for an image map area</p>
      </dd>
    </div>
  </dl>

  The default for both missing value and invalid value is the [`rect` keyword](#attribute-shape-rect)

  ```html
  <area shape="[rect|poly|circle|default]">
  ```
</section>



<section>
  <h2 id="attribute-width"><code>width</code> attribute</h2>

  The `width` attribute relates the following:

  - The wideness of an image resource on an [`input` element.](/en/html-content-forms/#element-input) 

  - A highness on the following elements:
    [`svg`,](/en/html-content-objects/#element-svg) 
    [`img`,](/en/html-content-objects/#element-img) 
    [`canvas`,](/en/html-content-objects/#element-canvas) 
    [`video`,](/en/html-content-objects/#element-video) 
    [`source`,](/en/html-content-objects/#element-source) 
    [`iframe`,](/en/html-content-objects/#element-iframe) 
    [`embed`,](/en/html-content-objects/#element-embed) 
    [`object`,](/en/html-content-objects/#element-object) 

  The value is a non-negative integer that is rendered in CSS pixels.

  ```html
  <applicable-html-element width="[non-negative-integer]">
  ```
</section>



<section>
  <h2 id="attribute-imagesizes"><code>imagesizes</code> attribute</h2>

  The `imagesizes` attribute relates the wideness of a responsive image resource on a [`link` element](/en/html-content-metas/#element-link)

  The value must be a set of comma-separated tokens. Each token contains both a media-condition and a width, separated by a space.

  ```html
  <link sizes="[[media-condition width], [media-condition width], etc.]">
  ```
</section>



<section>
  <h2 id="attribute-sizes"><code>sizes</code> attribute</h2>

  The `sizes` attribute relates the following:

  - The wideness and highness of an icon resource on a [`link` element](/en/html-content-metas/#element-link)

    The value must be one of the following tokens:

    - An `any` keyword

    - A string of 2 valid non-negative integers separated by a case-insensitive "x" character. Each number must not have a leading zero character (0). 
    
      The first number relates the width while the second number relates the height. Both in CSS pixels

    ```html
    <link sizes="[any|20x30]">
    ```
  - A synonym of the [`imagesizes` attribute](#attribute-imagesizes) but on the following elements: [`img`,](/en/html-content-objects/#element-img) and [`source`.](/en/html-content-objects/#element-source)

    ```html
    <applicable-html-element sizes="[[media-condition width], [media-condition width], etc.]">
    ```
</section>




<section>
  <h2 id="attribute-height"><code>height</code> attribute</h2>

  The `height` attribute relates the following:

  - The highnes of the image resource on an [`input` element.](/en/html-content-forms/#element-input) 

  - An highness on the following elements:
    <a href="/en/html-content-objects/#element-svg"><code>svg</code>,</a> 
    <a href="/en/html-content-objects/#element-img"><code>img</code>,</a> 
    <a href="/en/html-content-objects/#element-canvas"><code>canvas</code>,</a> 
    <a href="/en/html-content-objects/#element-video"><code>video</code>,</a> 
    <a href="/en/html-content-objects/#element-source"><code>source</code>,</a> 
    <a href="/en/html-content-objects/#element-iframe"><code>iframe</code>,</a> 
    <a href="/en/html-content-objects/#element-embed"><code>embed</code>,</a> and
    <a href="/en/html-content-objects/#element-object"><code>object</code></a>

  The value is a non-negative integer that is rendered in CSS pixels.

  ```html
  <applicable-html-element height="[non-negative-integer]">
  ```
</section>



<section>
  <h2 id="attribute-coords"><code>coords</code> attribute</h2>

  The `coords` attribute relates a freeform wideness and highness on an [`area` element](/en/html-content-objects/#element-area)

  The value must be a valid list of [floating-point numbers.](https://html.spec.whatwg.org/#attr-area-coords) This number relates the coordinates of the intended shape

  ```html
  <area coords="[list-of-floating-point-numbers]">
  ```
</section>



<section>
  <h2 id="attribute-alt"><code>alt</code> attribute</h2>

  The `alt` attribute relates an alternative text of an image resource on the following elements:
  <a href="/en/html-content-objects/#element-img"><code>img</code>,</a> 
  <a href="/en/html-content-objects/#element-area"><code>area</code>,</a> and 
  <a href="/en/html-content-forms/#element-input"><code>input</code>.</a>

  The value must be an empty or non-empty text

  ```html
  <applicable-html-element alt="[text]">
  ```
</section>




<section>
  <h2 id="attribute-poster"><code>poster</code> attribute</h2>

  The `poster` attribute relates an address of a poster image resource on a [`video` element](/en/html-content-objects/#element-video)

  The value must be a valid URL address.

  ```html
  <video poster="[valid-url]"></video>
  ```
</section>




<section>
  <h2 id="attribute-preload"><code>preload</code> attribute</h2>

  The `preload` attribute relates the fetching mechanism on the following elements: [`audio`,](/en/html-content-objects/#element-audio) and [`video`.](/en/html-content-objects/#element-video)

  The value is one of the following keywords:

  <dl>
    <div>
      <dt><code>none</code></dt>
      <dd>
        <p>The <code>none</code> keyword hints at no download of the resource</p>
      </dd>
    </div>
    <div id="attribute-preload-metadata">
      <dt><code>metadata</code></dt>
      <dd>
        <p>The <code>metadata</code> keyword hints at fetching the metadata of a media resource</p>
      </dd>
    </div>
    <div>
      <dt><code>auto</code></dt>
      <dd>
        <p>The <code>auto</code> keyword hints at fetching the whole of a media resource</p>
      </dd>
    </div>
  </dl>

  The default for both missing value and invalid value is browser-specific but [`metadata` keyword](#attribute-preload-metadata) is recommended.

  ```html
  <applicable-html-element preload="[metadata|none|auto]">
  ```
</section>



<section>
  <h2 id="attribute-autoplay"><code>autoplay</code> attribute</h2>

  The `autoplay` boolean attribute relates an automatic play functionality on the following elements: [`audio`,](/en/html-content-objects/#element-audio) and [`video`.](/en/html-content-objects/#element-video)

  ```html
  <applicable-html-element autoplay>
  ```
</section>




<section>
  <h2 id="attribute-loop"><code>loop</code> attribute</h2>

  The `loop` boolean attribute relates an automatic repeat functionality on the following elements: [`audio`,](/en/html-content-objects/#element-audio) and [`video`.](/en/html-content-objects/#element-video)

  ```html
  <applicable-html-element loop>
  ```
</section>



<section>
  <h2 id="attribute-muted"><code>muted</code> attribute</h2>

  The `muted` boolean attribute relates a no-sound functionality on the following elements: [`audio`,](/en/html-content-objects/#element-audio) and [`video`.](/en/html-content-objects/#element-video)

  ```html
  <applicable-html-element muted>
  ```
</section>



<section>
  <h2 id="attribute-playsinline"><code>playsinline</code> attribute</h2>

  The `playsinline` boolean attribute relates an inline play functionality on a [`video` element](/en/html-content-objects/#element-video)  

  ```html
  <applicable-html-element playsinline>
  ```
</section>



<section>
  <h2 id="attribute-srclang"><code>srclang</code> attribute</h2>

  The `srclang` attribute relates the primary language of a timed text resource on a [`track` element](/en/html-content-objects/#element-track)

  The value must be a valid [BCP 47 language tag](https://www.rfc-editor.org/info/bcp47)

  ```html
  <track srclang="[BCP-47-language-tag]">
  ```
</section>



<section>
  <h2 id="attribute-default"><code>default</code> attribute</h2>

  The `default` boolean attribute relates an initial preference pending user's choice on a [`track` element](/en/html-content-objects/#element-track)

  ```html
  <track default>
  ```
</section>



<section>
  <h2 id="attribute-controls"><code>controls</code> attribute</h2>

  The `controls` boolean attribute relates a preference for the user agent's control buttons on the following elements: [`audio`,](/en/html-content-objects/#element-audio) and [`video`.](/en/html-content-objects/#element-video)

  ```html
  <applicable-html-element controls>
  ```
</section>



<section>
  <h2 id="attribute-kind"><code>kind</code> attribute</h2>

  The `kind` attribute relates a sort of text track resource on a [`track` element](/en/html-content-objects/#element-track)

  The value is one of the following keywords:  

  <dl>
    <div id="attribute-kind-subtitles">
      <dt><code>subtitles</code></dt>
      <dd>The <code>subtitles</code> keyword specifies the resource as an alternative text for the sound of an <code>audio</code> or a <code>video</code> element</dd>
    </div>
    <div>
      <dt><code>captions</code></dt>
      <dd>The <code>captions</code> keyword specifies the resource as an alternative text for the sound and sound effects of either an <code>audio</code> element, or a <code>video</code> element</dd>
    </div>
    <div>
      <dt><code>descriptions</code></dt>
      <dd>The <code>description</code> keyword specifies the resource as an alternative text for the sound and visuals of a <code>video</code> element</dd>
    </div>
    <div>
      <dt><code>chapters</code></dt>
      <dd>The <code>chapters</code> keyword specifies the resource as a list of chapters for navigation purpose</dd>
    </div>
    <div id="attribute-kind-metadata">
      <dt><code>metadata</code></dt>
      <dd>The <code>metadata</code> keyword specifies the resource as content for scripts</dd>
    </div>
  </dl>

  The default missing value is the [`subtitles` keyword.](#attribute-kind-subtitles) And, the default invalid value is the [`metadata` keyword.](#attribute-kind-metadata)

  ```html
  <track kind="[subtitles|captions|descriptions|chapters|metadata]">
  ```
</section>



<section>
  <h2 id="attribute-label"><code>label</code> attribute</h2>

  The `label` attribute relates a user-readable title on the following elements:
  <a href="/en/html-content-forms/#element-option"><code>option</code>,</a> 
  <a href="/en/html-content-forms/#element-optgroup"><code>optgroup</code>,</a> and 
  <a href="/en/html-content-objects/#element-track"><code>track</code>.</a>

  The value must be a non-empty string.

  ```html
  <applicable-html-element label="[non-empty-text]">
  ```
</section>



<section>
  <h2 id="attribute-srcdoc"> <code>srcdoc</code> attribute</h2>

  The `srcdoc` attribute relates an html document on an [`iframe` element](/en/html-content-objects/#element-iframe)

  The value must do the following:

  - conform to the [HTML Syntax](https://html.spec.whatwg.org/#syntax)

  - escape all ampersand characters (&) and quotation mark characters (").

  ```html
  <iframe srcdoc="[escaped-html-document-content]"></iframe>
  ```
</section>



<section>
  <h2 id="attribute-sandbox"> <code>sandbox</code> attribute </h2>

  The `sandbox` attribute relates some security rules on an [`iframe` element](/en/html-content-objects/#element-iframe)

  The value must be an unordered set of space-separated [security tokens](https://html.spec.whatwg.org/#attr-iframe-sandbox).

  ```html
  <iframe sandbox="security-token security-token etc."></iframe>
  ```
</section>




<section>
  <h2 id="attribute-allowfullscreen"> <code>allowfullscreen</code> attribute</h2>

  The `allowfullscreen` boolean relates a fullscreen permission on an [`iframe` element](/en/html-content-objects/#element-iframe)

  ```html
  <iframe allowfullscreen></iframe>
  ```
</section>



<section>
  <h2 id="attribute-allow"> <code>allow</code> attribute </h2>

  The `allow` attribute relates a permission policy on an [`iframe` element](/en/html-content-objects/#element-iframe)

  The value must be a [permissions-policy](https://developer.mozilla.org/en-us/docs/web/http/headers/permissions-policy).

  ```html
  <iframe allow="[permission-policy]"></iframe>
  ```
</section>



<section>
  <h2 id="attribute-draggable"><code>draggable</code> attribute</h2>

  The `draggable` attribute relates a drag functionality on an HTML element

  The value is one of the following keywords:

  <dl>
    <div>
      <dt><code>true</code></dt>
      <dd>
        <p>The <code>true</code> keyword indicates that an element can be dragged</p>
      </dd>
    </div>
    <div>
      <dt><code>false</code></dt>
      <dd>
        <p>The <code>false</code> keyword indicates that an element cannot be dragged</p>
      </dd>
    </div>
  </dl>

  The default for both missing value and invalid value is an Auto State.

  ```html
  <html-element draggable="[true|false]">
  ```
</section>



<section>
  <h2 id="attribute-contenteditable"><code>contenteditable</code> attribute</h2>

  The `contenteditable` attribute relates an edit functionality on an HTML element

  The value is one of the following keywords:

  <dl>
    <div>
      <dt><code>true</code></dt>
      <dd>
        <p>The <code>true</code> keyword enables rich-text editing</p>
      </dd>
    </div>
    <div id="attribute-contenteditable-false">
      <dt><code>false</code></dt>
      <dd>
        <p>The <code>false</code> keyword disables the ability to edit content of an element</p>
      </dd>
    </div>
    <div>
      <dt><code>plaintext-only</code></dt>
      <dd>
        <p>The <code>plaintext-only</code> keyword enables plain-text editing</p>
      </dd>
    </div>
  </dl>

  The default for both missing value and invalid value is inherited from the parent up to the [<code>false</code> keyword](#attribute-contenteditable-false)

  ```html
  <html-element contenteditable="[false|true|plaintext-only]">
  ```
</section>


<section>
  <h2 id="attribute-for"><code>for</code> attribute</h2>

  The `for` attribute relates the following:

  - A [Content Form](/en/html-content-forms/) on a [`label` element](/en/html-content-forms/#element-label)

    The value must be the [ID](#attribute-id) of that Content Form

    ```html
    <label for="Content-Form-ID"></label>
    ```

  - A [Content Form](/en/html-content-forms/) used for a result on an [`output` element](/en/html-content-connotations/#element-output)

    The value must be a set of unique space-separated [IDs](#attribute-id) of a Content Form

    ```html
    <output for="[Content-Form-IDs]">[result]</output>
    ```
</section>



<section>
<h2 id="attribute-name"> <code>name</code> attribute </h2>

The `name` attribute relates the following:

<ul>
  <li>
    <p>A collection-unique identifier on the following elements:</p>
    <ul>
      <li id="sort-form-collection-elements">
        <p>
          Forms Collection: 
          <a href="/en/html-content-forms/#element-form"><code>form</code>,</a> 
          <a href="/en/html-content-forms/#element-fieldset"><code>fieldset</code>,</a> 
          <a href="/en/html-content-forms/#element-textarea"><code>textarea</code>,</a> 
          <a href="/en/html-content-forms/#element-select"><code>select</code>,</a> 
          <a href="/en/html-content-forms/#element-input"><code>input</code>,</a> 
          <a href="/en/html-content-forms/#element-button"><code>button</code>,</a> and
          <a href="/en/html-content-connotations/#element-output"><code>output</code></a>
        </p>
      </li>
      <li>
        <p>
          Navigables collection: 
          <a href="/en/html-content-objects/#element-iframe"><code>iframe</code></a>,
          <a href="/en/html-content-objects/#element-object"><code>object</code></a>
        </p>
      </li>
      <li>
        <p>Slots collection: <a href="/en/html-content-metas/#element-slot">slot</a></p>
      </li>
      <li>
        <p>Image maps collection: <a href="/en/html-content-objects/#element-map">map</a></p>
      </li>
      <li>
        <p>Accordions collection: <a href="/en/html-content-blocks/#element-details">details</a></p>
      </li>
    </ul>
    <p>The value must be an ID that is unique to the element's collection</p>      

    ```
    <applicable-html-element name="[ID]">
    ```
  </li>
  <li id="attribute-name-element-meta">
    <p>A Document Metadata key on a <a href="/en/html-content-metas/#element-meta"><code>meta</code> element</a></p>
    <p>
      The value must be one of the following keywords:
      <a href="/en/html-content-metas/#sort-app-name"><code>application-name</code></a>, 
      <a href="/en/html-content-metas/#sort-author"><code>author</code></a>, 
      <a href="/en/html-content-metas/#sort-description"><code>description</code></a>, 
      <a href="/en/html-content-metas/#sort-generator"><code>generator</code></a>, 
      <a href="/en/html-content-metas/#sort-keywords"><code>keywords</code></a>, 
      <a href="/en/html-content-metas/#sort-referrer"><code>referrer</code></a>, 
      <a href="/en/html-content-metas/#sort-theme-color"><code>theme-color</code></a>, and 
      <a href="/en/html-content-metas/#sort-color-scheme"><code>color-scheme</code></a>.
    </p>
    <pre><code>&lt;meta&gt; name="[keyword]"></code></pre>
  </li>
</ul>
</section>



<section>
  <h2 id="attribute-dirname"><code>dirname</code> attribute</h2>

  The `dirname` attribute relates a form-unique direction identifier on the following elements:
  <a href="/en/html-content-forms/#element-textarea"><code>textarea</code>,</a> and 
  <a href="/en/html-content-forms/#element-input"><code>input</code>.</a>

  The value must be an ID that is unique to all [elements in a form submission](#sort-form-collection-elements)

  ```html
  <applicable-html-element dirname="[ID]">
  ```
</section>  



<section>
  <h2 id="attribute-form"><code>form</code> attribute</h2>

  The `form` attribute relates a [`form` element](/en/html-content-forms/) on the following elements:
  <a href="/en/html-content-forms/#element-textarea"><code>textarea</code>,</a> 
  <a href="/en/html-content-forms/#element-select"><code>select</code>,</a> 
  <a href="/en/html-content-forms/#element-input"><code>input</code>,</a> 
  <a href="/en/html-content-forms/#element-button"><code>button</code>,</a> 
  <a href="/en/html-content-connotations/#element-output"><code>output</code>,</a> 
  <a href="/en/html-content-objects/#element-object"><code>object</code>,</a> and 
  <a href="/en/html-content-forms/#element-fieldset"><code>fieldset</code>.</a>

  The value must be the [ID](#attribute-id) of a `form` element

  ```html
  <applicable-html-element form="[form-element-ID]">
  ```
</section>




<section>
  <h2 id="attribute-accept-charset"><code>accept-charset</code> attribute</h2>

  The `accept-charset` attribute relates the character encodings for the submission of [Content Forms](/en/html-content-forms/) on a [`form` element](/en/html-content-forms/#element-form)

  The value must be "utf-8"

  ```html
  <form accept-charset="utf-8"></form>
  ```
</section>



<section>
  <h2 id="attribute-action"><code>action</code> attribute</h2>

  The `action` attribute relates a handler for the submission of [Content Forms](/en/html-content-forms/) on a [`form` element](/en/html-content-forms/#element-form)

  The value must be a valid URL address. 

  ```html
  <form action="[valid-url]"></form>
  ```
</section>



<section>
  <h2 id="attribute-formaction"><code>formaction</code> attribute</h2>

  The `formaction` attribute relates an higher precedence [`action` attribute](#attribute-enctype) but on the following elements: [`button`,](/en/html-content-forms/#element-button) and [`input`.](/en/html-content-forms/#element-input)

  ```html
  <applicable-html-element formaction="[valid-url]">
  ```
</section>



<section>
  <h2 id="attribute-enctype"><code>enctype</code> attribute</h2>

  The `enctype` attribute relates an encoding for submission of [Content Forms](/en/html-content-forms/) on a [`form` element](/en/html-content-forms/#element-form)

  The value is one of [3 `formenctype` keywords](https://html.spec.whatwg.org/#attr-fs-formenctype)

  The default missing value is nothing. And, the default invalid value is the `application/x-www-form-urlencoded` keyword

  ```html
  <form formenctype="[enctype-keyword]">[Content Forms]</form>
  ```
</section>



<section>
  <h2 id="attribute-formenctype"><code>formenctype</code> attribute</h2>

  The `formenctype` attribute relates an higher precedence [`enctype` attribute](#attribute-enctype) but on the following elements: [`button`,](/en/html-content-forms/#element-button) and [`input`.](/en/html-content-forms/#element-input)

  ```html
  <applicable-html-element formenctype="[enctype-keyword]">
  ```
</section>



<section>
  <h2 id="attribute-method"><code>method</code> attribute</h2>

  The `method` attribute relates a transfer mechanism for the submission of [Content Forms](/en/html-content-forms/) on a [`form` element](/en/html-content-forms/#element-form)

  The value is one of the following keywords:

  <dl>
    <div>
      <dt><code>get</code></dt>
      <dd>
        <p>The <code>get</code> keyword submits the Content Forms with an HTTP GET method</p>
      </dd>
    </div>
    <div>
      <dt><code>post</code></dt>
      <dd>
        <p>The <code>post</code> keyword submit the Content Forms with an HTTP POST method</p>
      </dd>
    </div>
    <div>
      <dt><code>dialog</code></dt>
      <dd>
        <p>The <code>dialog</code> keyword do not submit the Content Forms but closes the dialog box in which the <code>form</code> finds itself</p>
      </dd>
    </div>
  </dl>

  ```html
  <form method="[get|post|dialog]"></form>
  ```
</section>



<section>
  <h2 id="attribute-formmethod"><code>formmethod</code> attribute</h2>

  The `formmethod` attribute relates an higher precedence [`method` attribute](#attribute-method) but on the following elements: [`button`,](/en/html-content-forms/#element-button) and [`input`.](/en/html-content-forms/#element-input)

  ```html
  <applicable-html-element formmethod="[method-keyword]">
  ```
</section>



<section>
  <h2 id="attribute-novalidate"><code>novalidate</code> attribute</h2>

  The `novalidate` boolean attribute relates a no-validation rule for the submission of [Content Forms](/en/html-content-forms/) on a [`form` element](/en/html-content-forms/#element-form)

  ```html
  <form novalidate></form>
  ```
</section>



<section>
  <h2 id="attribute-formnovalidate"><code>formnovalidate</code> attribute</h2>

  The `formnovalidate` attribute relates an higher precedence [`novalidate` attribute](#attribute-novalidate) but on the following elements: [`button`,](/en/html-content-forms/#element-button) and [`input`.](/en/html-content-forms/#element-input)

  ```html
  <applicable-html-element formnovalidate>
  ```
</section>




<section>
  <h2 id="attribute-target"><code>target</code> attribute</h2>

  The `target` attribute relates a navigable on the following elements:
  <a href="/en/html-content-forms/#element-form"><code>form</code>,</a> 
  <a href="/en/html-content-connotations/#element-a"><code>a</code>,</a> 
  <a href="/en/html-content-objects/#element-area"><code>area</code>,</a> and 
  <a href="/en/html-content-metas/#element-base"><code>base</code></a>

  The value must be a [valid navigatable target name or keyword](https://html.spec.whatwg.org/#valid-navigable-target-name-or-keyword).

  ```html
  <applicable-html-element target="[value]">
  ```
</section>



<section>
  <h2 id="attribute-formtarget"><code>formtarget</code> attribute</h2>

  The `formtarget` attribute relates an higher precedence [`target` attribute](#attribute-target) but on the following elements: [`button`,](/en/html-content-forms/#element-button) and [`input`.](/en/html-content-forms/#element-input)

  ```html
  <applicable-html-element formtarget="[value]">
  ```
</section>



<section>
  <h2 id="attribute-autofocus"><code>autofocus</code> attribute</h2>

  The `autofocus` boolean attribute relates an automatic focus upon page load on an editable HTML element

  ```html
  <html-element autofocus>
  ```
</section>



<section>
  <h2 id="attribute-tabindex"><code>tabindex</code> attribute</h2>

  The `tabindex` attribute relates a focus and a focus order on an HTML element

  The value must be a valid integer

  <dl>
    <div>
      <dt>Negative integers</dt>
      <dd>
        <p>Numbers less than zero enables an element to be click focusable with no navigation order</p>
      </dd>
    </div>
    <div>
      <dt>0</dt>
      <dd>
        <p>The zero number enables an element to be click focusable with an implicit navigation order</p>
      </dd>
    </div>
    <div>
      <dt>Positive Integers</dt>
      <dd>
        <p>Numbers greater than zero enables an element to be click focusable with an explicit navigation order</p>
      </dd>
    </div>
  </dl>

  ```html
  <html-element tabindex="[integer]">
  ```
</section>



<section>
  <h2 id="attribute-accesskey"><code>accesskey</code> attribute</h2>

  The `accesskey` relates an identifier to help user agents create a keyboard shortcut on an HTML element

  The value must be an ordered set of unique space-separated single-length code-point strings

  ```html
  <html-element accesskey="[strings]">
  ``` 
</section>



<section>
  <h2 id="attribute-enterhintkey"><code>enterhintkey</code> attribute</h2>

  The `enterhintkey` attribute relates a label for the <kbd>enter</kbd> key in a virtual keyboard on an HTML element

  The value is one of the following keywords:

  <dl>
    <div>
      <dt><code>enter</code></dt>
      <dd>
        <p>The <code>enter</code> keyword relates an "enter" label or a familiar icon. This depicts a control that inserts a new line in a text field</p>
      </dd>
    </div>
    <div>
      <dt><code>done</code></dt>
      <dd>
        <p>The <code>done</code> keyword relates a "done" label. This depicts a control that wrap up action on the text field</p>
      </dd>
    </div>
    <div>
      <dt><code>go</code></dt>
      <dd>
        <p>The <code>go</code> keyword relates a "go" label. This depicts a control that goes to the target of the typed text</p>
      </dd>
    </div>
    <div>
      <dt><code>next</code></dt>
      <dd>
        <p>The <code>next</code> keyword relates a "next" label. This depict a control that takes a user to the next text field</p>
      </dd>
    </div>
    <div>
      <dt><code>previous</code></dt>
      <dd>
        <p>The <code>previous</code> keyword relates a "previous" label. This depicts a control that takes the user to the previous text field</p>
      </dd>
    </div>
    <div>
      <dt><code>search</code></dt>
      <dd>
        <p>The <code>search</code> keyword relates a "search" label. This depicts a control that takes the user to the search results of the typed text</p>
      </dd>
    </div>
    <div>
      <dt><code>send</code></dt>
      <dd>
        <p>The <code>send</code> keyword relates a "send" label. This depicts a control that delivers the text to its target</p>
      </dd>
    </div>
  </dl>

  The default for both missing value and invalid value is automatically determined by the user agent

  ```html
  <editable-html-element enterhintkey="[enter|done|go|next|previous|search|send]">
  ```
</section>



<section>
  <h2 id="attribute-inputmode"><code>inputmode</code> attribute</h2>

  The `inputmode` attribute relates a type of virtual keyboard to edit content on an editable HTML element

  The value is one of the following keywords:

  <dl>
    <div>
      <dt><code>none</code></dt>
      <dd>
        <p>The <code>none</code> keyword hints at no display of the browser's virtual keyboard</p>
      </dd>
    </div>
    <div>
      <dt><code>text</code></dt>
      <dd>
        <p>The <code>text</code> keyword hints at a virtual keyboard optimized to write text in user's locale</p>
      </dd>
    </div>
    <div>
      <dt><code>tel</code></dt>
      <dd>
        <p>The <code>tel</code> keyword hints at a virtual keyboard optimized to write telephone numbers in user's locale</p>
      </dd>
    </div>
    <div>
      <dt><code>url</code></dt>
      <dd>
        <p>The <code>url</code> keyword hints at a virtual keyboard optimized to write URL addresses in user's locale</p>
      </dd>
    </div>
    <div>
      <dt><code>email</code></dt>
      <dd>
        <p>The <code>email</code> keyword hints at a virtual keyboard optimized to write Email addresses in user's locale</p>
      </dd>
    </div>
    <div>
      <dt><code>numeric</code></dt>
      <dd>
        <p>The <code>numeric</code> keyword hints at a virtual keyboard optimized to write numeric inputs</p>
      </dd>
    </div>
    <div>
      <dt><code>decimal</code></dt>
      <dd>
        <p>The <code>decimal</code> keyword hints at a virtual keyboard optimized to write fractional numeric inputs</p>
      </dd>
    </div>
    <div>
      <dt><code>search</code></dt>
      <dd>
        <p>The <code>search</code> keyword hints at a virtual keyboard optimized to write search terms</p>
      </dd>
    </div>
  </dl>

  The default for both missing value and invalid value is <code>auto</code>.

  ```html
  <editable-html-element inputmode="[none|text|tel|url|email|numeric|decimal|search]">
  ```
</section>



<section>
  <h2 id="attribute-spellcheck"><code>spellcheck</code> attribute</h2>

  The `spellcheck` attribute relates a spelling and grammar audit on an editable HTML element

  The value must be one of the following keywords:

  <dl>
    <div>
      <dt><code>true</code></dt>
      <dd>
        <p>The <code>true</code> keyword indicates that spelling and grammar will be checked</p>
      </dd>
    </div>
    <div>
      <dt><code>false</code></dt>
      <dd>
        <p>The <code>false</code> keyword indicates that spelling and grammar will not be checked</p>
      </dd>
    </div>
  </dl>

  The default for both missing value and invalid value is the default state

  ```html
  <editable-html-element spellcheck="[true|false]">
  ```
</section>



<section>
  <h2 id="attribute-autocomplete"><code>autocomplete</code> attribute</h2>

  The `autocomplete` attribute relates automatic value prediction functionality on the following elements:
  <a href="/en/html-content-forms/#element-textarea"><code>textarea</code>,</a> 
  <a href="/en/html-content-forms/#element-select"><code>select</code>,</a> 
  <a href="/en/html-content-forms/#element-input"><code>input</code>,</a> 
  <a href="/en/html-content-forms/#element-form"><code>form</code>.</a>

  Note: The `autocomplete` attribute relates the meaning of the given value on an `input` element with a `type` attribute of `hidden` value

  The value is one of the following tokens:

  <dl>
    <div>
      <dt><code>off</code></dt>
      <dd>
        <p>The <code>off</code> token indicates no automatic completion on the content form.</p>
        <p>
          Note: This token is not available for an <code>input</code> element with the <code>type</code> attribute of <code>hidden</code> value.
        </p>
      </dd>
    </div>
    <div id="attribute-autocomplete-on">
      <dt><code>on</code></dt>
      <dd>
        <p>
          The <code>on</code> token indicates there will be unguided value predictions for the content form
        </p>
        <p>
          This token is not available for an <code>input</code> element with the <code>type</code> attribute of <code>hidden</code> value.
        </p>
      </dd>
    </div>
    <div>
      <dt> <a href="https://html.spec.whatwg.org/#autofill-detail-tokens"> Autofill detail token </a></dt>
      <dd>
        <p>An autofill detail token indicates the specific type of value to predict for the content form.</p>
        <p>
          This token is not available on a <code>form</code> element.
        </p>
      </dd>
    </div>
  </dl>

  The default for both missing value and invalid value is the [`on` keyword](#attribute-autocomplete-on)

  ```html
  <applicable-html-element autocomplete="[token]">
  ```
</section>




<section>
  <h2 id="attribute-list"><code>list</code> attribute</h2>

  The `list` attribute relates a [`datalist` element](/en/html-content-forms/#element-datalist) for value suggestions on an [`input` element](/en/html-content-forms/#element-input)

  The value must be an [ID](#attribute-id) of a `datalist` element

  ```html
  <input list="[datalist-id]">
  ```
</section>



<section>
  <h2 id="attribute-autocapitalize"><code>autocapitalize</code> attribute</h2>

  The `autocapitalize` attribute relates automatic capitalization of text made via input mechanisms other than a physical keyboard on an editable HTML element

  The value is one of the following keywords:

  <dl>
    <div>
      <dt><code>off</code> or <code>none</code></dt>
      <dd>
        <p>Either <code>off</code> keyword or <code>none</code> keyword hints at no automatic capitalization</p>
      </dd>
    </div>
    <div id="attribute-autocapitalize-sentences">
      <dt><code>on</code> or <code>sentences</code></dt>
      <dd>
        <p>Either <code>on</code> keyword or <code>sentences</code> keyword hints at automatic capitalization of the first character of each sentence</p>
      </dd>
    </div>
    <div>
      <dt><code>word</code></dt>
      <dd>
        <p>The <code>word</code> keyword hints at automatic capitalization of the first character of each word</p>
      </dd>
    </div>
    <div>
      <dt><code>characters</code></dt>
      <dd>
        <p>The <code>characters</code> keyword hints at the  automatic capitalization of every character</p>
      </dd>
    </div>
  </dl>

  The default missing value is the user agent's default. And, the default invalid value is the [<code>sentences</code> keyword](#attribute-autocapitalize-sentences)

  ```html
  <editable-html-element autocapitalize="[none|characters|words|sentences]">
  ```
</section>



<section>
  <h2 id="attribute-wrap"><code>wrap</code> attribute</h2>

  The `wrap` attribute relates whether new lines are included in text submission on a [`textarea` element](/en/html-content-forms/#element-textarea)

  The value is one of the following keywords:

  <dl>
    <div id="attribute-wrap-soft">
      <dt><code>soft</code></dt>
      <dd><p>The <code>soft</code> excludes newlines in the content submission.</p></dd>
    </div>
    <div>
      <dt><code>hard</code></dt>
      <dd>The <code>hard</code> keyword includes newlines in the content submission</dd>
    </div>
  </dl>

  The default for both missing value and invalid value is the [<code>soft</code> keyword](#attribute-wrap-soft)

  ```html
  <textarea wrap="[soft|wrap]"></textarea>
  ```
</section>



<section>
  <h2 id="attribute-disabled"><code>disabled</code> attribute</h2>

  The `disabled` boolean attribute relates an unusable functionality on the following elements:
  <a href="/en/html-content-forms/#element-fieldset"><code>fieldset</code>,</a> 
  <a href="/en/html-content-forms/#element-select"><code>select</code>,</a> 
  <a href="/en/html-content-forms/#element-optgroup"><code>optgroup</code>,</a> 
  <a href="/en/html-content-forms/#element-option"><code>option</code>,</a> 
  <a href="/en/html-content-forms/#element-textarea"><code>textarea</code>,</a> 
  <a href="/en/html-content-forms/#element-input"><code>input</code>,</a> 
  <a href="/en/html-content-forms/#element-button"><code>button</code>,</a> and
  <a href="/en/html-content-metas/#element-link"><code>link</code></a>

  Note: On a `fieldset` element, the unusable functionality is passed down to descendant [Content Forms](/en/html-content-forms/) but not those inside a [`legend` element](/en/html-content-forms/#element-legend)

  ```html
  <applicable-html-element disabled>
  ```
</section>



<section>
  <h2 id="attribute-readonly"><code>readonly</code> attribute</h2>

  The `readonly` boolean attribute relates an uneditable functionality on on the following elements: [`textarea`,](/en/html-content-forms/#element-textarea) and [`input`.](/en/html-content-forms/#element-input)

  ```html
  <applicable-html-element readonly>
  ```
</section>



<section>
  <h2 id="attribute-required"><code>required</code> attribute</h2>

  The `required` boolean attribute relates a compulsory functionality on the following elements: [`textarea`,](/en/html-content-forms/#element-textarea) [`select`,](/en/html-content-forms/#element-select) and [`input`.](/en/html-content-forms/#element-input)

  ```html
  <applicable-html-element required>
  ```
</section>



<section>
  <h2 id="attribute-multiple"><code>multiple</code> attribute</h2>

  The `multiple` boolean attribute relates the following functionalities:

  - Choose more than one [option](/en/html-content-forms/#element-option) items on a [`select` element](/en/html-content-forms/#element-select)

  - Enter more than one value on an [`input`.](/en/html-content-forms/#element-input)

  ```html
  <applicable-html-element multiple>
  ```
</section>



<section>
  <h2 id="attribute-checked"><code>checked</code> attribute</h2>

  The `checked` boolean attribute relates an on-state on an [`input` element](/en/html-content-forms/#element-input)

  ```html
  <input checked>
  ```
</section>



<section>
  <h2 id="attribute-selected"><code>selected</code> attribute</h2>

  The `selected` boolean attribute relates a default on an [`option` element](/en/html-content-forms/#element-option)

  ```html
  <option selected></option>
  ```
</section>



<section>
  <h2 id="attribute-maxlength"><code>maxlength</code> attribute</h2>

  The `maxlength` attribute relates the following:

  - A maximum wideness on a [`textarea` element.](/en/html-content-forms/#element-textarea)

  - The maximum wideness of an image resource on an [`input` element](/en/html-content-forms/#element-input)

  The value must be a [non-negative integer.](https://html.spec.whatwg.org/#valid-non-negative-integer) This integer is the maximum number of allowed characters

  ```html
  <applicable-html-element maxlength="[non-negative-integer]">
  ```
</section>



<section>
  <h2 id="attribute-minlength"><code>minlength</code> attribute</h2>

  The `minlength` attribute relates the following:

  - A minimumm wideness on a [`textarea` element.](/en/html-content-forms/#element-textarea)

  - The minimum wideness of an image resource on an [`input` element](/en/html-content-forms/#element-input)

  The value must be a [non-negative integer.](https://html.spec.whatwg.org/#valid-non-negative-integer) This integer is the minimum number of allowed characters

  ```html
  <applicable-html-element maxlength="[non-negative-integer]">
  ```
</section>




<section>
  <h2 id="attribute-size"><code>size</code> attribute</h2>

  The `size` attribute relates the following:

  - A wideness on an an [`input` element.](/en/html-content-forms/#element-input) 

  - Number of [option](/en/html-content-forms/#element-option) items to show on a [`select` element](/en/html-content-forms/#element-select)

  The value must be a valid [non-negative integer](https://html.spec.whatwg.org/#valid-non-negative-integer) greater than zero.

  The default value is one of the following integers:

  - 4, on a `select` element with a multiple attribute

  - 1, on a `select` element without a multiple attribute

  - 20, on an `input` element

  ```html
  <applicable-html-element size="[non-negative integer]">
  ```
</section>


<section>
  <h2 id="attribute-pattern"><code>pattern</code> attribute</h2>

  The `pattern` attribute relates an acceptable form of value on an [`input` element](/en/html-content-forms/#element-input)

  The value must be a [regular expression (regex).](https://tc39.es/ecma262/#sec-regexp-regular-expression-objects) The [`title` attribute](#attribute-title) should describe this regex.

  ```html
  <input pattern="[regex]">
  ```
</section>



<section>
  <h2 id="attribute-placeholder"><code>placeholder</code> attribute</h2>

  The `placeholder` attribute relates an example of a value on the following elements when empty: [`textarea` element](/en/html-content-forms/#element-textarea) and [`input` element](/en/html-content-forms/#element-input)

  The value must be a non-empty text

  ```html
  <applicable-html-element placeholder="[value-format]">
  ```
</section>



<section>
  <h2 id="attribute-value"><code>value</code> attribute</h2>

  The `value` attribute relates the following:

  - Starting number on an [`li` element](/en/html-content-layers/#element-li)

    The value must be a valid integer

    ```html
    <li value="[valid-integer]"></li>
    ```

  - Default content on an [`input` element](/en/html-content-forms/#element-input)

    The value must conform to the value of the `type` attribute

    ```html
    <input value="[default-content]">
    ```

  - Submission content on the following elements: [`button`,](/en/html-content-forms/#element-button) and [`option`.](/en/html-content-forms/#element-option)

    The value must be a text

    ```html
    <applicable-html-element value="[text]">
    ```

  - Progress number so far on a [`progress` element.](/en/html-content-connotations/#element-progress)

    The value must be a [valid floating-point number](https://html.spec.whatwg.org/#valid-floating-point-number) from zero to the value of the `max` attribute. Or, from zero to 1.0;

    ```html
    <progress value="[floating-point-number]"></progress>
    ```
    
  - Gauge number on a [`meter` element](/en/html-content-connotations/#element-meter)

    The value must be a [valid floating-point number.](https://html.spec.whatwg.org/#valid-floating-point-number)

    ```html
    <meter value="[floating-point-number]"></meter>
    ```

  - Machine-readable representation of content on a [`data` element](/en/html-content-connotations/#element-data)

    The value must be a representation of the element's content

    ```html
    <data value="[machine-representation]">[content]</data>
    ```
</section>




<section>
  <h2 id="attribute-min"><code>min</code> attribute</h2>

  The `min` attribute relates the lower bound of a range on the following elements: [`input`,](/en/html-content-forms/#element-input) and [`meter`.](/en/html-content-connotations/#element-meter)

  The value must be a valid floating-point number.

  ```html
  <applicable-html-element min="[floating-point-number]">
  ```
</section>



<section>
  <h2 id="attribute-step"><code>step</code> attribute</h2>

  The `step` attribute relates an increment or decrement factor on an [`input` element](/en/html-content-forms/#element-input)

  The value must be one of the following tokens:

  - An "any" string

  - a [floating-point number](https://html.spec.whatwg.org/#valid-floating-point-number) greater than zero

  ```html
  <input step="[arithmetic-factor]">
  ```
</section>



<section>
  <h2 id="attribute-max"><code>max</code> attribute</h2>

  The `max` attribute relates the upper bound of a range on the following elements:
  <a href="/en/html-content-forms/#element-input"><code>input</code>,</a> 
  <a href="/en/html-content-connotations/#element-progress"><code>progress</code>,</a> and 
  <a href="/en/html-content-connotations/#element-meter"><code>meter</code>.</a>

  The value must be a valid [floating-point number](https://html.spec.whatwg.org/#valid-floating-point-number)

  ```html
  <applicable-html-element max="[floating-point-number]">
  ```
</section>



<section>
  <h2 id="attribute-low"><code>low</code> attribute</h2>

  The `low` attribute relates the lower part of a bounded range on a [`meter` element](/en/html-content-connotations/#element-meter)

  The value must be a valid [floating-point number.](https://html.spec.whatwg.org/#valid-floating-point-number) This number down to the value of the [`min` attribute](#attribute-min) relates the lower part.

  ```html
  <meter low="[floating-point-number]">[range content]</meter>
  ```
</section>




<section>
  <h2 id="attribute-high"><code>high</code> attribute</h2>

  The `high` attribute relates the higher part of a bounded range on a [`meter` element](/en/html-content-connotations/#element-meter)

  The value must be a valid [floating-point number.](https://html.spec.whatwg.org/#valid-floating-point-number) This number up to the value of the [`max` attribute](#attribute-max) relates the lower part.

  ```html
  <meter high="[floating-point-number]">[range content]</meter>
  ```
</section>



<section>
  <h2 id="attribute-optimum"><code>optimum</code> attribute</h2>

  The `optimum` attribute relates the preferable part of a bounded range on a [`meter` element](/en/html-content-connotations/#element-meter)

  The value must be a valid [floating-point number.](https://html.spec.whatwg.org/#valid-floating-point-number) This number within a [lower part,](#attribute-low) [high part,](#attribute-high) or in-between relates that part as the better part.

  ```html
  <meter optimum="[floating-point-number]">[range content]</meter>
  ```
</section>





<section>
  <h2 id="attribute-accept"><code>accept</code> attribute</h2>

  The `accept` attribute relates a sort of resource for upload on an [`input` element](/en/html-content-forms/#element-input)

  The value must be a set of comma-separated tokens. Each token must be one of the following keywords:

  <dl>
    <div>
      <dt><code>audio/*</code></dt>
      <dd>The <code>audio/*</code> string hints at uploading a sound file only</dd>
    </div>
    <div>
      <dt><code>video/*</code></dt>
      <dd>The <code>video/*</code> string hints at uploading a video file only</dd>
    </div>
    <div>
      <dt><code>image/*</code></dt>
      <dd>The <code>image/*</code> string hints at uploading an image file only</dd>
    </div>
    <div>
      <dt>A valid MIME type string with no parameters</dt>
      <dd>This hints at uploading files of the specified MIME type only</dd>
    </div>
    <div>
      <dt>A file extension</dt>
      <dd>A string starting with a full-stop character hints at uploading the specified file extension only</dd>
    </div>
  </dl>

  ```html
  <input accept="[comma-separated-tokens]">
  ```
</section>



<section>
  <h2 id="attribute-start"><code>start</code> attribute</h2>

  The `start` attribute relates the starting number of a list on an [`ol` element](/en/html-content-layers/#element-ol)

  The value must be a valid integer

  ```html
  <ol start="[integer]"></ol>
  ```
</section>




<section>
  <h2 id="attribute-reversed"><code>reversed</code> attribute</h2>

  The `reversed` boolean attribute relates a descending order of list items on an [`ol` element](/en/html-content-layers/#element-ol)

  ```html
  <ol reversed></ol>
  ```
</section>



<section>
  <h2 id="attribute-abbr"><code>abbr</code> attribute</h2>

  The `abbr` attribute relates an alternative title on a [`th` element](/en/html-content-layers/#element-th) 

  The value must be a non-empty text

  ```html
  <th abbr="[non-empty-text]">[table header cell content]</th>
  ```
</section>



<section>
  <h2 id="attribute-scope"><code>scope</code> attribute</h2>

  The `scope` attribute relates a set of table cells on a [`th` element](/en/html-content-layers/#element-th)

  The value is one of the following keywords:

  <dl>
    <div>
      <dt><code>row</code></dt>
      <dd>
        <p>The <code>row</code> keyword signifies that the header cell applies to some of the subsequent cells in the same row(s)</p>
      </dd>
    </div>
    <div>
      <dt><code>col</code></dt>
      <dd>
        <p>The <code>col</code> keyword signifies that the header cell applies to some of the subsequent cells in the same column(s)</p>
      </dd>
    </div>
    <div>
      <dt><code>rowgroup</code></dt>
      <dd>
        <p>The <code>rowgroup</code> keyword signifies that the header cell applies to all the remaining cells in the row group</p>
      </dd>
    </div>
    <div>
      <dt><code>colgroup</code></dt>
      <dd>
        <p>The <code>colgroup</code> keyword signifies that the header cell applies to all the remaining cells in the column group</p>
      </dd>
    </div>
    <div id="attribute-scope-auto">
      <dt><code>auto</code></dt>
      <dd>
        <p>The <code>auto</code> keyword signifies that the header cell applies to a set of cells selected based on context</p>
      </dd>
    </div>
  </dl>

  The default for both missing value and invalid value is the [`auto` keyword](#attribute-scope-auto)

  ```html
  <th scope="[auto|row|col|rowgroup|colgroup]">[table header cell content]</th>
  ```
</section>




<section>
  <h2 id="attribute-headers"><code>headers</code> attribute</h2>

  The `headers` attribute relates some [`th` elements](/en/html-content-layers/#element-th) on the following elements: [`td`,](/en/html-content-layers/#element-td) and [`th`.](/en/html-content-layers/#element-th)

  The value must be an unordered set of space-separated [IDs](#attribute-id) of `th` elements. However, a `th` element must not relates itself.

  ```html
  <applicable-html-element headers="[ID ID etc.]">
  ```
</section>




<section>
  <h2 id="attribute-cols"><code>cols</code> attribute</h2>

  The `cols` attribute relates a wideness on a [`textarea` element](/en/html-content-forms/#element-textarea)

  The value must be a valid [non-negative integer](https://html.spec.whatwg.org/#valid-non-negative-integer) greater than zero. This integer is the number of characters allowed per line when the scrollbar is visible in the element's viewport. 

  The default value is 20.

  ```html
  <textarea cols="[non-negative-integer]"></textarea>
  ```
</section>



<section>
  <h2 id="attribute-span"><code>span</code> attribute</h2>

  The `span` attribute relates a wideness on the following elements: [`colgroup`,](/en/html-content-layers/#element-colgroup) and [`col`.](/en/html-content-layers/#element-col)

  The value must be a valid [non-negative integer](https://html.spec.whatwg.org/#valid-non-negative-integer) both greater than zero and less than or equal to 1000. This integer is the number of columns to cover in a [`table` element](/en/html-content-layers/#element-table)

  ```html
  <applicable-html-element colspan="[1 <= integer <= 1000]">
  ```
</section>



<section>
  <h2 id="attribute-colspan"><code>colspan</code> attribute</h2>

  The `colspan` attribute relates a wideness on the following elements: [`th`,](/en/html-content-layers/#element-th) and [`td`.](/en/html-content-layers/#element-td)

  The value must be a valid [non-negative integer](https://html.spec.whatwg.org/#valid-non-negative-integer) both greater than zero and less than or equal to 1000. This integer is the number of columns to span in a [`table` element](/en/html-content-layers/#element-table)

  ```html
  <applicable-html-element colspan="[1 <= integer <= 1000]">
  ```
</section>



<section>
  <h2 id="attribute-rows"><code>rows</code> attribute</h2>

  The `rows` attribute relates a highness on a [`textarea` element](/en/html-content-forms/#element-textarea)

  The value must be a [valid non-negative integer](https://html.spec.whatwg.org/#valid-non-negative-integer) greater than zero. This integer is the number of lines to show. 

  The default value is 2.

  ```html
  <textarea rows="[non-negative-integer]"></textarea>
  ```
</section>




<section>
  <h2 id="attribute-rowspan"><code>rowspan</code> attribute</h2>

  The `rowspan` attribute relates a highness on the following elements: [`th`,](/en/html-content-layers/#element-th) and [`td`.](/en/html-content-layers/#element-td)

  The value must be a [valid non-negative integer](https://html.spec.whatwg.org/#valid-non-negative-integer) less than or equal to 65534. This integer is the number of rows to span in a [`table` element.](/en/html-content-layers/#element-table) A value of Zero spans the remaining rows.

  ```html
  <applicable-html-element rowspan="[0 <= integer <= 65534]">
  ```

</section>



<section>
  <h2 id="attribute-open"><code>open</code> attribute</h2>

  The `open` boolean attribute relates a revelation of content on  the following elements: 
  [`details`,](/en/html-content-blocks/#element-details) and 
  [`dialog`.](/en/html-content-windows/#element-dialog)

  ```html
  <applicable-html-element open>
  ```
</section>



<section>
  <h2 id="attribute-href"><code>href</code> attribute</h2>

  The `href` attribute relates a resource address on the following elements: 
  <a href="/en/html-content-connotations/#element-a"><code>a</code>,</a>  
  <a href="/en/html-content-objects/#element-area"><code>area</code>,</a>
  <a href="/en/html-content-metas/#element-base"><code>base</code>,</a> and
  <a href="/en/html-content-metas/#element-link"><code>link</code>.</a> 

  The value must be a valid URL address.

  ```html
  <applicable-html-element href="[valid-URL-address]">
  ```
</section>



<section>
  <h2 id="attribute-download"><code>download</code> attribute</h2>

  The `download` boolean attribute relates a download functionality on the following elements: [`a`,](/en/html-content-connotations/#element-a) and [`area`](/en/html-content-objects/#element-area)

  ```html
  <applicable-html-element download>
  ```
</section>



<section>
  <h2 id="attribute-ping"><code>ping</code> attribute</h2>

  The `ping` attribute relates a set of addresses for hyperlink auditors on the following elements: [`a`,](/en/html-content-connotations/#element-a) and [`area`](/en/html-content-objects/#element-area)

  The value must be a set of space-separated secured URL addresses.

  ```html
  <applicable-html-element ping="[https-url https-url etc.]">
  ```
</section>



<section>
  <h2 id="attribute-cite"><code>cite</code> attribute</h2>

  The `cite` attribute relates the following:

  - An address of a Changelog resource on the following elements: [`del`,](/en/html-content-connotations/#element-del) and [`ins`.](/en/html-content-connotations/#element-ins)

  - An address of a Quote Source on the following elements: [`blockquote`,](/en/html-content-connotations/#element-blockquote) and [`q`.](/en/html-content-connotations/#element-q)

  The value must be a valid URL address

  ```html
  <applicable-html-element cite="[valid-url-address]">
  ```
</section>




<section>
  <h2 id="attribute-datetime"><code>datetime</code> attribute</h2>

  The `datetime` attribute relates the following:

  - Machine-readable representation on a [`time` element](/en/html-content-connotations/#element-time)

  - Time of document changes on the following elements: [`ins`,](/en/html-content-connotations/#element-ins) and [`del`.](/en/html-content-connotations/#element-del)

  The value must be a [valid datetime representation](https://html.spec.whatwg.org/#the-time-element:datetime-value). 

  Note: The time part of the value is optional for the following elements: `ins` or on a `del` element

  ```html
  <applicable-html-element datetime="[valid-datetime]">
  ```

</section>




<section>
  <h2 id="attribute-inert"><code>inert</code> attribute</h2>

  The `inert` boolean attribute relates a non-active functionality on an HTML element

  ```html
  <html-element inert>
  ```
</section>



<section>
  <h2 id="attribute-hidden"><code>hidden</code> attribute</h2>

  The `hidden` attribute relates a no-render state on an HTML element. On a `main` element, it means a <b>potential</b> [Main Card](/en/html-content-cards/#card-main).

  The value is one of the following keywords:

  <dl>
    <div>
      <dt><code>until-found</code></dt>
      <dd>
        <p>The <code>until-found</code> keyword maintains a no-rendering state until a user searches or jumps to a part of the content. </p>
      </dd>
    </div>

    <div id="attribute-hidden-hidden">
      <dt><code>hidden</code> or The empty string</dt>
      <dd>
        <p>The <code>hidden</code> keyword or an empty string keyword maintains a no-rendering state until the attribute is removed</p>
      </dd>
    </div>
  </dl>

  The default missing value is a visible state. And, the default for an invalid state is the [`hidden` keyword](#attribute-hidden-hidden)

  ```html
  <html-element hidden="[hidden|until-found]">
  ```
</section>




<section>
  <h2 id="attribute-itemscope"><code>itemscope</code> attribute</h2>

  The `itemscope` boolean attribute relates a microdata item tag on an HTML element

  ```html
  <html-element itemscope>
  ```
</section>



<section>
  <h2 id="attribute-itemtype"><code>itemtype</code> attribute</h2>

  The `itemtype` attribute relates a microdata vocabulary on an HTML element with an [`itemscope` attribute](#attribute-itemscope)

  The value must be an unordered set of unique space-separated absolute URL. 

  ```html
  <html-element itemscrope itemtype="[valid-absoluteURL valid-absoluteURL etc]">
  ```
</section>



<section>
  <h2 id="attribute-itemid"><code>itemid</code> attribute</h2>

  The `itemid` attribute relates the global identifier of an [`itemtype` attribute](#attribute-itemtype) on an [itemscoped attribute](#attribute-itemscope)

  The value must be a valid URL

  ```html
  <html-element itemscope itemtype="[valid-absoluteURL]" itemid="[valid-URL]" >
  ```
</section>




<section>
  <h2 id="attribute-itemprop"><code>itemprop</code> attribute</h2>

  The `itemprop` attribute relates a microdata property name on an HTML element

  The value must be an ordered set of one or more unique space-separated tokens. Each token must be a one-length code point and of the following type:

  <ul>
    <li>
      <p>Either of the following if the item is a typed item</p>
      <ul>
        <li>
          <p>A public-defined name for a property</p>
        </li>
        <li>
          <p>Either a proprietary-defined or public-defined absolute URL for a property</p>
        </li>
      </ul>
    </li>
    <li>
      <p>A proprietary-defined string for a property name if the item is not a typed item. <br> The string must neither contain a full-stop character nor a colon character</p>
    </li>
  </ul>

  ```html
  <html-element itemprop="[name]">[value]</html-element>
  ```

  Notes on specifying the `itemprop` attribute: 

  - It requires the [`href` attribute](#attribute-href) on the following elements: 
  [`a`,](/en/html-content-connotations/#element-a), and 
  [`area`.](/en/html-content-connotations/#element-area)

  - It disallows the [`rel` attribute](#attribute-rel) on a [`link` element](/en/html-content-metas/#element-link)

  - It disallows the following attributes on a `meta` element: `name`, `charset`, and `http-equiv`.

  - It requires a [`src` attribute](#attribute-src) on the following elements: 
  [`audio`,](/en/html-content-objects/#element-audio) 
  [`embed`,](/en/html-content-objects/#element-embed)  
  [`iframe`,](/en/html-content-objects/#element-iframe) and 
  [`video`](/en/html-content-objects/#element-video)
</section>




<section>
  <h2 id="attribute-itemref"><code>itemref</code> attribute</h2>

  The `itemref` attribute relates a set of additional [microdata properties](#attribute-itemprop) on an [itemscoped element](#attribute-itemscope)

  The value must be an unordered set of unique space-separated element [IDs](#attribute-id) of Microdata Properties

  ```html
  <html-element itemscope itemref="[ID ID etc]">
  ```
</section>




<section>
  <h2 id="attribute-popover"><code>popover</code> attribute</h2>

  The `popover` attribute relates a popover functionality on an HTML element

  The value is one of the following keywords that specifies the closing mechanisms:

  <dl>
    <div>
      <dt><code>auto</code> or empty string</dt>
      <dd>
        <p>The <code>auto</code> keyword or the empty string("") relates the following closing mechanisms:</p>
        <ul>
          <li>
            <p>allow closing of other opened popovers</p>
          </li>
          <li>
            <p>allow closing of the popover via either an <a href="ttps://html.spec.whatwg.org/#close-requests">indirect request</a> or clicking outside the popover</p>
          </li>
        </ul>
      </dd>
    </div>
    <div id="attribute-popover-manual">
      <dt><code>manual</code></dt>
      <dd>
        <ul>
          <li>
            <p>disallow closing of other opened popovers</p>
          </li>
          <li>
            <p>disallow closing of the popover via either an <a href="ttps://html.spec.whatwg.org/#close-requests">indirect request</a> or clicking outside the popover</p>
          </li>
        </ul>
      </dd>
    </div>
  </dl>

  The default missing value is the no popover state. While the default for the invalid value is the [<code>manual</code> keyword](#attribute-popover-manual)

  ```html
  <html-element popover="[auto|manual]">
  ```
</section>




<section>
  <h2 id="attribute-popovertarget"><code>popovertarget</code> attribute</h2>

  The `popovertarget` attribute relates a [popover](#attribute-popover) on the following elements: [`button`,](/en/html-content-forms/#element-button) and [`input`](/en/html-content-forms/#element-input)

  The value must be the [ID](#attribute-id) of an element with a [popover attribute](#attribute-popover)

  ```html
  <applicable-html-element popovertarget="[ID]">
  ```
</section>



<section>
  <h2 id="attribute-popovertargetaction"><code>popovertargetaction</code> attribute</h2>

  The `popovertargetaction` attribute relates the visibility status of a [popover](#attribute-popover) on the following elements: [`button`,](/en/html-content-forms/#element-button) and [input.](/en/html-content-forms/#element-input)

  The value is one of the following keywords:

  <dl>
    <div>
      <dt><code>show</code></dt>
      <dd>
        <p>The <code>show</code> keyword shows the targeted popover content</p>
      </dd>
    </div>
    <div>
      <dt><code>hide</code></dt>
      <dd>
        <p>The <code>hide</code> keyword hides the targeted popover content</p>
      </dd>
    </div>
    <div>
      <dt id="attribute-popovertargetaction-toggle"><code>toggle</code></dt>
      <dd>
        <p>The <code>toggle</code> keyword switches between showing and hiding the targeted popover content </p>
      </dd>
    </div>
  </dl>

  The default missing value and invalid value is the [`toggle` keyword](#attribute-popovertargetaction-toggle)

  ```html
  <applicable-html-element popovertargetaction="[toggle|show|hide]">
  ```
</section>


