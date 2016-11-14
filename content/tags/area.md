+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/article"
prev = "/tags/anchor"
title = "area"
toc = true
weight = 4

+++

The HTML <span class='tag-span'>&lt;area&gt;</span> element defines a hot-spot region on an image, and optionally associates it with a hypertext link. This element is used only within a <span class='tag-span'>&lt;map&gt;</span> element.

<h3>Global attributes</h3>

    alt - Replacement text for use when images are not available
    coords - Coordinates for the shape to be created in an image map
    download - Whether to download the resource instead of navigating to it, and its file name if so
    href - Address of the hyperlink
    hreflang - Language of the linked resource
    rel Relationship between the document containing the hyperlink and the destination resource
    shape - The kind of shape to be created in an image map
    target - Browsing context for hyperlink navigation
    type - Hint for the type of the referenced resource

The area element represents either a hyperlink with some text and a corresponding area on an image map, or a dead area on an image map.

An area element with a parent node must have a map element ancestor or a template element ancestor.

If the area element has an href attribute, then the area element represents a hyperlink. In this case, the alt attribute must be present. It specifies the text of the hyperlink. Its value must be text that, when presented with the texts specified for the other hyperlinks of the image map, and with the alternative text of the image, but without the image itself, provides the user with the same kind of choice as the hyperlink would when used without its text but with its shape applied to the image. The alt attribute may be left blank if there is another area element in the same image map that points to the same resource and has a non-blank alt attribute.

If the area element has no href attribute, then the area represented by the element cannot be selected, and the alt attribute must be omitted.

In both cases, the shape and coords attributes specify the area.

The shape attribute is an enumerated attribute. The following table lists the keywords defined for this attribute. The states given in the first cell of the rows with keywords give the states to which those keywords map.

<h3>Advantages of this tag</h3>
<ol>
  <li>Will help in Search Engine Optimization(SEO) by following the HTML standards</li>
  <li>Provides semantic meaning to the HTML page</li>
</ol>

<h3>Working Example</h3>

    <p>Please select a shape:
     <img src="shapes.png" usemap="#shapes" alt="Four shapes are available: a red hollow box, a green circle, a blue triangle, and a yellow four-pointed star.">
     <map name="shapes">
      <area shape=rect coords="50,50,100,100"> <!-- the hole in the red box -->
      <area shape=rect coords="25,25,125,125" href="red.html" alt="Red box.">
      <area shape=circle coords="200,75,50" href="green.html" alt="Green circle.">
      <area shape=poly coords="325,25,262,125,388,125" href="blue.html" alt="Blue triangle.">
      <area shape=poly coords="450,25,435,60,400,75,435,90,450,125,465,90,500,75,465,60" href="yellow.html" alt="Yellow star.">
     </map>
    </p>

<p>Please select a shape:
 <img src="shapes.png" usemap="#shapes" alt="Four shapes are available: a red hollow box, a green circle, a blue triangle, and a yellow four-pointed star.">
 <map name="shapes">
  <area shape=rect coords="50,50,100,100"> <!-- the hole in the red box -->
  <area shape=rect coords="25,25,125,125" href="red.html" alt="Red box.">
  <area shape=circle coords="200,75,50" href="green.html" alt="Green circle.">
  <area shape=poly coords="325,25,262,125,388,125" href="blue.html" alt="Blue triangle.">
  <area shape=poly coords="450,25,435,60,400,75,435,90,450,125,465,90,500,75,465,60" href="yellow.html" alt="Yellow star.">
 </map>
</p>

<h3>References</h3>
https://developer.mozilla.org/en/docs/Web/HTML/Element/area
<br>
https://www.w3.org/TR/html5/embedded-content-0.html#the-area-element

<h3>Point of Contact</h3>
Niranjan Thrineshwar <br>
nthrineshwar@deloitte.com <br>
9663770742
