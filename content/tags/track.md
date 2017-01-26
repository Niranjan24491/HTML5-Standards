+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/ul"
prev = "/tags/title"
title = "track"
toc = true
weight = 122

+++

The HTML5 <span class='tag-span'>&lt;track&gt;</span> tag is used to specify external timed text tracks for media elements (i.e. the <span class='tag-span'>&lt;video&gt;</span> element and the <span class='tag-span'>&lt;audio&gt;</span> element). The text tracks specified with the <track> tag could include subtitles, captions, descriptions, chapters, and metadata.

<h3>Need for this tag</h3>

 Text tracks for media elements can be added using <span class='tag-span'>&lt;track&gt;</span> element.

<h3>Disadvantages of this tag</h3>
<ol>
  <li>Browser support for <span class='tag-span'>&lt;track&gt;</span> element may be limited for some time.</li>
</ol>

<h3>Advantages of this tag</h3>
<ol>
  <li>The <span class='tag-span'>&lt;track&gt;</span> element automatically handle subtitles without any javascript dependency.</li>
</ol>

{{% notice note %}}
  A media element cannot have more than one track with the same kind, srclang, and label.
{{% /notice %}}


<h3>Working Example</h3>

<video width="500" height="300" controls>
  <source src="/data/dummy_video.mp4" type="video/mp4">
  <track src="/data/track_subtitles.vtt" kind="subtitles" srclang="en" label="English">
  This browser doesn't support video tag.
</video>

    <video width="500" height="300" controls>
      <source src="/data/dummy_video.mp4" type="video/mp4">
      <track src="/data/track_subtitles.vtt" kind="subtitles" srclang="en" label="English">
      This browser doesn't support video tag.
    </video>

<h3>References</h3>

[MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/track)
<br>
[Quackit](http://www.quackit.com/html_5/tags/html_track_tag.cfm)


<h3>Point of Contact</h3>
