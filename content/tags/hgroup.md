+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/hr"
prev = "/tags/headings"
title = "hgroup"
toc = true
weight = 39

+++

<h3>Standard Definition</h3>
This tag is typically used to group a set of one or more h1-h6 elements.It’s all about the document outline. When grouping headings in an hgroup element, the outline algorithm will mask all but the highest level heading in the group from the resulting document outline.


<h3>Need for this tag</h3>
This tag is needed to group one or more related heading elements possibly contained within a header element.

<h3>Advantages of this tag</h3>
<ol>
  <li>hgroup tag acts as a wrapper for two one or more related heading elements possibly contained within a header element.</li>
</ol>

<h3>Disadvantages of this tag</h3>
<ol>
  <li>This tag has now been dropped from the W3C HTML5 specification. However, it is still included in the WHATWG Living Standard specification.</li>
  <li>Heading semantics are still exposed regardless of an outer hgroup.</li>
</ol>


<h3>Working Example</h3>

	<header>
	<hgroup>
	<h1>Talking Dogs</h1>
	<h2>Humans aren't the only talkers!</h2>
	</hgroup>
	</header>

<h3>References</h3>
http://www.quackit.com/html_5/tags/html_hgroup_tag.cfm
