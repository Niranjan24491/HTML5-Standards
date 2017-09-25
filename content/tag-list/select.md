+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/source"
prev = "/tags/section"
title = "select"
toc = true
weight = 85

+++

The HTML <span class='tag-span'>&lt;select&gt;</span> element represents a control that provides a menu of options.

<h3>Need for this tag</h3>
This element is used in conjunction with the <span class='tag-span'>&lt;option&gt;</span> element to produce a list of options that the user can choose from.

<h3>Global attributes</h3>

autofocus
  This attribute lets you specify that a form control should have input focus when the page loads, unless the user overrides it, for example by typing in a different control. Only one form element in a document can have the autofocus attribute, which is a Boolean.

disabled
  This Boolean attribute indicates that the user cannot interact with the control. If this attribute is not specified, the control inherits its setting from the containing element, for example fieldset; if there is no containing element with the disabled attribute set, then the control is enabled.

form HTML5
  The form element that the select element is associated with (its "form owner"). If this attribute is specified, its value must be the ID of a form element in the same document. This enables you to place select elements anywhere within a document, not just as descendants of their form elements.

multiple
  This Boolean attribute indicates that multiple options can be selected in the list. If it is not specified, then only one option can be selected at a time.

name
  The name of the control.

required HTML5
  A Boolean attribute indicating that an option with a non-empty string value must be selected.

size
  If the control is presented as a scrolled list box, this attribute represents the number of rows in the list that should be visible at one time. Browsers are not required to present a select element as a scrolled list box. The default value is 0.


<h3>Working Example</h3>

      <!-- The second value will be selected initially -->
      <select name="select">
      <option value="value1">Value 1</option>
      <option value="value2" selected>Value 2</option>
      <option value="value3">Value 3</option>
      </select>

Select any value from below.
<select name="select">
<option value="value1">Value 1</option>
<option value="value2" selected>Value 2</option>
<option value="value3">Value 3</option>
</select>

<h3>References</h3>

[Quackit](http://www.quackit.com/html_5/tags/html_select_tag.cfm)
<br>
[MDN](https://developer.mozilla.org/en/docs/Web/HTML/Element/select)
