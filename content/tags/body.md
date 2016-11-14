+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/button"
prev = "/tags/blockquote"
title = "body"
toc = true
weight = 5

+++

The HTML <body> Element represents the content of an HTML document. There can be only one <body> element in a document.

<h3>Need for this tag</h3>
The start tag may be omitted if the first thing inside it is not a space character, comment, <script> element or <style> element. The end tag may be omitted if the body element has contents or has a start tag, and is not immediately followed by a comment.

<h3>Working Example</h3>

    <!DOCTYPE HTML>
    <html>
     <head>
      <title>Online or offline?</title>
      <script>
       function update(online) {
         document.getElementById('status').textContent =
           online ? 'Online' : 'Offline';
       }
      </script>
     </head>
     <body ononline="update(true)"
           onoffline="update(false)"
           onload="update(navigator.onLine)">
      <p>You are: <span id="status">(Unknown)</span></p>
     </body>
    </html>

<h3>References</h3>
https://developer.mozilla.org/en/docs/Web/HTML/Element/body
<br>
https://www.w3.org/TR/html5/sections.html#the-body-element

<h3>Point of Contact</h3>
Niranjan Thrineshwar <br>
nthrineshwar@deloitte.com <br>
9663770742
