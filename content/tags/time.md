+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/title"
prev = "/tags/thead"
title = "time"
toc = true
weight = 110

+++

The HTML <span class='tag-span'>&lt;time&gt;</span> tag is used for declaring the date and/or time within an HTML document. It was added to the HTML5 specs back in 2009. Later in 2011, the spec was dropped. Later, the time element was added back with some revamped features.

<h3>Need for this tag</h3>

It represents the date, time, or duration for whatever text you are representing in a machine readable format. That means it is for computers, not humans, so it has very specific formats.

{{% notice tip %}}
  Any script or search engine reading your content can understand the date/time of publication with the help of <span class='tag-span'>&lt;time&gt;</span> tag.
{{% /notice %}}

<h3>Disadvantages of this tag</h3>

<ol>
  <li>The <span class='tag-span'>&lt;time&gt;</span> tag cannot be used for dates prior to the Gregorian calendar.</li>
  <li>The <span class='tag-span'>&lt;time&gt;</span> element cannot appear as a descendant of the <span class='tag-span'>&lt;time&gt;</span> element.</li>
</ol>

<h3>Advantages of this tag</h3>

<ol>
  <li>It can be used for creating event scheduling, archiving, and other time-based functions. </li>
</ol>

<h3>Working Example</h3>

<p>The concert is <time datetime="2009-02-18">next Wednesday</time>.</p>

    <p>The concert is <time datetime="2009-02-18">next Wednesday</time>.</p>

<h3>References</h3>

[MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/time)
<br>
[W3](https://www.w3.org/TR/2011/WD-html-markup-20110405/time.html)
<br>
[CSS-Tricks](https://css-tricks.com/time-element/)

<h3>Point of Contact</h3>
