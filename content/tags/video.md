+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/"
prev = "/tags/var"
title = "video"
toc = true
weight = 125

+++

The HTML <span class='tag-span'>&lt;video&gt;</span> element is used to embed videos along with captions into your web page.

<h3>Need for this tag</h3>

With modern website becoming more interactive, video and audio support were needed for HTML document. <span class='tag-span'>&lt;video&gt;</span> element was introduced in HTML5 to do the job.
{{% notice tip %}}
  Any content between the opening and closing <span class='tag-span'>&lt;video&gt;</span> tags is fallback content. This content is displayed only by browsers that don't support the <span class='tag-span'>&lt;video&gt;</span> tag.
{{% /notice %}}

<h3>Disadvantages of this tag</h3>
<ol>
  <li>Limited video formats(MP4/MPEG 4, WebM and Ogg) are only supported by the <span class='tag-span'>&lt;video&gt;</span> element.</li>
</ol>

<h3>Advantages of this tag</h3>

<ol>
  <li>HTML5 video is now widely implemented in the major browsers and it has support from major websites.</li>
  <li>HTML5 <span class='tag-span'>&lt;video&gt;</span> tag supports all the event attributes described in - HTML Events Reference.</li>
  <li>HTML5 <span class='tag-span'>&lt;video&gt;</span> tag accepts attributes that provides lots of options w.r.t video playing.</li>
</ol>

<h3>Working Example</h3>

<video width="500" height="300" controls>
  <source src="/data/dummyvideo.mp4" type="video/mp4">
  This browser doesn't support video tag.
</video>

    <video width="500" height="300" controls>
    <source src="/data/dummyvideo.mp4" type="video/mp4">
    This browser doesn't support video tag.
    </video>

<h3>References</h3>

[MDN](https://developer.mozilla.org/en/docs/Web/HTML/Element/video)
<br>
[Quackit](http://www.quackit.com/html_5/tags/html_video_tag.cfm)

<h3>Point of Contact</h3>
