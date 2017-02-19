+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/table"
prev = "/tags/summary"
title = "sup"
toc = true
weight = 101

+++

<h3>Standard Definition</h3>

The HTML <span class='tag-span'>&lt;sup&gt;</span> element defines a span of text that should be displayed, for typographic reasons, higher, and often smaller, than the main span of text.

{{% notice tip %}}
  This element should be used for typographical reasons only, i.e. changing the position of the text changing its meaning like in mathematical (like f4, though the use of a MathML formula should be considered) or in French abbreviations (like Mlle, Mme or Cie)
{{% /notice %}}

{{% notice note %}}
  This element must not be used for styling purpose like the styling of the product name Latex. In that case CSS style should be used: the vertical-align property with the super value will achieve the same effect.
{{% /notice %}}

<h3>Advantages of this tag</h3>
  <ul>
    <li>
      Superscript is especially useful for presenting mathematical exponents or writing ordinal numbers
    </li>
    <li>The default cascading style sheet settings of the superscript tag for most web browsers are "vertical-align:super" and "font-size:smaller"</li>
  </ul>

<h3>Working Example</h3>

        <p>This text is <sup>superscripted</sup></p>

<p>This text is <sup>superscripted</sup></p>

<h3>References</h3>
[MDN](https://developer.mozilla.org/en/docs/Web/HTML/Element/sup)
