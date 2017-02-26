+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/dl"
prev = "/tags/dialog"
title = "div"
toc = true
weight = 25

+++

The HTML <code>div</code> (short for division) tag is generic container for flow content, which has no default rendering or meaning. The tag is extensively used to define the structural sections of a document and to layout a web page using CSS. With the <code>div</code> tag, you can group large sections of HTML elements together and format them with CSS.

<h3>Need for this tag</h3>
Pages have parts – sections that serve particular functions – and as a rule those parts have been set with <code>div</code> tags. On the top of most pages is a header. Likewise most pages have a navigation <code>div</code> and on the bottom a footer. These are <code>div</code> that tend stay the same throughout a website. Then there are <code>divs</code> (or a <code>div</code>) with content that is unique to each page.

<h3>Disadvantage of this tag</h3>
The most obvious disadvantage of the <code>div</code> tag is the fact that it doesn't aid in adding semantics to the page. The <code>div</code> tag is a generic holder of content. As such, a parser has no understanding of why that content is being pulled out and place in its own container.

<h3>Advantages of this tag</h3>
<ol>
  <li>Properly structuring our DOM (Document Object Model)</li>
  <li>It is a container in which you create a division of your documents and you can manipulate your document layout using class and id names in the <code>div</code> tag.</li>
  <li>A <code>div</code> is a block element. This means that if you use a div, unless  you float objects next to it using CSS, the <code>div</code> will be alone on a line.</li>
</ol>


<h3>Working Example</h3>

    <div class="welcome-box">
      <h1>Welcome</h1>
      <p>Hi, welcome to our website.</p>
    </div>

<div class="welcome-box">
  <h1>Welcome</h1>
  <p>Hi, welcome to our website.</p>
</div>

<h3>References</h3>
[TutorialRepublic](http://www.tutorialrepublic.com/html-reference/html-div-tag.php)
<br>
[Quackit](http://www.quackit.com/html_5/tags/html_div_tag.cfm)
