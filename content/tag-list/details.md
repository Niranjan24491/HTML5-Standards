+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/dfn"
prev = "/tags/del"
title = "details"
toc = true
weight = 22

+++

The HTML <span class='tag-span'>&lt;details&gt;</span> element tag is used along with <span class='tag-span'>&lt;summary&gt;</span> to create an accordion-like widget. It is used as a wrapper for all the content we want to show and hide.

<h3>Need for this tag</h3>

<p>To create an interactive and accordion-like widget that the user can toggle open and close.</p>

{{% notice note %}}
  This behaviour does not depend on scripting language(JS), and should work even if JavaScript is disabled or not present.
{{% /notice %}}

<h3>Disadvantages of this tag</h3>

<p>Browser support is the only concern for this tag. IE-Edge and older version of Firefox are yet to support this tag, we'll have to use some polyfills to get the effect.</p>

<h3>Advantages of this tag</h3>

<ul>

  <li>Removed dependency on any javascript library to accomplish this behavior which bloats the page size for the user.</li>

  <li>Will get an accessibility bonus since now this behavior will be handled natively in the browser</li>

</ul>

{{% notice tip %}}
  People often use accordions for FAQs anyway, so they’re a great candidate for <span class='tag-span'>&lt;details&gt;</span>/<span class='tag-span'>&lt;summary&gt;</span>.
{{% /notice %}}

<h3>Working Example</h3>

    <details>
      <summary>Accordion Summary</summary>
      <p>Here is the data residing under accordion... </p>
    </details>


<details>
  <summary>Accordion Summary</summary>
  <p>Here is the data residing under accordion... </p>
</details>

<p>Click on accordion summary text</p>

<h3>References</h3>

[MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details)
<br>
[HTML5Doctor](http://html5doctor.com/the-details-and-summary-elements/)
