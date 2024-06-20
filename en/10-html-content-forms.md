---
title: The 24 Content Forms of HTML
canonical: https://www.toheeb.com/en/html-content-forms/
book-hc: 10
---

<header>

  <h1 id="content-form">The 24 Content Forms of HTML</h1>

  A Content Form accepts textual and non-textual data within a [Content Block](/en/html-content-blocks/)

  <nav class="list-to-grid">
  <h2>Outline</h2>

  The 24 Content Forms are as follows:

  - [Select Form](#form-select)

  - [Textarea Form](#form-textarea)

  - [Sensitive Form](#form-sensitive)

  - [Search Form](#form-search)

  - [Color Form](#form-color)

  - [URL Form](#form-url)

  - [Email Form](#form-email)

  - [File Form](#form-file)

  - [Telephone Form](#form-telephone)

  - [Range Form](#form-range)

  - [Number Form](#form-number)

  - [Datetime Form](#form-datetime)

  - [Date Form](#form-date)

  - [Month Form](#form-month)

  - [Week Form](#form-week)

  - [Time Form](#form-time)

  - [Text Form](#form-text)

  - [Hidden Form](#form-hidden)

  - [Checkbox Form](#form-checkbox)

  - [Radio Form](#form-radio)

  - [Reset Button Form](#form-button-reset)

  - [Submit Button Form](#form-button-submit)

  - [Image Button Form](#form-button-image) 

  - [Custom Button Form](#form-button-custom)


  Content Forms leverage the following helpers:
  <span class="i-grid-wrapper">
    <span><a href="/en/html-content-blocks/#title-fieldset">Fieldset Title,</a> </span>
    <span><a href="/en/html-content-connotations/#connotation-label">Label Connotation,</a> </span>
    <span><a href="/en/html-content-mixes/#card-search">Search Card,</a> and </span>
    <span><a href="/en/html-content-mixes/#card-form">Form Card.</a> </span>
  </span>
  </nav>
</header>




<section>
  <h2 id="form-select">Select Form</h2>

  A Select Form accepts text from multiple [option items](#item-option)

  The syntax is a [`select` element](https://html.spec.whatwg.org/#the-select-element) with the following contents:

  - Zero or one count for each of the following attributes: 

    - [`autocomplete`](/en/html-content-attributes/#attribute-autocomplete) 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form)

    - [`multiple`](/en/html-content-attributes/#attribute-multiple) 

    - [`name`](/en/html-content-attributes/#attribute-name) 

    - [`required`](/en/html-content-attributes/#attribute-required) 

    - [`size`](/en/html-content-attributes/#attribute-size)


  - Zero or one count for each <a href="https://html.spec.whatwg.org/#global-attributes">global attribute</a>

  - One first-child `option` element as a placeholder label if the `select` element has the followings:

    - `value` attribute with empty string value

    - `size` attribute with one as value

    - `required` boolean attribute

  - Zero or more counts for each of the following elements: 

    - [`hr`](/en/html-content-breaks/#break-option), 

    - [`optgroup`](#group-option), and 

    - [`option`](#item-option)


  ```html
  <select></select>
  ```
</section>



<section>
  <h2 id="form-textarea">Textarea Form</h2>

  A Textarea Form accepts multi-line text

  The syntax is a [`textarea` element](https://html.spec.whatwg.org/#the-textarea-element) with the following contents:

  - Zero or one count for each of the following attributes: 

    - [`autocomplete`](/en/html-content-attributes/#attribute-autocomplete)

    - [`cols`](/en/html-content-attributes/#attribute-cols)

    - [`dirname`](/en/html-content-attributes/#attribute-dirname)

    - [`disabled`](/en/html-content-attributes/#attribute-disabled)

    - [`form`](/en/html-content-attributes/#attribute-form)

    - [`maxlength`](/en/html-content-attributes/#attribute-maxlength)

    - [`minlength`](/en/html-content-attributes/#attribute-minlength)

    - [`name`](/en/html-content-attributes/#attribute-name)

    - [`placeholder`](/en/html-content-attributes/#attribute-placeholder)

    - [`readonly`](/en/html-content-attributes/#attribute-readonly)

    - [`required`](/en/html-content-attributes/#attribute-required)

    - [`rows`](/en/html-content-attributes/#attribute-rows)

    - [`wrap`](/en/html-content-attributes/#attribute-wrap)


  - Zero or one count for each <a href="https://html.spec.whatwg.org/#global-attributes">Global Attribute</a>

  - A Text Content as the default value

  ```html
  <textarea></textarea>
  ```
</section>



<section>
  <h2 id="form-sensitive">Sensitive Form</h2>

  A Sensitive Form accepts text via an obscured medium.

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#password-state-(type=password)) with the following attributes:

  - One `type` attribute with the `password` value

  - Zero or one count for each of the following attributes:

    - [`autocomplete`](/en/html-content-attributes/#attribute-autocomplete) 

    - [`dirname`](/en/html-content-attributes/#attribute-dirname) 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form) 

    - [`maxlength`](/en/html-content-attributes/#attribute-maxlength) 

    - [`minlength`](/en/html-content-attributes/#attribute-minlength) 

    - [`name`](/en/html-content-attributes/#attribute-name) 

    - [`pattern`](/en/html-content-attributes/#attribute-pattern) 

    - [`placeholder`](/en/html-content-attributes/#attribute-placeholder) 

    - [`readonly`](/en/html-content-attributes/#attribute-readonly) 

    - [`required`](/en/html-content-attributes/#attribute-required) 

    - [`size`](/en/html-content-attributes/#attribute-size) 

    - [`value`](/en/html-content-attributes/#attribute-value)  

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="password">
  ```
</section>



<section>
  <h2 id="form-search">Search Form</h2>

  A Search Form accept search terms

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#text-(type=text)-state-and-search-state-(type=search)) with the following attributes:

  - One `type` attribute with the `search` value

  - Zero or one count for each of the following attributes: 

    - [`autocomplete`](/en/html-content-attributes/#attribute-autocomplete) 

    - [`dirname`](/en/html-content-attributes/#attribute-dirname) 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form) 

    - [`list`](/en/html-content-attributes/#attribute-list) 

    - [`maxlength`](/en/html-content-attributes/#attribute-maxlength) 

    - [`minlength`](/en/html-content-attributes/#attribute-minlength) 

    - [`name`](/en/html-content-attributes/#attribute-name) 

    - [`pattern`](/en/html-content-attributes/#attribute-pattern) 

    - [`placeholder`](/en/html-content-attributes/#attribute-placeholder) 

    - [`readonly`](/en/html-content-attributes/#attribute-readonly) 

    - [`required`](/en/html-content-attributes/#attribute-required) 

    - [`size`](/en/html-content-attributes/#attribute-size)

    - [`value`](/en/html-content-attributes/#attribute-value)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="search">
  ```
</section>


<section>
  <h2 id="form-color">Color Form</h2>

  A Color Form accepts a [hex color](https://html.spec.whatwg.org/#valid-lowercase-simple-colour) via a picker

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#color-state-(type=color)) with the following attributes:

  - One `type` attribute with the `color` value

  - Zero or one count for each of the following attributes:   

    - [`autocomplete`](/en/html-content-attributes/#attribute-autocomplete) 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form) 

    - [`list`](/en/html-content-attributes/#attribute-list) 

    - [`name`](/en/html-content-attributes/#attribute-name)

    - [`value`](/en/html-content-attributes/#attribute-value) 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="color">
  ```
</section>



<section>
  <h2 id="form-url">URL Form</h2>

  A URL Form accepts an absolute URL address

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#url-state-(type=url)) with the following attributes:

  - One `type` attribute with the `url` value

  - Zero or one count for each of the following attributes: 

    - [`autocomplete`](/en/html-content-attributes/#attribute-autocomplete) 

    - [`dirname`](/en/html-content-attributes/#attribute-dirname) 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form) 

    - [`list`](/en/html-content-attributes/#attribute-list) 

    - [`maxlength`](/en/html-content-attributes/#attribute-maxlength) 

    - [`minlength`](/en/html-content-attributes/#attribute-minlength) 

    - [`name`](/en/html-content-attributes/#attribute-name) 

    - [`pattern`](/en/html-content-attributes/#attribute-pattern) 

    - [`placeholder`](/en/html-content-attributes/#attribute-placeholder) 

    - [`readonly`](/en/html-content-attributes/#attribute-readonly) 

    - [`required`](/en/html-content-attributes/#attribute-required) 

    - [`size`](/en/html-content-attributes/#attribute-size)

    - [`value`](/en/html-content-attributes/#attribute-value) 


  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="url">
  ```
</section>



<section>
  <h2 id="form-email">Email Form</h2>

  An Email Form accepts an Email Address

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#email-state-(type=email)) with the following attributes:

  - One `type` attribute with the `email` value

  - Zero or one count for each of the following attributes:

    - [`autocomplete`](/en/html-content-attributes/#attribute-autocomplete) 

    - [`dirname`](/en/html-content-attributes/#attribute-dirname) 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form) 

    - [`list`](/en/html-content-attributes/#attribute-list) 

    - [`maxlength`](/en/html-content-attributes/#attribute-maxlength) 

    - [`minlength`](/en/html-content-attributes/#attribute-minlength) 

    - [`multiple`](/en/html-content-attributes/#attribute-multiple) 

    - [`name`](/en/html-content-attributes/#attribute-name) 

    - [`pattern`](/en/html-content-attributes/#attribute-pattern) 

    - [`placeholder`](/en/html-content-attributes/#attribute-placeholder) 

    - [`readonly`](/en/html-content-attributes/#attribute-readonly) 

    - [`required`](/en/html-content-attributes/#attribute-required) 

    - [`size`](/en/html-content-attributes/#attribute-size)

    - [`value`](/en/html-content-attributes/#attribute-value) 


  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="email">
  ```
</section>




<section>
  <h2 id="form-file">File Form</h2>

  A File Form accepts non-textual information via an upload button

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#file-upload-state-(type=file)) with the following attributes:

  - One `type` attribute with the `file` value

  - Zero or one count for each of the following attributes: 

    - [`accept`](/en/html-content-attributes/#attribute-accept) 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form) 

    - [`multiple`](/en/html-content-attributes/#attribute-multiple) 

    - [`name`](/en/html-content-attributes/#attribute-name) 

    - [`required`](/en/html-content-attributes/#attribute-required) 

    - [`value`](/en/html-content-attributes/#attribute-value) 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="file">
  ```
</section>




<section>
  <h2 id="form-telephone">Telephone Form</h2>

  A Telephone Form accepts a telephone number

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#telephone-state-(type=tel)) with the following attributes:

  - One `type` attribute with the `tel` value

  - Zero or one count for each of the following attributes: 

    - [`autocomplete`](/en/html-content-attributes/#attribute-autocomplete) 

    - [`dirname`](/en/html-content-attributes/#attribute-dirname) 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form) 

    - [`list`](/en/html-content-attributes/#attribute-list) 

    - [`maxlength`](/en/html-content-attributes/#attribute-maxlength) 

    - [`minlength`](/en/html-content-attributes/#attribute-minlength) 

    - [`name`](/en/html-content-attributes/#attribute-name) 

    - [`pattern`](/en/html-content-attributes/#attribute-pattern) 

    - [`placeholder`](/en/html-content-attributes/#attribute-placeholder) 

    - [`readonly`](/en/html-content-attributes/#attribute-readonly) 

    - [`required`](/en/html-content-attributes/#attribute-required) 

    - [`size`](/en/html-content-attributes/#attribute-size)

    - [`value`](/en/html-content-attributes/#attribute-value)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="tel">
  ```
</section>




<section>
  <h2 id="form-range">Range Form</h2>

  A Range Form accepts a [number](https://html.spec.whatwg.org/#valid-floating-point-number) within a range

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#range-state-(type=range)) with the following attributes:

  - One `type` attribute with the `range` value

  - Zero or one count for each of the following attributes: 

    - [`autocomplete`](/en/html-content-attributes/#attribute-autocomplete) 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form) 

    - [`list`](/en/html-content-attributes/#attribute-list) 

    - [`max`](/en/html-content-attributes/#attribute-max) 

    - [`min`](/en/html-content-attributes/#attribute-min) 

    - [`name`](/en/html-content-attributes/#attribute-name) 

    - [`step`](/en/html-content-attributes/#attribute-step) 

    - [`value`](/en/html-content-attributes/#attribute-value) 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="range">
  ```
</section>



<section>
  <h2 id="form-number">Number Form</h2>

  A Number Form accepts a [number](https://html.spec.whatwg.org/#valid-floating-point-number) value

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#number-state-(type=number)) with the following attributes:

  - One `type` attribute with the `number` value

  - Zero or one count for each of the following attributes: 

    - [`autocomplete`](/en/html-content-attributes/#attribute-autocomplete) 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form) 

    - [`list`](/en/html-content-attributes/#attribute-list) 

    - [`max`](/en/html-content-attributes/#attribute-max) 

    - [`min`](/en/html-content-attributes/#attribute-min) 

    - [`name`](/en/html-content-attributes/#attribute-name) 

    - [`readonly`](/en/html-content-attributes/#attribute-readonly) 

    - [`required`](/en/html-content-attributes/#attribute-required) 

    - [`step`](/en/html-content-attributes/#attribute-step) 

    - [`value`](/en/html-content-attributes/#attribute-value) 


  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="number">
  ```
</section>




<section>
  <h2 id="form-datetime">Datetime Form</h2>

  A Datetime Form accept year, month, day, hour, minute, second, and millisecond values via a picker

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#local-date-and-time-state-(type=datetime-local)) with the following attributes:

  - One `type` attribute with the `datetime-local` value

  - Zero or one count for each of the following attributes:
  [`autocomplete`](/en/html-content-attributes/#attribute-autocomplete) 
  [`disabled`](/en/html-content-attributes/#attribute-disabled) 
  [`form`](/en/html-content-attributes/#attribute-form) 
  [`list`](/en/html-content-attributes/#attribute-list) 
  [`max`](/en/html-content-attributes/#attribute-max) 
  [`min`](/en/html-content-attributes/#attribute-min) 
  [`name`](/en/html-content-attributes/#attribute-name) 
  [`readonly`](/en/html-content-attributes/#attribute-readonly) 
  [`required`](/en/html-content-attributes/#attribute-required) 
  [`step`](/en/html-content-attributes/#attribute-step) 
  [`value`](/en/html-content-attributes/#attribute-value) 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="datetime-local">
  ```
</section>




<section>
  <h2 id="form-date">Date Form</h2>

  A Date Form accept year, month, and day values via a picker

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#date-state-(type=date)) with the following attributes:

  - One `type` attribute with the `date` value

  - Zero or one count for each of the following attributes: 
  [`autocomplete`](/en/html-content-attributes/#attribute-autocomplete) 
  [`disabled`](/en/html-content-attributes/#attribute-disabled) 
  [`form`](/en/html-content-attributes/#attribute-form) 
  [`list`](/en/html-content-attributes/#attribute-list) 
  [`max`](/en/html-content-attributes/#attribute-max) 
  [`min`](/en/html-content-attributes/#attribute-min) 
  [`name`](/en/html-content-attributes/#attribute-name) 
  [`readonly`](/en/html-content-attributes/#attribute-readonly) 
  [`required`](/en/html-content-attributes/#attribute-required) 
  [`step`](/en/html-content-attributes/#attribute-step) 
  [`value`](/en/html-content-attributes/#attribute-value) 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="date">
  ```
</section>



<section>
  <h2 id="form-month">Month Form</h2>

  A Month Form accept year and month values via a picker

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#month-state-(type=month)) with the following attributes:

  - One `type` attribute with the `month` value

  - Zero or one count for each of the following attributes: 

    - [`list`](/en/html-content-attributes/#attribute-list)
    
    - [`min`](/en/html-content-attributes/#attribute-min)
    
    - [`max`](/en/html-content-attributes/#attribute-max)
    
    - [`step`](/en/html-content-attributes/#attribute-step)
    
    - [`disabled`](/en/html-content-attributes/#attribute-disabled)
    
    - [`readonly`](/en/html-content-attributes/#attribute-readonly)
    
    - [`required`](/en/html-content-attributes/#attribute-required)
    
    - [`autocomplete`](/en/html-content-attributes/#attribute-autocomplete)
    
    - [`value`](/en/html-content-attributes/#attribute-value)
    
    - [`name`](/en/html-content-attributes/#attribute-name)
    
    - [`form`](/en/html-content-attributes/#attribute-form)  

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="month">
  ```
</section>



<section>
  <h2 id="form-week">Week Form</h2>

  A Week Form accept week and year values via a picker

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#week-state-(type=week)) with the following attributes:

  - One `type` attribute with the `week` value

  - Zero or one count for each of the following attributes:   

    - [`autocomplete`](/en/html-content-attributes/#attribute-autocomplete) 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form) 

    - [`list`](/en/html-content-attributes/#attribute-list) 

    - [`max`](/en/html-content-attributes/#attribute-max) 

    - [`min`](/en/html-content-attributes/#attribute-min) 

    - [`name`](/en/html-content-attributes/#attribute-name) 

    - [`readonly`](/en/html-content-attributes/#attribute-readonly) 

    - [`required`](/en/html-content-attributes/#attribute-required) 

    - [`step`](/en/html-content-attributes/#attribute-step) 

    - [`value`](/en/html-content-attributes/#attribute-value) 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="week">
  ```
</section>



<section>
  <h2 id="form-time">Time Form</h2>

  A Time Form accept hour, minute, second, and millisecond values via a picker

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#time-state-(type=time)) with the following attributes:

  - One `type` attribute with the `time` value

  - Zero or one count for each of the following attributes:   

    - [`autocomplete`](/en/html-content-attributes/#attribute-autocomplete) 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form) 

    - [`list`](/en/html-content-attributes/#attribute-list) 

    - [`max`](/en/html-content-attributes/#attribute-max) 

    - [`min`](/en/html-content-attributes/#attribute-min) 

    - [`name`](/en/html-content-attributes/#attribute-name) 

    - [`readonly`](/en/html-content-attributes/#attribute-readonly) 

    - [`required`](/en/html-content-attributes/#attribute-required) 

    - [`step`](/en/html-content-attributes/#attribute-step) 

    - [`value`](/en/html-content-attributes/#attribute-value) 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="time">
  ```
</section>




<section>
  <h2 id="form-text">Text Form</h2>

  A Text Form accepts plain text

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#text-(type=text)-state-and-search-state-(type=search)) with the following attributes:

  - One `type` attribute with the `text` value

  - Zero or one count for each of the following attributes: 

    - [`autocomplete`](/en/html-content-attributes/#attribute-autocomplete) 

    - [`dirname`](/en/html-content-attributes/#attribute-dirname) 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form) 

    - [`list`](/en/html-content-attributes/#attribute-list) 

    - [`maxlength`](/en/html-content-attributes/#attribute-maxlength) 

    - [`minlength`](/en/html-content-attributes/#attribute-minlength) 

    - [`name`](/en/html-content-attributes/#attribute-name) 

    - [`pattern`](/en/html-content-attributes/#attribute-pattern) 

    - [`placeholder`](/en/html-content-attributes/#attribute-placeholder) 

    - [`readonly`](/en/html-content-attributes/#attribute-readonly) 

    - [`required`](/en/html-content-attributes/#attribute-required) 

    - [`size`](/en/html-content-attributes/#attribute-size) 

    - [`value`](/en/html-content-attributes/#attribute-value) 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="text">
  ```
</section>




<section>
  <h2 id="form-hidden">Hidden Form</h2>

  An Hidden Form accepts plain text from a program but, not from a user

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#hidden-state-(type=hidden)) with the following attributes:

  - One `type` attribute with the `hidden` value

  - Zero or one [`value` attribute](/en/html-content-attributes/#attribute-value) But, it must be omitted if there's a sibling `name` attribute with a `_charset_` value.

  - Zero or one count for each of the following attributes: 

    - [`autocomplete`](/en/html-content-attributes/#attribute-autocomplete) 

    - [`dirname`](/en/html-content-attributes/#attribute-dirname) 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form) 

    - [`name`](/en/html-content-attributes/#attribute-name) 


  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="hidden">
  ```
</section>




<section>
  <h2 id="form-radio">Radio Form</h2>

  A Radio Form accepts a value from a set of binary options

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#radio-button-state-(type=radio)) with the following attributes:

  - One `type` attribute with the `radio` value

  - Zero or one count for each of the following attributes:   

    - [`checked`](/en/html-content-attributes/#attribute-checked) 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form) 

    - [`name`](/en/html-content-attributes/#attribute-name) 

    - [`required`](/en/html-content-attributes/#attribute-required) 

    - [`value`](/en/html-content-attributes/#attribute-value) 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="radio">
  ```
</section>



<section>
  <h2 id="form-checkbox">Checkbox Form</h2>

  A Checkbox Form accepts a value from each item in a set of binary options

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#checkbox-state-(type=checkbox)) with the following attributes:

  - One `type` attribute with the `checkbox` value

  - Zero or one count for each of the following attributes: 

    - [`checked`](/en/html-content-attributes/#attribute-checked) 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form) 

    - [`name`](/en/html-content-attributes/#attribute-name) 

    - [`required`](/en/html-content-attributes/#attribute-required) 

    - [`value`](/en/html-content-attributes/#attribute-value) 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="checkbox">
  ```
</section>



<section>
  <h2 id="form-button-reset">Reset Button Form</h2>

  A Reset Button set associated [Content Forms](#outline) back to their default value. 

  A Reset Button Form can be a void or non-void content form

  <h3>Void Reset Button Form</h3>

  A Void Reset Button Form conveys the button with plain text

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#reset-button-state-(type=reset)) with the following attributes:

  - One `type` attribute with the `reset` value

  - Zero or one count for each of the following attributes:   

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form) 

    - [`name`](/en/html-content-attributes/#attribute-name) 

    - [`popovertarget`](/en/html-content-attributes/#attribute-popovertarget) 

    - [`popovertargetaction`](/en/html-content-attributes/#attribute-popovertargetaction) 

    - [`value`](/en/html-content-attributes/#attribute-value) 


  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <button type="reset"></button>
  ```
</section>


<section>
  <h3>Non-void Reset Button Form</h3>

  A Non-void Reset Button conveys the button with rich content

  The syntax is a [`button` element](https://html.spec.whatwg.org/#the-button-element) with the following contents:

  - One `type` attribute with the `reset` value

  - Zero or one count for each of the following attributes: 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled) 

    - [`form`](/en/html-content-attributes/#attribute-form) 

    - [`name`](/en/html-content-attributes/#attribute-name) 

    - [`popovertarget`](/en/html-content-attributes/#attribute-popovertarget) 

    - [`popovertargetaction`](/en/html-content-attributes/#attribute-popovertargetaction) 

    - [`value`](/en/html-content-attributes/#attribute-value) 


  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation](/en/html-content-connotations/) But exclude the following descendant [interactive contents](https://html.spec.whatwg.org/#interactive-content):

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
  <button type="reset"></button>
  ```
</section>





<section>
  <h2 id="form-button-submit">Submit Button Form</h2>

  A Submit Button initiates the submission of associated Content Forms. 

  A collection of Content Forms are associated if they have the same parent [Form Card](/en/html-content-mixes/#card-form) or use a [`form` attribute](/en/html-content-attributes/#attribute-form) to the same Form Card

  A Submit Button Form can be a void or non-void content form

  <h3>Void Submit Button Form</h3>

  A Void Submit Button Form conveys the button with rich content

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#submit-button-state-(type=submit)) with the following attributes:

  - One `type` attribute with the `submit` value

  - Zero or one count for each of the following attributes: [`disabled`](/en/html-content-attributes/#attribute-disabled), [`value`](/en/html-content-attributes/#attribute-value), [`name`](/en/html-content-attributes/#attribute-name), [`dirname`](/en/html-content-attributes/#attribute-dirname), [`form`](/en/html-content-attributes/#attribute-form), [`formaction`](/en/html-content-attributes/#attribute-formaction), [`formenctype`](/en/html-content-attributes/#attribute-formenctype), [`formmethod`](/en/html-content-attributes/#attribute-formmethod), [`formnovalidate`](/en/html-content-attributes/#attribute-formnovalidate), [`formtarget`](/en/html-content-attributes/#attribute-formtarget), [`popovertarget`](/en/html-content-attributes/#attribute-popovertarget), and [`popovertargetaction`](/en/html-content-attributes/#attribute-popovertargetaction)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <button type="submit"></button>
  ```
</section>



<section>
  <h3>Non-void Submit Button Form</h3>

  A Non-void Submit Button Form conveys the button with rich content

  The syntax is a [`button` element](https://html.spec.whatwg.org/#the-button-element) with the following contents:

  - One `type` attribute with the `submit` value

  - Zero or one count for each of the following attributes: [`disabled`](/en/html-content-attributes/#attribute-disabled), [`value`](/en/html-content-attributes/#attribute-value), [`name`](/en/html-content-attributes/#attribute-name), [`form`](/en/html-content-attributes/#attribute-form), [`formaction`](/en/html-content-attributes/#attribute-formaction), [`formenctype`](/en/html-content-attributes/#attribute-formenctype), [`formmethod`](/en/html-content-attributes/#attribute-formmethod), [`formnovalidate`](/en/html-content-attributes/#attribute-formnovalidate), [`formtarget`](/en/html-content-attributes/#attribute-formtarget), [`popovertarget`](/en/html-content-attributes/#attribute-popovertarget), and [`popovertargetaction`](/en/html-content-attributes/#attribute-popovertargetaction)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation](/en/html-content-connotations/) But exclude the following descendant [interactive contents](https://html.spec.whatwg.org/#interactive-content):

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
  <button type="submit"></button>
  ```
</section>




<section>
  <h2 id="form-button-image">Image Button Form</h2>

  An Image Button initiates the submission of associated Content Forms along with an image coordinate.

  A collection of Content Forms are associated if they have the same parent [Form Card](/en/html-content-mixes/#card-form) or use a [`form` attribute](/en/html-content-attributes/#attribute-form) to the same Form Card

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#image-button-state-(type=image)) with the following attributes:

  - One `type` attribute with the `image` value

  - Zero or one count for each of the following attributes: 
  [`alt`](/en/html-content-attributes/#attribute-alt) 
  [`disabled`](/en/html-content-attributes/#attribute-disabled) 
  [`form`](/en/html-content-attributes/#attribute-form) 
  [`formaction`](/en/html-content-attributes/#attribute-formaction) 
  [`formenctype`](/en/html-content-attributes/#attribute-formenctype) 
  [`formmethod`](/en/html-content-attributes/#attribute-formmethod) 
  [`formnovalidate`](/en/html-content-attributes/#attribute-formnovalidate) 
  [`formtarget`](/en/html-content-attributes/#attribute-formtarget) 
  [`height`](/en/html-content-attributes/#attribute-height) 
  [`name`](/en/html-content-attributes/#attribute-name) 
  [`popovertarget`](/en/html-content-attributes/#attribute-popovertarget) 
  [`popovertargetaction`](/en/html-content-attributes/#attribute-popovertargetaction) 
  [`src`](/en/html-content-attributes/#attribute-src) 
  [`value`](/en/html-content-attributes/#attribute-value) 
  [`width`](/en/html-content-attributes/#attribute-width) 


  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <input type="image">
  ```
</section>



<section>
  <h2 id="form-button-custom">Custom Button Form</h2>

  A Custom Button Form initiates a custom command to preferred contents

  A Custom Button Form can be a void or non-void content form

  <h3>Void Custom Button Form</h3>

  A Void Custom Button Form conveys the button with plain text

  The syntax is a void [`input` element](https://html.spec.whatwg.org/#the-input-element) with the following attributes:

  - One `type` attribute with the `button` value

  - Zero or one count for each of the following attributes:   [`disabled`](/en/html-content-attributes/#attribute-disabled) 
  [`form`](/en/html-content-attributes/#attribute-form) 
  [`name`](/en/html-content-attributes/#attribute-name) 
  [`popovertarget`](/en/html-content-attributes/#attribute-popovertarget) 
  [`popovertargetaction`](/en/html-content-attributes/#attribute-popovertargetaction) 
  [`value`](/en/html-content-attributes/#attribute-value) 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  ```html
  <button type="button"></button>
  ```
</section>



<section>
  <h3>Non-void Custom Button Form</h3>

  A Non-void Custom Button Form conveys the button with rich content

  The syntax is a [`button` element](https://html.spec.whatwg.org/#the-button-element) with the following contents:

  - One `type` attribute with the `button` value

  - Zero or one count for each of the following attributes: [`disabled`](/en/html-content-attributes/#attribute-disabled) 
  [`form`](/en/html-content-attributes/#attribute-form) 
  [`name`](/en/html-content-attributes/#attribute-name) 
  [`popovertarget`](/en/html-content-attributes/#attribute-popovertarget) 
  [`popovertargetaction`](/en/html-content-attributes/#attribute-popovertargetaction) 
  [`value`](/en/html-content-attributes/#attribute-value) 

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation](/en/html-content-connotations/) But exclude the following descendant [interactive contents](https://html.spec.whatwg.org/#interactive-content):

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
  <button type="button"></button>
  ```
</section>





<aside>
<h2>Utility Contents</h2>

A Content Form may use one or more of the following contents


<section>
<h3 id="data-list">Data List</h3>

  A Data List relates a set of suggestions for [Content Forms](/en/html-content-forms/) that uses a [`list` attribute](/en/html-content-attributes/#attribute-list)

  The syntax is a [`datalist` element](https://html.spec.whatwg.org/#the-datalist-element) with the following contents:

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each [Option Item](#item-option)

  - Zero or more counts for each Text Content, [Content Object](/en/html-content-objects/), [Content Form](/en/html-content-forms/), [Content Break](/en/html-content-breaks/), and [Content Connotation](/en/html-content-connotations/). But, as fallback contents.

  ```html
  <datalist></datalist>
  ```
</section>


<section>
<h3 id="item-option">Option Item</h3>
  
  An Option Item specifies a choice in a [Select Form](#form-select) or a suggestion in a [Data List](#data-list)

  The syntax is an [`option` element](https://html.spec.whatwg.org/#the-option-element) with the following contents:

  - Zero or one count for each of the following attributes: 

    - [`disabled`](/en/html-content-attributes/#attribute-disabled)

    - [`label`](/en/html-content-attributes/#attribute-label) 

    - [`selected`](/en/html-content-attributes/#attribute-selected) 

    - [`value`](/en/html-content-attributes/#attribute-value)


  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - No content if there're the following attributes: `label`, and `value`. Otherwise, text content. However, it must be non-empty text content if there's no `label` attribute and the `option` element is not a child of a Data List.

  ```html
  <option></option>
  ```
</section>


<section>
<h3 id="group-option">Option Group</h3>

  An Option Group relates a set of [Option Items](#item-option) in a [Select Form](#form-select). 

  The syntax is an [`optgroup` element](https://html.spec.whatwg.org/#the-optgroup-element) with the following contents:

  - One [`label` attribute](/en/html-content-attributes/#attribute-label)

  - Zero or one [`disabled` attribute](/en/html-content-attributes/#attribute-disabled)

  - Zero or one count for each [Global Attribute](https://html.spec.whatwg.org/#global-attributes)

  - Zero or more counts for each [Option Item](#item-option)

  ```html
  <optgroup label="[term]"></optgroup>
  ```
</section>



</aside>

