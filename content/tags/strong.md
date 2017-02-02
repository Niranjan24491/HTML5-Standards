+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/sub"
prev = "/tags/span"
title = "strong"
toc = true
weight = 88

+++

<h3>Standard Definition</h3>
  The HTML <strong> element gives text strong importance, and is typically displayed in bold.

  <h3>Bold vs. Strong</h3>

  It is often confusing to new developers why there are so many ways to express the same thing on a rendered website. Bold and Strong are perhaps one of the most common. Why use <strong></strong> vs <b></b>? You have to type a whole lot more with strong and it produces the exact same result, right?

  Perhaps not; strong is a logical state, and bold is a physical state. Logical states separate presentation from the content, and by doing so allow for it to be expressed in many different ways. Perhaps instead of rendering some text as bold you want to render it red, or a different size, or underlined, or whatever. It makes more sense to change the presentational properties of strong than it does bold. This is because bold is a physical state; there is no separation of presentation and content, and making bold do anything other than bold text would be confusing and illogical.

  It is important to note that <b></b> does have other uses, when one wants to draw attention without increasing importance.

  <h3>Emphasis vs. Strong</h3>

  While in HTML4, Strong simply indicated a stronger emphasis, in HTML5, the element is described as representing "strong importance for its contents." This is an important distinction to make. While Emphasis is used to change the meaning of a sentence ("I love carrots" vs. "I love carrots"), Strong is used to give portions of a sentence added importance (e.g., "Warning! This is very dangerous.") Both Strong and Emphasis can be nested to increase the relative degree of importance or stress emphasis, respectively.

<h3>Working Example</h3>

        <p>When doing x it is <strong>imperative</strong>
         to do y before proceeding.</p>s

<h3>References</h3>

  https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong

  http://stackoverflow.com/questions/271743/whats-the-difference-between-b-and-strong-i-and-em

<h3>Point of Contact</h3>
