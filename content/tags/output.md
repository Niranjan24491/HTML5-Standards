+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/p"
prev = "/tags/option"
title = "output"
toc = true
weight = 67

+++

The output element represents the result of a calculation..
There are many ways to use this tag.

<ol>
  <li>By using the new-in-HTML5 number input type and the parseInt JavaScript function to convert the input strings to integers</li>

	<form onsubmit="return false" oninput="o.value = parseInt(a.value) + parseInt(b.value)">
    <input name="a" type="number" step="any"> +
    <input name="b" type="number" step="any"> =
    <output name="o"></output>
  	</form>

<li>By using <b>for</b> attribute to the <b>output</b> and IDs to each of the associated input's</li>

      <form onsubmit="return false" oninput="o.value = parseInt(a.value) + parseInt(b.value)">
        <input name="a" id="a" type="number" step="any"> +
        <input name="b" id="b" type="number" step="any"> =
        <output name="o" for="a b"></output>
      </form>

<li>By using <b>valueAsNumber</b> property of JavaScript input objects</li>

    <form onsubmit="return false" oninput="o.value = a.valueAsNumber + b.valueAsNumber">
      <input name="a" id="a" type="number" step="any"> +
      <input name="b" id="b" type="number" step="any"> =
      <output name="o" for="a b"></output>
    </form>
</ol>

<h3>Need for this tag</h3>
We can use <b>output</b> to show the results of a calculations.   

<h3>Disadvantage of this tag</h3>
<ol>
  <li>Still there are few browsers which are not Supporting</li>
  <li>This tag will not work for few languages, German or Swedish, where the input and the output should use a decimal comma instead of a decimal point</li>
</ol>

<h3>Advantages of this tag</h3>
<ol>
  <li>Showing calculations on webpage will be easy with this tag</li>
</ol>

<h3>References</h3>
http://html5doctor.com/the-output-element/

<h3>Point of Contact</h3>
Gaurav Sharma <br>
gasharma@deloitte.com
