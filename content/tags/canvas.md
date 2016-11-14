+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/caption"
prev = "/tags/button"
title = "canvas"
toc = true
weight = 5

+++

HTML5 element <canvas> gives you an easy and powerful way to draw graphics using JavaScript. It can be used to draw graphs, make photo compositions or do simple (and not so simple) animations.

    <canvas id="mycanvas" width="100" height="100"></canvas>

You can easily find that <canvas> element in the DOM using getElementById() method as follows −

    var canvas  = document.getElementById("mycanvas");

Let us see a simple example on using <canvas> element in HTML5 document.

    <!DOCTYPE HTML>
    <html>
       <head>
          <style>
             #mycanvas{border:1px solid red;}
          </style>
       </head>
       <body>
          <canvas id="mycanvas" width="100" height="100"></canvas>
       </body>
    </html>

<h3>The Rendering Context</h3>
The <canvas> is initially blank, and to display something, a script first needs to access the rendering context and draw on it.

The canvas element has a DOM method called getContext, used to obtain the rendering context and its drawing functions. This function takes one parameter, the type of context 2d.

Following is the code to get required context along with a check if your browser supports <canvas> element −

    var canvas  = document.getElementById("mycanvas");

    if (canvas.getContext){   
    var ctx = canvas.getContext('2d');   
    // drawing code here   
    }

    else {   
    // canvas-unsupported code here
    }


{{% notice note %}}
  For more info on the canvas attributes and methods, please checkout the below link.
  https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial
{{% /notice %}}

<h3>References</h3>
https://www.tutorialspoint.com/html5/html5_canvas.htm

<h3>Point of Contact</h3>
Niranjan Thrineshwar <br>
nthrineshwar@deloitte.com <br>
9663770742
