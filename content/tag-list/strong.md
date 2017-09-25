+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/sub"
prev = "/tags/span"
title = "strong"
toc = true
weight = 88

+++

  The HTML <span class='tag-span'>&lt;strong&gt;</span> element gives text strong importance, and is typically displayed in bold.

  <h3><span class='tag-span'>&lt;strong&gt;</span> vs. <span class='tag-span'>&lt;bold&gt;</span></h3>

  It is often confusing to new developers why there are so many ways to express the same thing on a rendered website. Bold and Strong are perhaps one of the most common. Why use <span class='tag-span'>&lt;strong&gt;</span> vs <span class='tag-span'>&lt;b&gt;</span>? You have to type a whole lot more with strong and it produces the exact same result, right?

  Perhaps not; <span class='tag-span'>&lt;strong&gt;</span> is a logical state, and <span class='tag-span'>&lt;bold&gt;</span> is a physical state. Logical states separate presentation from the content, and by doing so allow for it to be expressed in many different ways. Instead of rendering some text as bold you want to render it red, or a different size, or underlined, or whatever. It makes more sense to change the presentational properties of <span class='tag-span'>&lt;strong&gt;</span> than of <span class='tag-span'>&lt;bold&gt;</span>. This is because <span class='tag-span'>&lt;bold&gt;</span> is a physical state; there is no separation of presentation and content, and making <span class='tag-span'>&lt;bold&gt;</span> do anything other than bold text would be confusing and illogical.

  It is important to note that <span class='tag-span'>&lt;b&gt;</span> does have other uses, when one wants to draw attention without increasing importance.

  <h3><span class='tag-span'>&lt;strong&gt;</span> vs. <span class='tag-span'>&lt;emphasis&gt;</span></h3>

  While in HTML4, <span class='tag-span'>&lt;strong&gt;</span> simply indicated a stronger emphasis, in HTML5, <span class='tag-span'>&lt;strong&gt;</span> element is described as representing "strong importance for its contents." This is an important distinction to make. While <span class='tag-span'>&lt;emphasis&gt;</span> is used to change the meaning of a sentence, <span class='tag-span'>&lt;strong&gt;</span> is used to give portions of a sentence added importance (e.g., "Warning! This is very dangerous."). Both <span class='tag-span'>&lt;strong&gt;</span> and <span class='tag-span'>&lt;emphasis&gt;</span> can be nested to increase the relative degree of importance or stress emphasis, respectively.

<h3>Working Example</h3>

      <p>When doing x it is <strong>imperative</strong> to do y before proceeding.</p>

 <p>When doing x it is <strong>imperative</strong> to do y before proceeding.</p>

<h3>References</h3>

[MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong)
<br>
[StackOverflow](http://stackoverflow.com/questions/271743/whats-the-difference-between-b-and-strong-i-and-em)
