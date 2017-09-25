+++
date = "2016-10-01T00:44:41+05:30"
next = "/tags/aside"
prev = "/tags/area"
title = "article"
toc = true
weight = 5

+++

<p>The <span class='tag-span'>&lt;article&gt;</span> element represents a complete, or self-contained, composition in a document. This could be a magazine, newspaper, technical or scholarly article, an essay or report, a blog or other social media post.</p>

{{% notice tip %}}
  A general rule is that the article element is appropriate only if the element’s contents would be listed explicitly in the document’s outline. Each article should be identified, typically by including a heading(h1-h4 element) as a child of the article element.
{{% /notice %}}

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
    </article>

<article>
  <header>
    <h4>The Very First Rule of Life</h4>
    <p><time datetime="2016-02-28">3 days ago</time></p>
  </header>
  <p>If there’s a microphone anywhere near you, assume it’s hot and
  sending whatever you’re saying to the world. Seriously.</p>
  <p>...</p>
</article>

<h3>The difference between <span class='tag-span'>article</span> and <span class='tag-span'>section</span> and <span class='tag-span'>div</span></h3>

<p>There’s been a lot of confusion over the difference (or perceived lack of a difference) between <span class='tag-span'>article</span>, <span class='tag-span'>section</span> and <span class='tag-span'>div</span> elements in HTML5. </p>

<p>The <span class='tag-span'>article</span> element is a specialized kind of <span class='tag-span'>section</span>. It has a more specific semantic meaning than <span class='tag-span'>section</span> in that it is an independent, self-contained block of related content. We could use <span class='tag-span'>section</span>, but using article gives more semantic meaning to the content.</p>

<p>By contrast <span class='tag-span'>section</span>; is only a block of related content, and <span class='tag-span'>div</span> is only a block of content. To decide which of these three elements is appropriate, choose the first suitable option:</p>

<ul>
  <li>Would the content would make sense on its own in a feed reader? If so use <span class='tag-span'>article</span></li>
  <li>Is the content related? If so use <span class='tag-span'>section</span></li>
  <li>Finally if there’s no semantic relationship use <span class='tag-span'>div</span></li>
</ul>

<h3>References</h3>
[MDN](https://developer.mozilla.org/en/docs/Web/HTML/Element/article)
<br>
[W3c](http://w3c.github.io/html/sections.html#elementdef-article)
<br>
[HTML5Doctor](http://html5doctor.com/the-article-element/)
