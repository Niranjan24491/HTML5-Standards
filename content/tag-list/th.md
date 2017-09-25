+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/thead"
prev = "/tags/tfoot"
title = "th"
toc = true
weight = 108

+++

The HTML <span class='tag-span'>&lt;th&gt;</span> tag is used to designate a cell that is a header for a group of cells within a table.

<h3>Need for this tag</h3>

The <span class='tag-span'>&lt;th&gt;</span> tag can store information about a set of rows or columns.

<h3>Advantages of this tag</h3>

Table cells may contain two types of information: header information and data. This distinction enables user agents to render header and data cells distinctly, even in the absence of style sheets. For example, visual user agents may present header cell text with a bold font. Speech synthesizers may render header information with a distinct voice inflection.

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

<h3>References</h3>

[MDN](https://developer.mozilla.org/en/docs/Web/HTML/Element/th)
<br>
[Quackit](http://www.quackit.com/html/tags/html_th_tag.cfm)
