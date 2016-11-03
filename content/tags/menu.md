+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/meta"
prev = "/tags/kbd"
title = "menu"
toc = true
weight = 5

+++

The HTML menu element represents a group of commands that a user can perform or activate. This includes both list menus, which might appear across the top of a screen, as well as context menus, such as those that might appear underneath a button after it has been clicked.

<h3>Need for this tag</h3>
MENU Element is designed for creating contextual, toolbar, and popup menus. It is very handy and is commonly used to create contextual menus and submenus in a web app.

<h3>Disadvantage of this tag</h3>
<ol>
  <li>The browser support for MENU elements is still limited and it’s difficult to guess how (if?) browsers will implement them and how they will look</li>
</ol>

<h3>Advantages of this tag</h3>
<ol>
  <li>The MENU element makes it simple and straight forward for developers to add context menu items in an element</li>
  <li>MENU element is useful for SEO purposes or web scrapers to differentiate the contents of the menu from the body content</li>
</ol>

<h3>Working Example</h3>

	<body contextmenu="new-context-menu">
	<menu id="new-context-menu" type="context">
	    <menuitem>Hello World</menuitem>
	</menu>
	</body>

<h3>References</h3>
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/menu
<br>
https://webdesign.tutsplus.com/tutorials/introducing-the-html5-menu-and-menuitem-elements--cms-22269

<h3>Point of Contact</h3>
Chirag Bhatia <br>
chibhatia@deloitte.com