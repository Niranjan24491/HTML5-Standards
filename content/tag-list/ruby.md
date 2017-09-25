+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/section"
prev = "/tags/progress"
title = "ruby"
toc = true
weight = 82

+++

Represents a container for base text and ruby text � small annotations used for phonetic readings in languages such as Japanese and Chinese.

These are the elements used in creating ruby text in HTML5:
<ol>
  <li><b>Ruby:</b> An inline element that contains base text with ruby annotations</li>
  <li><b>Rt:</b> Ruby text, coming after the base text it defines</li>
  <li><b>Rp:</b> ruby parentheses, an element used to wrap opening and closing parentheses around <b>rt</b> ruby text. These are for user agents that don�t support ruby text, so that it makes sense when displayed inline. Browsers that support <b>ruby</b> hide <b>rp</b> via {display:none;}.</li>
</ol>

<h3>Working Example</h3>

	<ruby>
	? <rt> ??` </rt>
	</ruby>

<h3>Need for this tag</h3>
A ruby annotation is a small extra text, attached to the main text to indicate the pronunciation or meaning of the corresponding characters. This kind of annotation is often used in Japanese publications.   

<h3>Disadvantage of this tag</h3>
<ol>
  <li>There is no browsers support the CSS3 Ruby module yet</li>
</ol>

<h3>Advantages of this tag</h3>
<ol>
  <li>Due to this tag we can add annotations used for phonetic readings</li>
</ol>

<h3>References</h3>
http://html5doctor.com/ruby-rt-rp-element/

<h3>Point of Contact</h3>
Gaurav Sharma <br>
gasharma@deloitte.com
