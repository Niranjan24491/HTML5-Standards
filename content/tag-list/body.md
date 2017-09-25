+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/button"
prev = "/tags/blockquote"
title = "body"
toc = true
weight = 12

+++

The HTML <span class='tag-span'>&lt;body&gt;</span> Element represents the content of an HTML document. There can be only one <span class='tag-span'>&lt;body&gt;</span> element in a document.

<h3>Need for this tag</h3>
The start tag may be omitted if the first thing inside it is not a space character, comment, <span class='tag-span'>&lt;script&gt;</span> element or <span class='tag-span'>&lt;style&gt;</span> element. The end tag may be omitted if the body element has contents or has a start tag, and is not immediately followed by a comment.

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
[MDN](https://developer.mozilla.org/en/docs/Web/HTML/Element/body)
<br>
[W3C](https://www.w3.org/TR/html5/sections.html#the-body-element)
