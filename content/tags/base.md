+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/bdi"
prev = "/tags/audio"
title = "base"
toc = true
weight = 5

+++

The HTML <span class='tag-span'>&lt;base&gt;</span> element specifies the base URL to use for all relative URLs contained within a document. There can be only one <span class='tag-span'>&lt;base&gt;</span> element in a document.

<h3>Disadvantages of this tag</h3>
<ul>
  <li>There cannot be more than one <span class='tag-span'>&lt;base&gt;</span> element per document.</li>
  <li>If multiple <span class='tag-span'>&lt;base&gt;</span> elements are specified, only the first href and first target value are used; all others are ignored.</li>
</ul>

<h3>Advantages of this tag</h3>
<ol>
  <li>Will help in Search Engine Optimization(SEO) by following the HTML standards</li>
  <li>Provides semantic meaning to the HTML page</li>
</ol>

<h3>Working Example</h3>

    <!DOCTYPE html>
    <html>
        <head>
            <title>This is an example for the &lt;base&gt; element</title>
            <base href="http://www.example.com/news/index.html">
        </head>
        <body>
            <p>Visit the <a href="archives.html">archives</a>.</p>
        </body>
    </html>

<h3>References</h3>
[MDN](https://developer.mozilla.org/en/docs/Web/HTML/Element/base)
<br>
[W3](https://www.w3.org/TR/html5/document-metadata#the-base-element)

<h3>Point of Contact</h3>
Niranjan Thrineshwar <br>
nthrineshwar@deloitte.com <br>
9663770742
