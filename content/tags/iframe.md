+++
date = "2016-10-01T00:45:09+05:30"
next = "/tags/img"
prev = "/tags/html"
title = "iframe"
toc = true
weight = 5

+++

<h3>Standard Definition</h3>
The HTML Inline Frame Element (iframe) represents a nested browsing context, effectively embedding another HTML page into the current page. In HTML 4.01, a document may contain a head and a body or a head and a frameset, but not both a body and a frameset. However, an iframe can be used within a normal document body. Each browsing context has its own session history and active document. The browsing context that contains the embedded content is called the parent browsing context. The top-level browsing context (which has no parent) is typically the browser window.

<h3>Need for this tag</h3>
Following are the points where iframe tag is needed.
<ol>
  <li>embedding third-party media</li>
  <li>embedding your own media in a document-agnostic way</li>
  <li>embedding code examples (we do it on this site)</li>
  <li>embedding third party "applets" like payment forms</li>
</ol>

<h3>Disadvantages of this tag</h3>
<ol>
  <li>In cases of mobile use and some old browsers the iframe doesn’t responds faster and thus, error of page cannot be displayed is shown there…</li>
  <li>One of the main problem with an iframe is bookmark and navigation. it should be only used for embed a page inside your content.</li>
  <li>Blocks page onload and Non-semantic</li>
</ol>
<h3>Advantages of this tag</h3>
<ol>
  <li>To Use an External Content on your Webpage like: You-Tube Videos, Online Games, Flash files, etc…</li>
  <li>For the purpose of Advertisements based on Images and their links, instead of placing images and codes every where just place the iframe tag and whenever you need to change the advertisements just change it in the iframe source and all pages will be updated with the new advertisements.</li>
  <li>To add a content which should not be concerned with search engines as Robots will read the source code as the iframe tag only but won’t be entering to the iframe’s content</li>
  <li>URL Branding – this is very important use of iframe as sometimes we need to show some pages completely, this way whole pages can be sourced under our own URL and customized header and footer for that content or demo piece.</li>
  <li>With proper use of Adjusting Heights and Sides you can also crop another Webpage into your own Webpage as required.</li>
  <li>Repeats with No Conflicts – this means that using same Id’s or Name’s in using tags won’t conflict and CSS will work individually for both Perfectly.</li>
</ol>

<h3>Working Example</h3>

    <iframe src="hello.html" width="400" height="300"
    scrolling="auto">
      <p>[Your browser does not support frames or is currently configured not to display frames. However, you may visit <a href="optional.html">the related document.</a>]</p>
    </iframe>

<h3>References</h3>
https://developer.mozilla.org/en/docs/Web/HTML/Element/iframe
<br>
http://www.tutorialrepublic.com/html-reference/html-iframe-tag.php
<br>
https://developer.yahoo.com/performance/rules.html


<h3>Point of Contact</h3>
Shashank Jain <br>
shashajain@deloitte.com <br>
9742228200
