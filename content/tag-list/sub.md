+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/summary"
prev = "/tags/strong"
title = "sub"
toc = true
weight = 89

+++

<h3>Standard Definition</h3>

The HTML <span class='tag-span'>&lt;sub&gt;</span> element defines a span of text that should be displayed, for typographic reasons, lower, and often smaller, than the main span of text.


{{% notice tip %}}
  This element should be used for typographical reasons only, i.e. changing the position of the text changing its meaning like in mathematical (like t2, though the use of a MathML formula should be considered) or chemical formulas (like H2O).
{{% /notice %}}

{{% notice note %}}
  This element must not be used for styling purpose like the styling of the product name Latex. In that case CSS style should be used: the vertical-align property with the super value will achieve the same effect.
{{% /notice %}}

<h3>Working Example</h3>

        <p>The chemical formula of water: H<sub>2</sub>O</p>

<p>The chemical formula of water: H<sub>2</sub>O</p>

<h3>References</h3>

[MDN](https://developer.mozilla.org/en/docs/Web/HTML/Element/sub)
