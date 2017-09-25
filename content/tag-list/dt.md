+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/em"
prev = "/tags/doctype"
title = "dt"
toc = true
weight = 28

+++

The HTML dt element (or HTML Definition Term Element) identifies a term in a definition list. This element can occur only as a child element of a dl. It is usually followed by a dd element; however, multiple dt elements in a row indicate several terms that are all defined by the immediate next dd element.

<h3>Need for this tag</h3>
As DL consist of a structure which has name value pair, so DT is needed to provide a name to all the values defined in the Definition List structure.

<h3>Advantages of this tag</h3>
<ol>
  <li>dt provide a context for the text with which they are associated. By being given context, text is given added meaning.</li>
  <li>dt is used in google glossary. By semantically marking up your content you enable it to be processed by automatic methods much more easily.</li>
  <li>By using definition term, and other semantic markup constructs, you can more easily extract structured information about your content.</li>
</ol>

<h3>Disadvantage of this tag</h3>
<ol>
  <li>The dt within definition lists cannot contain block level elements – particularly heading elements (h1 – h6). If content within a dt cannot be flagged as a heading, it cannot be given “heading” importance within the document hierarchy. Also, Google and other search engines will not index definition list content in the same way that they do for heading-based content.</li>
</ol>

<h3>Working Example</h3>

    <dl>
      <dt>term1</dt>
      <dd>– definition1</dd>
      <dt>term2</dt>
      <dd>– definition2</dd>
    </dl>

<h3>References</h3>
http://www.tutorialrepublic.com/html-reference/html-div-tag.php
<br>
http://www.quackit.com/html_5/tags/html_div_tag.cfm
<br>
https://developer.mozilla.org/en/docs/Web/HTML/Element/dt
<h3>Point of Contact</h3>
Shashank Jain <br>
shashajain@deloitte.com <br>
9742228200
