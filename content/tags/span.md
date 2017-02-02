+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/strong"
prev = "/tags/source"
title = "span"
toc = true
weight = 87

+++

<h3>Standard Definition</h3>

    The HTML <span> element is a generic inline container for phrasing content, which does not inherently represent anything

<h3>Need for this tag</h3>

    It can be used to group elements for styling purposes (using the class or id attributes), or because they share attribute values, such as lang. It should be used only when no other semantic element is appropriate. <span> is very much like a <div> element, but <div> is a block-level element whereas a <span> is an inline element.

<h3>Disadvantages of this tag</h3>

  <ul>
    <li>A span is an inline element, and must only contain text content or nested inline or phrase elements. It shouldn’t be used to surround block-level elements—a usage that’s often seen in Content Management Systems which attempt to apply styling to almost any element by throwing a span around it.</li>

    <li>A note of caution: it’s not unheard of for people to go crazy with spans, using them all over the place. span-itis is a bad practice—it’s just as bad as a dose of div-itis. Be sure to check that you’re using the span element appropriately. For example, if you find yourself applying spans like this, you’re in trouble.</li>
  </ul>

<h3>Advantages of this tag</h3>
  <ul>
  Using the span, we can hang a styled class on a chunk of text inside a paragraph to transform it on the display. Let’s say we want to create a class that makes our text orange and bold. Easy enough:
  </ul>
          .text_emphasis {
            font-weight: bold;
            color: #ff6600;
            }
  Now we use a span element to style the words we want so emphasized:

  <p>I have a <span class="text_emphasis>really terrible</span> headache right now.

<h3>Working Example</h3>

        <p><span>Some text</span></p>

<h3>References</h3>

  https://www.sitepoint.com/web-foundations/span-html-element/

  https://developer.mozilla.org/en/docs/Web/HTML/Element/span

<h3>Point of Contact</h3>
Niranjan Thrineshwar
