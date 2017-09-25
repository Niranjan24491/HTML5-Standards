+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/span"
prev = "/tags/select"
title = "source"
toc = true
weight = 86

+++

The HTML <span class='tag-span'>&lt;source&gt;</span> element specifies media resources for either <span class='tag-span'>&lt;picture&gt;</span>, <span class='tag-span'>&lt;audio&gt;</span> or <span class='tag-span'>&lt;video&gt;</span> element.

<h3>Need for this tag</h3>

The <span class='tag-span'>&lt;source&gt;</span> element allows authors to specify multiple alternative media resources for media elements supported by different browsers. It does not represent anything on its own.

{{% notice note %}}
  The src attribute gives the address of the media resource. The value must be a valid non-empty URL potentially surrounded by spaces. This attribute must be present.<br><br>Dynamically modifying a source element and its attribute when the element is already inserted in a video or audio element will have no effect. To change what is playing, just use the src attribute on the media element directly, possibly making use of the canPlayType() method to pick from amongst available resources. Generally, manipulating source elements manually after the document has been parsed is an unnecessarily complicated approach.

{{% /notice %}}

{{% notice tip %}}
  The type attribute gives the type of the media resource, to help the user agent determine if it can play this media resource before fetching it. If specified, its value must be a valid MIME type. The codecs parameter, which certain MIME types define, might be necessary to specify exactly how the resource is encoded.
{{% /notice %}}


<h3>Advantages of this tag</h3>

  <ul>
    <li>It gives your users a pleasant experience to watch videos as they don’t have to download any additional plugins.</li>
  </ul>

<h3>Working Example</h3>

    <video controls>
    <source src="foo.webm" type="video/webm">
    <source src="foo.ogg" type="video/ogg">
    <source src="foo.mov" type="video/quicktime">
    I'm sorry; your browser doesn't support HTML5 video.
    </video>

<video controls>
  <source src="foo.webm" type="video/webm">
  <source src="foo.ogg" type="video/ogg">
  <source src="foo.mov" type="video/quicktime">
  I'm sorry; your browser doesn't support HTML5 video.
</video>

<h3>References</h3>
[W3](https://dev.w3.org/html5/spec-preview/the-source-element.html)
<br>
[MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/source)
