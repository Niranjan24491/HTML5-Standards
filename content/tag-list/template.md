+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/textarea"
prev = "/tags/td"
title = "template"
toc = true
weight = 105

+++

The HTML <span class='tag-span'>&lt;template&gt;</span> element is a mechanism for holding client-side content that is not to be rendered when a page is loaded but may subsequently be instantiated during runtime using JavaScript.

<h3>Need for this tag</h3>

The HTML <span class='tag-span'>&lt;template&gt;</span> element provides a mechanism to define HTML markup fragments as prototypes that can be used to insert fragments of HTML code into your page multiple times. To use a template, it must be cloned and inserted into the DOM using JavaScript.

{{% notice note %}}
   While the parser does process the contents of the <span class='tag-span'>&lt;template&gt;</span> element while loading the page, it does so only to ensure that those contents are valid; the element's contents are not rendered, however.
{{% /notice %}}

<h3>Disadvantages of this tag</h3>

<ol>

  <li>Browser support for <span class='tag-span'>&lt;template&gt;</span> element may be limited for some time.</li>

  <li>To use <span class='tag-span'>&lt;template&gt;</span>, you need to use script to clone the template and insert it into the DOM. So, if JavaScript is turned off, <span class='tag-span'>&lt;template&gt;</span> element will be completely useless.</li>
</ol>

<h3>Advantages of this tag</h3>

<ol>

  <li>The <span class='tag-span'>&lt;template&gt;</span> tag provides native support for the concept of templating.</li>

  <li>The <span class='tag-span'>&lt;template&gt;</span> element used as a starting point for a particular application so that the format does not have to be recreated each time it is used.</li>

  <li> The <span class='tag-span'>&lt;template&gt;</span> element allows templating functionality with cleaner and simpler code.</li>

</ol>

<h3>Working Example</h3>

    <table id="producttable">
      <thead>
        <tr>
          <td>UPC_Code</td>
          <td>Product_Name</td>
        </tr>
      </thead>
      <tbody>
        <!-- existing data could optionally be included here -->
      </tbody>
    </table>

    <template id="productrow">
      <tr>
        <td class="record"></td>
        <td></td>
      </tr>
    </template>

<ul>
  <li>In the snippet above, first we have a table into which we will later insert content using JavaScript code. Then comes the template, which describes the structure of an HTML fragment representing a single table row.
  </li>

  <li>Now that the table has been created and the template defined, we use JavaScript to insert rows into the table, with each row being constructed using the template as its basis.</li>

  <li>The result is the original HTML table, with new rows appended to it via JavaScript,</li>
</ul>

<h3>References</h3>

[MDN](https://developer.mozilla.org/en/docs/Web/HTML/Element/template)
<br>
[HTML5Rock](https://www.html5rocks.com/en/tutorials/webcomponents/template/)
