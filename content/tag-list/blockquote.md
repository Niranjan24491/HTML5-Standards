+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/body"
prev = "/tags/bdo"
title = "blockquote"
toc = true
weight = 11

+++

The HTML <span class='tag-span'>&lt;blockquote&gt;</span> Element (or HTML Block Quotation Element) indicates that the enclosed text is an extended quotation. Usually, this is rendered visually by indentation. A URL for the source of the quotation may be given using the cite attribute, while a text representation of the source can be given using the <span class='tag-span'>&lt;cite&gt;</span> element.

<h3>Attributes</h3>
This element includes the global attributes "cite" to mention URL that designates a source document or message for the information quoted. This attribute is intended to point to information explaining the context or the reference for the quote.

{{% notice tip %}}
  To change <span class='tag-span'>&lt;blockquote&gt;</span> indent, use CSS margin property. <br/>
  For short quotes use <span class='tag-span'>&lt;q&gt;</span> element.
{{% /notice %}}

<h3>Working Example</h3>

    <blockquote cite="http://developer.mozilla.org">
      <p>This is a quotation taken from the Mozilla Developer Center.</p>
    </blockquote>

<blockquote cite="http://developer.mozilla.org">
  <p>This is a quotation taken from the Mozilla Developer Center.</p>
</blockquote>

<h3>References</h3>
[MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote)
