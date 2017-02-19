+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/strong"
prev = "/tags/source"
title = "span"
toc = true
weight = 87

+++
    The HTML <span class='tag-span'>&lt;span&gt;</span> element is a generic inline container for phrasing content, which does not inherently represent anything.

<h3>Need for this tag</h3>

It can be used to group elements for styling purposes (using the class or id attributes). It should be used only when no other semantic element is appropriate. <span class='tag-span'>&lt;span&gt;</span> is very much like a <span class='tag-span'>&lt;div&gt;</span> element, but <span class='tag-span'>&lt;div&gt;</span> is a block-level element whereas a <span class='tag-span'>&lt;span&gt;</span> is an inline element.

<h3>Disadvantages of this tag</h3>

<ul>
  <li>A <span class='tag-span'>&lt;span&gt;</span> is an inline element, and must only contain text content or nested inline or phrase elements. It shouldn’t be used to surround block-level elements—a usage that’s often seen in Content Management Systems which attempt to apply styling to almost any element by throwing a span around it.</li>

  <li>A note of caution: it’s not unheard of for people to go crazy with <span class='tag-span'>&lt;span&gt;</span>, using them all over the place. Be sure to check that you’re using the <span class='tag-span'>&lt;span&gt;</span> element appropriately. </li>
</ul>

<h3>Advantages of this tag</h3>

<ul>
  <li>Using the <span class='tag-span'>&lt;span&gt;</span>, we can hang a styled class on a chunk of text inside a paragraph to transform it on the display.</li>
</ul>

<h3>Working Example</h3>

        <p>I have a <span class="text_emphasis">really terrible</span> headache right now.</p>
        
        .text_emphasis {
          font-weight: bold;
          color: #ff6600;
        }

<p>I have a <span class="text_emphasis">really terrible</span> headache right now.</p>

<h3>References</h3>

[MDN](https://developer.mozilla.org/en/docs/Web/HTML/Element/span)
<br>
[SitePoint](https://www.sitepoint.com/web-foundations/span-html-element/)
