+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/base"
prev = "/tags/aside"
title = "audio"
toc = true
weight = 7

+++

The HTML <span class='tag-span'>&lt;audio&gt;</span> element is used to embed sound content in documents. It may contain one or more audio sources, represented using the src attribute or the <span class='tag-span'>&lt;source&gt;</span> element; the browser will choose the most suitable one.

<h3>Need for this tag</h3>
Fallback content for browsers not supporting the <span class='tag-span'>&lt;audio&gt;</span> element can be added too, inside the opening and closing <span class='tag-span'>&lt;audio&gt;</span><span class='tag-span'>&lt;/audio&gt;</span> tags.

The most basic playback functionality can be made available using the controls attribute (see below); for more advanced usage, audio playback and controls can be manipulated using the HTML Media API, and more specifically the features defined in the HTMLAudioElement interface.

{{% notice note %}}
  * The autoplay attribute has precedence over preload. If autoplay is specified, the browser would obviously need to start downloading the audio for playback.
  * The browser is not forced by the specification to follow the value of this attribute; it is a mere hint.
{{% /notice %}}

<h3>Advantages of this tag</h3>
<ol>
  <li>Will help in Search Engine Optimization(SEO) by following the HTML standards</li>
  <li>Provides semantic meaning to the HTML page</li>
</ol>

<h3>Working Example</h3>

    <!-- Simple audio playback -->
    <audio src="http://developer.mozilla.org/@api/deki/files/2926/=AudioTest_(1).ogg" controls>
      Your browser does not support the <code>audio</code> element.
    </audio>


<!-- Simple audio playback -->
<audio src="http://developer.mozilla.org/@api/deki/files/2926/=AudioTest_(1).ogg" controls>
  Your browser does not support the <code>audio</code> element.
</audio>



<h3>References</h3>
[MDN](https://developer.mozilla.org/en/docs/Web/HTML/Element/audio)
