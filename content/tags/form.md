+++
date = "2016-10-01T00:45:09+05:30"
next = "/tags/head"
prev = "/tags/footer"
title = "form"
toc = true
weight = 35

+++

<h3>Standard Definition</h3>
An HTML form is a section of a document containing normal content, markup, special elements called controls (checkboxes, radio buttons, menus, etc.), and labels on those controls. Users generally "complete" a form by modifying its controls (entering text, selecting menu items, etc.), before submitting the form to an agent for processing (e.g., to a Web server, to a mail server, etc.)

<h3>Need for this tag</h3>
The form element allows you to define method and action attributes, which tell the browser what to do when the form is submitted. AJAX isn't a 100% coverage tool, and as a web developer you should be practicing graceful degradation - forms should be able to be submitted, and data transferred, even when JS is turned off.
<ol>
  <li>if you want to execute a traditional (ie. non-AJAX) form post.</li>
  <li>you want to capture the "submit" event programmatically.</li>
  <li>it is needed in order for mobile Safari to show the "Go" button on the keyboard.</li>
  <li>it is needed if you want to programmatically "reset" a form (ie. call reset()).</li>
  <li>it is needed if you have to segregate fields with the same name.</li>
</ol>

<h3>Advantages of this tag</h3>
<ol>
  <li>Using form tags can help people read and understand you code in some cases, by showing them your intentions.</li>
  <li>The 'onsubmit' method is available on forms. If you have a form with an input[type=submit], and it's not disabled, then when someone hits 'enter' while filling out one of the other form inputs, the form will submit. You can still do that by listening for the 'keydown' event on the input elements, but it's a nice bit of ui that you get for free with form tags.</li>
  <li>It makes generic form serialization easier (since it groups input fields).</li>
</ol>

<h3>Working Example</h3>

    <form action="http://somesite.com/prog/adduser" method="post">
      <p>
        <label for="firstname">First name: </label>
        <input type="text" id="firstname"><BR>
        <label for="lastname">Last name: </label>
        <input type="text" id="lastname"><BR>
        <label for="email">email: </label>
        <input type="text" id="email"><BR>
        <input type="radio" name="sex" value="Male"> Male<BR>
        <input type="radio" name="sex" value="Female"> Female<BR>
        <input type="submit" value="Send"> <input type="reset">
      </p>
    </form>

<h3>References</h3>
http://www.tutorialrepublic.com/html-reference/html5-form-tag.php
<br>
https://www.w3.org/TR/html401/interact/forms.html
<br>
http://www.quackit.com/html_5/tags/html_form_tag.cfm
<br>
http://stackoverflow.com/questions/31066693/what-is-the-purpose-of-the-html-form-tag

<h3>Point of Contact</h3>
Shashank Jain <br>
shashajain@deloitte.com <br>
9742228200
