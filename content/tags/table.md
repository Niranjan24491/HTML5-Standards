+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/tbody"
prev = "/tags/sup"
title = "table"
toc = true
weight = 5

+++

The HTML Table Element <span class='tag-span'>&lt;table&gt;</span> represents tabular data - i.e., information expressed via a two dimensional data table.

<h3>Need for this tag</h3>

<p>To formulate tabular layout.</p>

{{% notice note %}}
  <span class='tag-span'>&lt;table&gt;</span> aren't really designed to be used as a way to position elements. For structuring your HTML layout, use floating elements instead of <span class='tag-span'>&lt;table&gt;</span>.<br>
  However, HTML emails are an exception where tables are still commonly used for layout purposes. The reason for this is poor CSS support in popular email clients.
{{% /notice %}}

<h3>Disadvantages of this tag</h3>

<ul>
  <li>Web crawler don't always read tables very well so they can negatively affect SEO.</li>

  <li>Tables need to be completely downloaded before they are displayed and that can leave visitors staring at a blank screen resulting bad user experience</li>

  <li>For disabled users, those who use screen readers will find it harder to jump from section to section</li>

</ul>

<h3>Advantages of this tag</h3>

<ul>
  <li>Tables provide layout rigidity and inhibit layout flexibility. Rigidity because the columns in a table can never break.</li>

  <li>Tables make it easier to display tabular data.</li>
</ul>

<h3>Working Example</h3>

    <table>
      <tr>
        <td>...</td>
        <td>...</td>
      </tr>
      <tr>
        <td>...</td>
        <td>...</td>
      </tr>
    </table>

<h3>References</h3>

[MDN](https://developer.mozilla.org/en/docs/Web/HTML/Element/table)
<br>
[W3C](https://www.w3.org/TR/html5/tabular-data.html)


<h3>Point of Contact</h3>
Abhishek Jha
