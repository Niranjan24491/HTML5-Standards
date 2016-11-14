+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/anchor"
prev = "/tags/abbreviation"
title = "address"
toc = true
weight = 2

+++

The HTML <span class='tag-span'>&lt;address&gt;</span> element is used for indicating an address, usually related to authorship of the current document, or a section of the document. If the tag applies to the body element, then it applies to the document as a whole.

<h3>Need for this tag</h3>

The <span class='tag-span'>&lt;address&gt;</span> is used to indicate authorship of document.

{{% notice note %}}
  The <span class='tag-span'>&lt;address&gt;</span> element must not be used to represent arbitrary addresses (e.g. postal addresses), unless those addresses are contact information for the section. To display postal addresses, simply use the <span class='tag-span'>&lt;p&gt;</span> element. Typically an <span class='tag-span'>&lt;address&gt;</span> element can be placed inside the <span class='tag-span'>&lt;footer&gt;</span> element of the current section, if any.
{{% /notice %}}

{{% notice tip %}}
  The <span class='tag-span'>&lt;address&gt;</span> element should not contain more information than the contact information, like a publication date (which belongs in a <span class='tag-span'>&lt;time&gt;</span> element).
{{% /notice %}}

<h3>Disadvantages of this tag</h3>
The <span class='tag-span'>&lt;address&gt;</span> element cannot contain
<span class='tag-span'>&lt;article&gt;</span>, <span class='tag-span'>&lt;aside&gt;</span>
<span class='tag-span'>&lt;nav&gt;</span>, <span class='tag-span'>&lt;section&gt;</span>
<span class='tag-span'>&lt;header&gt;</span>, <span class='tag-span'>&lt;footer&gt;</span>
<span class='tag-span'>&lt;hgroup&gt;</span>, <span class='tag-span'>&lt;h1&gt;</span>-
<span class='tag-span'>&lt;h6&gt;</span> or other <span class='tag-span'>&lt;address&gt;</span> elements.

<h3>Advantages of this tag</h3>

<ol>
  <li>Will help in Search Engine Optimization(SEO) by following the HTML standards</li>
  <li>Provides semantic meaning to the HTML page</li>
</ol>

<h3>Working Example</h3>

    <address>
        You can contact author at <a href="http://www.somedomain.com/contact">www.somedomain.com</a>.<br>
        If you see any bugs, please <a href="mailto:webmaster@somedomain.com">contact webmaster</a>.<br>
        You may also want to visit us:<br>
        Mozilla Foundation<br>
        1981 Landings Drive<br>
        Building K<br>
        Mountain View, CA 94043-0801<br>
        USA
    </address>

<address>
    You can contact author at <a href="http://www.somedomain.com/contact">www.somedomain.com</a>.<br>
    If you see any bugs, please <a href="mailto:webmaster@somedomain.com">contact webmaster</a>.<br>
    You may also want to visit us:<br>
    Mozilla Foundation<br>
    1981 Landings Drive<br>
    Building K<br>
    Mountain View, CA 94043-0801<br>
    USA
</address>

<h3>References</h3>
[MDN](https://developer.mozilla.org/en/docs/Web/HTML/Element/address)
<br>
[Quackit](http://www.quackit.com/html_5/tags/html_address_tag.cfm)

<h3>Point of Contact</h3>
Niranjan Thrineshwar <br>
nthrineshwar@deloitte.com <br>
9663770742
