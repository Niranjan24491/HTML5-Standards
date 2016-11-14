+++
date = "2016-10-01T00:44:53+05:30"
next = "/tags/ol"
prev = "/tags/meter"
title = "nav"
toc = true
weight = 5

+++

<p>The <span class='tag-span'>&lt;nav&gt;</span> element (HTML Navigation Element) represents a section of a page that links to other pages or to parts within the page: basically it is a section with navigation links. </p>

<h3>Need for this tag</h3>
  <ul>
    <li>We can encapsulate a group of links in a single semantic element and it looks organized.</li>

    <li>This information provide a hint to users as to the type of content. For example the role of the element, which in this case is "navigation", can be announced by screen reader software when a user navigates to an <span class='tag-span'>&lt;nav&gt;</span> element. </li>

    <li>Not all links of a document must be in a <span class='tag-span'>&lt;nav&gt;</span> element, it is intended only for major block of navigation links; in particular the <span class='tag-span'>&lt;footer&gt;</span> element often has a list of links that don't need to be in a <span class='tag-span'>&lt;nav&gt;</span> element. While a <span class='tag-span'>&lt;nav&gt;</span> can be used in such cases, it is usually unnecessary.</li>

    <li>A document may have several <span class='tag-span'>&lt;nav&gt;</span> elements, for example, one for site navigation and one for intra-page navigation.</li>
  </ul>

<h3>Advantages of this tag</h3>
<ul>
  <li>User agents, such as screen readers targeting disabled users, can use this element to determine whether to omit the initial rendering of this content. </li>

  <li>User Agents may also provide methods to navigate to <span class='tag-span'>&lt;nav&gt;</span> elements when a user navigates to an <span class='tag-span'>&lt;nav&gt;</span> element.
  </li>

  <li>A nav element doesn’t have to contain a list, it can contain other kinds of content as well.</li>
</ul>

<h3>Working Example</h3>

    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>

  <p>Below are a few examples of areas of the site in which you might consider using the <span class='tag-span'>&lt;nav&gt;</span> element.
    <ol>
      <li>Table of Contents: It is primary navigation for that particularly content</li>
      <li>Previous/next buttons or pagination: It is important to the overall structure and hierarchy of the site</li>
      <li>Search form: A search form is hugely important to the navigation of a site.</li>
      <li>Breadcrumbs: Although breadcrumbs are not always necessary and can be used when not applicable, a breadcrumb trail can be an important navigation aid.</li>
    </ol>
  </p>

<h3>The difference between 	<span class='tag-span'>&lt;nav&gt;</span> and <span class='tag-span'>&lt;menu&gt;</span></h3>

<p>If you aren’t aware there is another element that can confuse the issue in the HTML 5 specification – <span class='tag-span'>&lt;menu&gt;</span>. It have been noticed that some developers are using <span class='tag-span'>&lt;menu&gt;</span> element for navigation rather than <span class='tag-span'>&lt;nav&gt;</span> element. We thought it best to clarify that <span class='tag-span'>&lt;menu&gt;</span> is to be used for a list of commands and is an interactive element and more likely to be used exclusively in Web Applications.</p>

<h3>References</h3>
https://developer.mozilla.org/en/docs/Web/HTML/Element/nav
<br>
http://html5doctor.com/nav-element/

<h3>Point Of Contact</h3>
Abhishek Jha
