+++
date = "2016-10-01T00:45:09+05:30"
next = "/tags/iframe"
prev = "/tags/hr"
title = "html"
toc = true
weight = 41

+++

The web pages you view, including this one, are written in Hypertext Markup Language using HTML tags. Think of HTML as the under-the-hood code that controls how a web page looks and functions. When you learn any new language, you begin with simple phrases and build from there. Learning about HTML is no different

<h3>Need for this tag</h3>
The <html> tag tells the browser that this is an HTML document.
The <html> tag represents the root of an HTML document.
The <html> tag is the container for all other HTML elements (except for the <!DOCTYPE> tag).

<h3>Advantages of this tag</h3>
HTML5 allows a new attribute to be passed along with HTML tag i.e. the manifest attributes.
he manifest attribute specifies the location of the document's cache manifest.

HTML5 introduces application cache, which means that a web application is cached, and accessible without an internet connection.

Application cache gives an application three advantages:

Offline browsing - users can use the application when they're offline
Speed - cached resources load faster
Reduced server load - the browser will only download updated/changed resources from the server
The manifest attribute should be included on every page of your web application that you want cached.

The manifest file is a simple text file that lists the resources the browser should cache for offline access.

<h3>Working Example</h3>

    <!DOCTYPE HTML>
    <html manifest="demo.appcache">
      <head>
      <title>Title of the document</title>
      </head>
      <body>
      The content of the document......
      </body>
    </html>

<h3>References</h3>
https://www.tutorialspoint.com/html/index.htm
<br>
http://webdesign.about.com/od/beginninghtmlglossary/g/html_tag.htm

<h3>Point of Contact</h3>
Niranjan Thrineshwar
nthrineshwar@deloitte.com
9663770742
