+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/figure"
prev = "/tags/fieldset"
title = "figcaption"
toc = true
weight = 32

+++

The HTML figcaption element represents a caption or a legend associated with a figure or an illustration described by the rest of the data of the figure element which is its immediate ancestor which means figcaption can be the first or last element inside a figure block. Also, the HTML Figcaption Element is optional; if not provided, then the parent figure element will have no caption.

<h3>Need for this tag</h3>
FIGCAPTION Element is used to put an additional information about the image. As if we have to give a discription about the image, we don't need to embed an another paragraph to define the description. It may slightly complex also, to use another paragraph and style it with the displayed image. So with FIGCAPTION Element, we can define a description and it will automatically adjust its surrounding style according the image.

<h3>Disadvantage of this tag</h3>
<ol>
  <li>Older browsers (such as IE8 and below) will need JavaScript-based polyfills and basic CSS to make the elements behave as intended</li>
</ol>

<h3>Advantages of this tag</h3>
<ol>
  <li>If you need to add more semantics to an image, you can use elements such as h1 and p inside figcaption.</li>
</ol>

<h3>Working Example</h3>

    <figure>
      <img src="discovery.jpg" alt="Space Shuttle">
      <figcaption>NASA - Space Shuttle Discovery</figcaption>
    </figure>

<h3>References</h3>
http://www.quackit.com/html_5/tags/html_figcaption_tag.cfm
<br>
http://www.tutorialrepublic.com/html-reference/html-figcaption-tag.php
<br>
https://developer.mozilla.org/en/docs/Web/HTML/Element/figcaption

<h3>Point of Contact</h3>
Shashank Jain <br>
shashajain@deloitte.com <br>
9742228200
