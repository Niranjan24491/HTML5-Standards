+++
date = "2016-10-01T00:44:41+05:30"
next = "/tags/aside"
prev = "/tags/area"
title = "article"
toc = true
weight = 5

+++

<p>The <span class='tag-span'>&lt;article&gt;</span> element represents a complete, or self-contained, composition in a document, page, application, or site. This could be a magazine, newspaper, technical or scholarly article, an essay or report, a blog or other social media post.</p>

<p>A general rule is that the article element is appropriate only if the element’s contents would be listed explicitly in the document’s outline. Each article should be identified, typically by including a heading(h1-h4 element) as a child of the article element.</p>

<h3>Need for this tag</h3>

<p>Assistive Technology may convey the semantics of the article to users. This information can provide a hint to users as to the type of content. For example the role of the element, which in this case matches the element name "article", can be announced by screen reader software when a user navigates to an article element. User Agents may also provide methods to navigate to article elements.</p>

<p>When article elements are nested, the inner article elements represent articles that are in principle related to the contents of the outer article. For instance, a blog entry on a site could consist of summaries of other blog entries in article elements nested within the article element for the blog entry.</p>

<p>Author information associated with an article element (q.v. the address element) does not apply to nested article elements.</p>

<h3>Advantages of this tag</h3>

<ol>
  <li>Will help in Search Engine Optimization(SEO) by following the HTML standards</li>
  <li>Provides semantic meaning to the HTML page</li>
</ol>

<h3>Working Example</h3>

    <article>
      <header>
        <h2>The Very First Rule of Life</h2>
        <p><time datetime="2016-02-28">3 days ago</time></p>
      </header>
      <p>If there’s a microphone anywhere near you, assume it’s hot and
      sending whatever you’re saying to the world. Seriously.</p>
      <p>...</p>
      <footer>
        <a href="?comments=1">Show comments...</a>
      </footer>
    </article>

<h3>The difference between 	&lt;article&gt; and &lt;section&gt;</h3>

<p>There’s been a lot of confusion over the difference (or perceived lack of a difference) between the &lt;article&gt; and &lt;section&gt; elements in HTML5. The &lt;article&gt; element is a specialised kind of &lt;section&gt; it has a more specific semantic meaning than &lt;section&gt; in that it is an independent, self-contained block of related content. We could use &lt;section&gt;, but using &lt;article&gt; gives more semantic meaning to the content.</p>

<p>By contrast &lt;section&gt; is only a block of related content, and &lt;div&gt; is only a block of content. To decide which of these three elements is appropriate, choose the first suitable option:</p>

<ul>
  <li>Would the content would make sense on its own in a feed reader? If so use &lt;article&gt;</li>
  <li>Is the content related? If so use &lt;section&gt;</li>
  <li>Finally if there’s no semantic relationship use &lt;div&gt;</li>
</ul>

<h3>References</h3>
https://developer.mozilla.org/en/docs/Web/HTML/Element/article
<br>
http://w3c.github.io/html/sections.html#elementdef-article
<br>
http://html5doctor.com/the-article-element/

<h3>Point of Contact</h3>
<p>Niranjan Thrineshwar</p>
