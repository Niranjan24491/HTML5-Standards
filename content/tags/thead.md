+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/time"
prev = "/tags/th"
title = "thead"
toc = true
weight = 5

+++

The <span class='tag-span'>&lt;thead&gt;</span> tag is used to group the header content in an HTML table. The <span class='tag-span'>&lt;thead&gt;</span> element should be used in conjunction with the <span class='tag-span'>&lt;tbody&gt;</span> and <span class='tag-span'>&lt;tfoot&gt;</span> elements to specify each part of a table (header, footer,  body).

<h3>Need for this tag</h3>

<p>The <span class='tag-span'>&lt;thead&gt;</span> element can encapsulate an entire row (or rows) to designate them as the Table Header.</p>

<h3>Advantages of this tag</h3>

<ul>
  <li>The <span class='tag-span'>&lt;thead&gt;</span>, <span class='tag-span'>&lt;tbody&gt;</span> ,<span class='tag-span'>&lt;tfoot&gt;</span> elements in HTML are used to group table rows into logical sections based on their content. There are two main reasons you'd want to do this:

  <ol>
    <li>They allow you to add semantics to your table.
    <li>They allow you to style the head and the foot of the table without introducing redundant classes/ids</li>
  </ol>

  <li>This division enables user agents to support scrolling of table bodies independently of the table head and foot.</li>

  <li> When long tables are printed, the table head and foot information may be repeated on each page that contains table data.</li>

</ul>

{{% notice note %}}
  You can actually code <span class='tag-span'>&lt;thead&gt;</span>, <span class='tag-span'> &lt;tfoot&gt;</span>, <span class='tag-span'>&lt;tbody&gt;</span> out of order and they will appear in the right place on the table. While obscure, this is one of advantage of table related semantics tag.
{{% /notice %}}

<h3>Working Example</h3>

    <table>
      <thead>
        <tr>
          <th>Month</th>
          <th>Expense</th>
          <th>Savings</th>
        </tr>
      </thead>
      <tfoot>
        <tr>
          <td>Sum</td>
          <td>Rs.18000</td>
          <td>Rs.8000</td>
        </tr>
      </tfoot>
      <tbody>
        <tr>
          <td>January</td>
          <td>Rs.6000</td>
          <td>Rs.2000</td>
        </tr>
        <tr>
          <td>February</td>
          <td>Rs.5000</td>
          <td>Rs.3000</td>
        </tr>
        <tr>
          <td>March</td>
          <td>Rs.5000</td>
          <td>Rs.3000</td>
        </tr>
      </tbody>
    </table>

<table>
  <thead>
    <tr>
      <th>Month</th>
      <th>Expense</th>
      <th>Savings</th>
    </tr>
  </thead>
  <tfoot>
    <tr>
      <th>Sum</th>
      <td>Rs.16000</td>
      <td>Rs.8000</td>
    </tr>
  </tfoot>
  <tbody>
    <tr>
      <td>January</td>
      <td>Rs.6000</td>
      <td>Rs.2000</td>
    </tr>
    <tr>
      <td>February</td>
      <td>Rs.5000</td>
      <td>Rs.3000</td>
    </tr>
    <tr>
      <td>March</td>
      <td>Rs.5000</td>
      <td>Rs.3000</td>
    </tr>
  </tbody>
</table>

<h3>References</h3>

[MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/thead)
<br>
[HTMLHELP](http://htmlhelp.com/reference/html40/tables/thead.html)

<h3>Point of Contact</h3>
Abhishek Jha
