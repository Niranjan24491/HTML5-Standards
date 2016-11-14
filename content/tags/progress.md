+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/ruby"
prev = "/tags/pre"
title = "progress"
toc = true
weight = 81

+++

When building web sites and web applications, we often need to provide essential feedback to a user informing them of the progress of their request or task, be it uploading a file, playing a video, or importing data.

HTML5 makes life easier for us by defining an element whose sole purpose is just that: the <b>progress</b> element.

Progress element can have two attributes:
<ol>
  <li><b>Max:</b> Specifies how much work the task requires in total</li>
  <li><b>Value:</b> Specifies how much of the task has been completed</li>
</ol>

<h3>Working Example</h3>
    <progress value="60" max="100"></progress>

<h3>Need for this tag</h3>
The <b>progress</b> element may seem very similar to the <b>meter</b> element � which was also introduced in HTML5 � but it can be seen as a more specific kind of <b>meter</b> element that�s only used to measure progress of a task. It�s worth bearing this in mind when deciding which one to use.   

<h3>Disadvantage of this tag</h3>
<ol>
  <li>Still there are few browsers which are not Supporting</li>
  <li>This tag will not work for few languages, German or Swedish, where the input and the output should use a decimal comma instead of a decimal point</li>
</ol>

<h3>Advantages of this tag</h3>
<ol>
  <li>Browser support is pretty good</li>
  <li>CSS styling is possible in varity of ways</li>
</ol>

<h3>References</h3>
http://html5doctor.com/the-progress-element/

<h3>Point of Contact</h3>
Gaurav Sharma <br>
gasharma@deloitte.com
