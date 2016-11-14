+++

MENU along with the Menuitem element will incorporate the new menu items as part of the native contextual menu. In the example below, we will add to our <body> a new context menu item named "Sample Item 1".

<h3>Working Example</h3>

	<body contextmenu="new-context-menu">
	<menu id="new-context-menu" type="context">
	    <menuitem>Sample Item 1</menuitem>
	</menu>
	</body>
    
When we view this example in the browser (at the moment, only in Firefox) you should see that the menuitem we declared is added at the very top of the list.

<h3>Adding Sub-menu and Icon</h3>
We can create sub-menus using Menuitem and also a new attribute called icon has been introduced making it possible to add an icon along side the menu. It’s worth noting that this attribute is only applicable within the <menuitem> element.

<h3>Working Example</h3>

    <menu id="demo-image" type="context">
        <menu label="Image Rotation">
            <menuitem icon="img/arrow-return-090.png">Rotate 90</menuitem>
            <menuitem icon="img/arrow-return-180.png">Rotate 180</menuitem>
            <menuitem icon="img/arrow-stop-180.png">Flip Horizontally</menuitem>
            <menuitem icon="img/arrow-stop-270.png">Flip Vertically</menuitem>
        </menu>
    </menu>

<h3>Need for this tag</h3>
MENUITEM Element is designed for creating sub-menu under Menu contextual, toolbar, and popup menus. It is very handy and is commonly used to create submenus in a web app.

<h3>Disadvantage of this tag</h3>
<ol>
  <li>The browser support for MENUITEM elements is minimal</li>
</ol>

<h3>Advantages of this tag</h3>
<ol>
  <li>The MENUITEM element makes it simple and straight forward for developers to add sub level in context menu items in an element</li>
</ol>

<h3>References</h3>
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/menu
<br>
https://webdesign.tutsplus.com/tutorials/introducing-the-html5-menu-and-menuitem-elements--cms-22269

<h3>Point of Contact</h3>
Gaurav Sharma <br>
gasharma@deloitte.com