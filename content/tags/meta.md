+++
date = "2016-10-01T00:45:09+05:30"
next = "/tags/meter"
prev = "/tags/menuitem"
title = "meta"
toc = true
weight = 5

+++

The META elements can be used to include name/value pairs describing properties of the HTML document, such as author, expiry date, a list of keywords, document author etc.

The <meta> tag is used to provide such additional information. This tag is an empty element and so does not have a closing tag but it carries information within its attributes.

You can include one or more meta tags in your document based on what information you want to keep in your document but in general, meta tags do not impact physical appearance of the document so from appearance point of view, it does not matter if you include them or not.

<h3>Need for this tag</h3>
You can use <meta> tag to specify important keywords related to the document and later these keywords are used by the search engines while indexing your webpage for searching purpose.

<h3>Advantages of this tag</h3>
We can specify the following attributes for meta tag which help in SEO.
<ul>
  <li>Document Description: You can use <meta> tag to give a short description about the document. This again can be used by various search engines while indexing your webpage for searching purpose.</li>
  <li>Document Revision Date: You can use <meta> tag to give information about when last time the document was updated. This information can be used by various web browsers while refreshing your webpage.</li>
  <li>Document Refreshing: A <meta> tag can be used to specify a duration after which your web page will keep refreshing automatically.</li>
  <li>Page Redirection: You can use <meta> tag to redirect your page to any other webpage. You can also specify a duration if you want to redirect the page after a certain number of seconds.</li>
  <li>Setting Cookies: Cookies are data, stored in small text files on your computer and it is exchanged between web browser and web server to keep track of various information based on your web application need. You can use <meta> tag to store cookies on client side and later this information can be used by the Web Server to track a site visitor.</li>
  <li>Setting Author Name</li>
  <li>Specify Character Set</li>
</ul>

<h3>Working Example</h3>

    <!DOCTYPE html>
    <html>
      <head>
      <title>Meta Tags Example</title>
      <meta name="keywords" content="HTML, Meta Tags, Metadata" />
      <meta name="description" content="Learning about Meta Tags." />
      <meta name="revised" content="HTML5, 3/7/2017" />
      <meta http-equiv="cookie" content="userid=xyz; expires=Wednesday, 08-Aug-15 23:59:59 GMT;" />
      <meta name="author" content="Mahnaz Mohtashim" />
      <meta http-equiv="Content-Type" content="text/html; charset=Big5" />
      <meta http-equiv="refresh" content="5; url=https://www.tutorialspoint.com" />
      </head>
      <body>
        <p>Hello HTML5!</p>
      </body>
    </html>

<h3>References</h3>
https://www.tutorialspoint.com/html/html_meta_tags.htm

<h3>Point of Contact</h3>
Niranjan Thrineshwar
nthrineshwar@deloitte.com
9663770742
