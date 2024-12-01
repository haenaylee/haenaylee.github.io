---
layout: page
title: Drawing
description: Learning to reconnect with childhood.
img: assets/img/drawing_background.jpg
importance: 1
category: fun
---

After my first job out of college, I've been thinking a lot about what kind of life or career might make me happy. I thought about the things that sparked me as a kid and began to reintroduce them back into my life, hoping they might point me in the right directions.

English and art were the subjects I were effortlessly good at as a kid. From elementary to high school, I would  consistently write ten pages for a one page prompt, or spend every lunch and recess in the art classroom perfecting my sculptures. I lost touch with my creative side while I was focusing on becoming an engineer, but I am beyond thrilled to revisit it as an adult. Despite the loss of a child's wild imagination, in its stead is an extraordinary sense of artistic and financial freedom.

My goal is to practice the Renaissance-era style of drawing (and perhaps painting) until I can bring a particular vision of mine to life. It will be my way of acknowledging and grappling with the magnitude of suffering in the world. But I have yet to take classes so I have a long, exciting way to go!

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/dancer.jpg" title="dancer" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/practice.jpg" title="practice" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hisokas.jpg" title="hisokas" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Prior to any formal art instruction; my very first figure drawing and first time trying shadowing. Center: Some practice sketches while watching YouTube videos on Renaissance drawing. Right: Tried drawing a character from an popular anime; definitely need to work on coloring...
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
