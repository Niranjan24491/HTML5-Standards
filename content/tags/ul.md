+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/var"
prev = "/tags/track"
title = "ul"
toc = true
weight = 123

+++

<p>The HTML <span class='tag-span'>&lt;ul&gt;</span> element (or HTML Unordered List Element) represents an unordered list of items, namely a collection of items that do not have a numerical ordering, and their order in the list is meaningless. Typically, unordered-list items are displayed with a bullet, which can be of several forms, like a dot, a circle or a squared.</p>

<h3>Need for this tag</h3>

<p>Specifying lists of information in which changing the order of the items would not change the meaning of list.</p>

<h3>Disadvantages of this tag</h3>

<p>The HTML <span class='tag-span'>&lt;ul&gt;</span> element is widely used for navigation list, rather <span class='tag-span'>&lt;div&gt;</span>/<span class='tag-span'>&lt;span&gt;</span> or <span class='tag-span'>&lt;nav&gt;</span> should be used.</p>

<p>While tabbing through the site having many lists, screen readers can't give any clue as to where we are on the page and no information other than "List, 10 items. List, 6 items..." will be available. With <span class='tag-span'>&lt;div&gt;</span> and <span class='tag-span'> &lt;span&gt;</span> this wont be case as they immediately make content available to the screen readers.</p>

<h3>Advantages of this tag</h3>

<p>It provides semantic correctness. HTML has the ability to express lists of things, and it helps the Google robot, screen readers to identify that the information is a list, and not just "something" that is some text inside an arbitrary element.</p>

<h3>Working Example</h3>

    <ul>
      <li>First item</li>
      <li>Second item</li>
      <li>Third item</li>
    </ul>

<h3>Difference between <span class='tag-span'>&lt;ul&gt;</span> and <span class='tag-span'> &lt;ol&gt;</span></h3>

<p> The <span class='tag-span'>&lt;ul&gt;</span> and <span class='tag-span'>&lt;ol&gt;</span> elements both represent a list of items. They differ in that, with the <span class='tag-span'> &lt;ol&gt;</span> element, the order is meaningful. As a rule of thumb to determine which one to use, try changing the order of the list items; if the meaning is changed, the <span class='tag-span'> &lt;ol&gt;</span> element should be used, otherwise you can use <span class='tag-span'>&lt;ul&gt;</span>.</p>


<h3>References</h3>

[MDN](https://developer.mozilla.org/en/docs/Web/HTML/Element/ul)
<br>
[W3C](https://www.w3.org/TR/html-markup/ul.html)

<h3>Point of Contact</h3>
Abhishek Jha
