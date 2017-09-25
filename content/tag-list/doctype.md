+++
date = "2016-10-01T00:45:09+05:30"
next = "/tags/dt"
prev = "/tags/dl"
title = "doctype"
toc = true
weight = 27

+++

The HTML syntax of HTML5 requires a DOCTYPE to be specified to ensure that the browser renders the page in standards mode. The DOCTYPE has no other purpose and is therefore optional for XML. Documents with an XML media type are always handled in standards mode. [DOCTYPE]

The DOCTYPE declaration is <!DOCTYPE html> and is case-insensitive in the HTML syntax. DOCTYPEs from earlier versions of HTML were longer because the HTML language was SGML-based and therefore required a reference to a DTD. With HTML5 this is no longer the case and the DOCTYPE is only needed to enable standards mode for documents written using the HTML syntax. Browsers already do this for <!DOCTYPE html>.

<h3>Need for this tag</h3>
Why specify a doctype? Because it defines which version of (X)HTML your document is actually using, and this is a critical piece of information needed by some tools processing the document.

For example, specifying the doctype of your document allows you to use tools such as the Markup Validator to check the syntax of your (X)HTML. Such tools won't be able to work if they do not know what kind of document you are using.

But the most important thing is that with most families of browsers, a doctype declaration will make a lot of guessing unnecessary, and will thus trigger a "standard" rendering mode.

<h3>Advantages of this tag</h3>
<ol>
  <li>Will help in Search Engine Optimization(SEO) by following the HTML standards</li>
  <li>Provides semantic meaning to the HTML page</li>
  <li>This is a critical piece of information needed by some tools processing the document</li>
</ol>

<h3>Working Example</h3>

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="utf-8">

<h3>References</h3>
https://www.sitepoint.com/community/t/doctype-importance-and-why-we-use-doctype/28956/2
<br>
http://stackoverflow.com/questions/6076432/why-do-i-need-a-doctype-what-does-it-do

<h3>Point of Contact</h3>
Niranjan Thrineshwar
nthrineshwar@deloitte.com
9663770742
