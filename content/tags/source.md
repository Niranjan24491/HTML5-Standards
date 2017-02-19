+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/span"
prev = "/tags/select"
title = "source"
toc = true
weight = 86

+++

<h3>Standard Definition</h3>
        The HTML <source> element specifies multiple media resources for either the <picture>, the <audio> or the <video> element

<h3>Need for this tag</h3>
    It is an empty element. It is commonly used to serve the same media content in multiple formats supported by different browsers.

<h3>Global attributes</h3>

1. The source element allows authors to specify multiple alternative media resources for media elements. It does not represent anything on its own.

2. The src attribute gives the address of the media resource. The value must be a valid non-empty URL potentially surrounded by spaces. This attribute must be present.

NOTE: Dynamically modifying a source element and its attribute when the element is already inserted in a video or audio element will have no effect. To change what is playing, just use the src attribute on the media element directly, possibly making use of the canPlayType() method to pick from amongst available resources. Generally, manipulating source elements manually after the document has been parsed is an unnecessarily complicated approach.

3. The type attribute gives the type of the media resource, to help the user agent determine if it can play this media resource before fetching it. If specified, its value must be a valid MIME type. The codecs parameter, which certain MIME types define, might be necessary to specify exactly how the resource is encoded. [RFC4281]

<h3>Advantages of this tag</h3>

  1. It gives your users a pleasant experience to watch videos as they don’t have to download any additional plugins.

<h3>Working Example</h3>

        <video controls>
        <source src="foo.webm" type="video/webm">
        <source src="foo.ogg" type="video/ogg">
        <source src="foo.mov" type="video/quicktime">
        I'm sorry; your browser doesn't support HTML5 video.
        </video>

<h3>References</h3>
https://dev.w3.org/html5/spec-preview/the-source-element.html

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/source

<h3>Point of Contact</h3>
Niranjan Thrineshwar
