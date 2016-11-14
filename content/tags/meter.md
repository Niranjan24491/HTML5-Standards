+++

The Meter element represents a scalar measurement within a known range, or a fractional value; for example disk usage, the relevance of a query result, or the fraction of a voting population to have selected a particular candidate. This is also known as a gauge.

The Meter element uses the phrasing content model which means it can contain the text of the document, along with the elements that mark up that text, but there must be no (additional) Meter element among its descendants.

Meter element can have 6 more attributes:
<ol>
<li><b>Value:</b> A floating point number that represents the current value of the measured range.</li>
  <li><b>Min:</b> Indicates the lower bound of the measured range.</li>
  <li><b>Max:</b> Indicates the upper bound of the measured range.</li>
  <li><b>Low:</b> It represents the upper bound of the low end of the measured range.</li>
  <li><b>High:</b> t represents the lower bound of the high end of the measured range.</li>
  <li><b>Optimum:</b> This attribute indicates the optimum value and must be within the range of min and max values.</li>
</ol>

<h3>Working Example</h3>

    <meter min="0" low="10" optimum="50" high="90" max="100"></meter>

<h3>Need for this tag</h3>
Use the meter element to measure data within a given range (a gauge).

<h3>Disadvantage of this tag</h3>
<ol>
  <li>The browser support for Meter elements is minimal</li>
  <li>There is no explicit way to specify units in the meter element</li>
</ol>

<h3>Advantages of this tag</h3>
<ol>
  <li>By Meter tag we can generate live graphs and charts easily</li>
</ol>

<h3>References</h3>
https://css-tricks.com/html5-meter-element/
<br/>
http://html5doctor.com/measure-up-with-the-meter-tag/

<h3>Point of Contact</h3>
Gaurav Sharma <br>
gasharma@deloitte.com