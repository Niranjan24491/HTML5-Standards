+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/doctype"
prev = "/tags/div"
title = "dl"
toc = true
weight = 26

+++

The <code>dl</code> (short for definition list) tag specifies a definition list. It is a list of terms with their associated definitions. It encloses a list of pairs of terms and descriptions.

<h3>Need for this tag</h3>
A definition list is the container element for DT and DD elements. The DL element should be used when you want to incorporate a definition of a term in your document, it is often used in glossaries to define many terms, it is also used in “normal” documents when the author wishes to explain a term in a more detail (Like this definition).

<h3>Advantages of this tag</h3>
<ol>
  <li>dl provide a context for the text with which they are associated. By being given context, text is given added meaning.</li>
  <li>dl is used in google glossary. By semantically marking up your content you enable it to be processed by automatic methods much more easily.</li>
  <li>By using definition lists, and other semantic markup constructs, you can more easily extract structured information about your content.</li>
</ol>

<h3>Disadvantage of this tag</h3>
<ol>
  <li>The dt within definition lists cannot contain block level elements – particularly heading elements (h1 – h6). If content within a dt cannot be flagged as a heading, it cannot be given “heading” importance within the document hierarchy. Also, Google and other search engines will not index definition list content in the same way that they do for heading-based content.</li>

  <li>Although definition lists can be styled to look like tabular data, they cannot contain screen reader accessibility features such as “labels” and “headers” to tie information together. For this reason, they should not be used to replace complex tabular data.</li>
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
http://www.benmeadowcroft.com/webdev/articles/definition-lists/
<h3>Point of Contact</h3>
Shashank Jain <br>
shashajain@deloitte.com <br>
9742228200
