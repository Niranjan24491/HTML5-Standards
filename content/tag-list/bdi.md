+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/bdo"
prev = "/tags/base"
title = "bdi"
toc = true
weight = 9

+++

The HTML <span class='tag-span'>&lt;bdi&gt;</span> Element (or Bi-Directional Isolation Element) isolates a span of text that might be formatted in a different direction from other text outside it.

<h3>Need for this tag</h3>
The <span class='tag-span'>&lt;bdi&gt;</span> element is useful when embedding text with an unknown directionality, from a database for example, inside text with a fixed directionality.

{{% notice note %}}
  Though the same visual effect can be achieved using the CSS rule unicode-bidi: isolate on a <span> or another text-formatting element, the semantic meaning is only conveyed by the <bdi> element. Especially, browsers are allowed to ignore CSS styling. In such a case, the text would still be correctly displayed using the HTML element, but will become garbage when using the CSS styling to convey semantic.
{{% /notice %}}

<h3>Advantages of this tag</h3>
<ol>
  <li>Will help in Search Engine Optimization(SEO) by following the HTML standards</li>
  <li>Provides semantic meaning to the HTML page</li>
</ol>

<h3>Working Example</h3>

    <p>And the top five contributors are:</p>
    <ol>
      <li>User <bdi>إيان</bdi>: 195 posts</li>
    </ol>

<p>And the top five contributors are:</p>
<ol>
  <li>User <bdi>إيان</bdi>: 195 posts</li>
</ol>

{{% notice tip %}}
  In the example above, usernames are shown along with the number of points in a contest. If the <span class='tag-span'>&lt;bdi&gt;</span> element is not supported in the browser, the username of the Arabic user would confuse the text (the bidirectional algorithm would put the colon and the number "195" next to the word "User" rather than next to the word "points").
{{% /notice %}}


<h3>References</h3>
[MDN](https://developer.mozilla.org/en/docs/Web/HTML/Element/bdi)
<br>
[Quackit](http://www.quackit.com/html_5/tags/html_bdi_tag.cfm)
