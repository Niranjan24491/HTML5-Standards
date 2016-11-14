+++
date = "2016-10-01T00:44:48+05:30"
next = "/tags/select"
prev = "/tags/s"
title = "section"
toc = true
weight = 84

+++

The HTML <span class='tag-span'>&lt;section&gt;</span> element represents a generic section of a document, i.e., a thematic grouping of content, typically with a heading. Each &lt;section&gt; should be identified, typically by including a heading (&lt;h1&gt;-&lt;h6&gt; element) as a child of the &lt;section&gt; element.

<h3>Rules of thumb for using &lt;section&gt;</h3>

Of course, there are always exceptions, but these should give useful guidance for 99% of cases:
<ol>
  <li>Don’t use it just as hook for styling or scripting; that’s a div.</li>
  <li>Don’t use it if article, aside or nav is more appropriate.</li>
  <li>Don’t use it unless there is naturally a heading at the start of the section.</li>
</ol>

<h3>Advantages of this tag</h3>
<ol>
  <li>Will help in Search Engine Optimization(SEO) by following the HTML standards</li>
  <li>Provides semantic meaning to the HTML page</li>
</ol>

<h3>Working Example</h3>

    <section>
      <h2>Heading</h2>
      <img src="bird.jpg" alt="bird">
    </section>

<h3>The difference between 	&lt;section&gt; and &lt;div&gt;</h3>

<h5>&lt;section&gt;</h5>

<p>The section element represents a generic section of a document or application. A section, in this context, is a thematic grouping of content, typically with a heading.</p>

<p>Examples of sections would be chapters, the various tabbed pages in a tabbed dialog box, or the numbered sections of a thesis. A Web site's home page could be split into sections for an introduction, news items, and contact information.</p>

{{% notice note %}}
  The section element is not a generic container element. When an element is needed for styling purposes or as a convenience for scripting, authors are encouraged to use the div element instead. A general rule is that the section element is appropriate only if the element's contents would be listed explicitly in the document's outline.
{{% /notice %}}


<h5>&lt;div&gt;</h5>

<p>The div element has no special meaning at all. It represents its children. It can be used with the class, lang, and title attributes to mark up semantics common to a group of consecutive elements.</p>

{{% notice note %}}
  Authors are strongly encouraged to view the div element as an element of last resort, for when no other element is suitable. Use of the div element instead of more appropriate elements leads to poor accessibility for readers and poor maintainability for authors.
{{% /notice %}}

<h3>References</h3>

[MDN](https://developer.mozilla.org/en/docs/Web/HTML/Element/section)
<br>
http://html5doctor.com/the-section-element/
<br>
http://w3c.github.io/html/sections.html#the-section-element

<h3>Point Of Contact</h3>
Niranjan Thrineshwar
