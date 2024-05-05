---
layout: page
title: Sokoban
description: A classic puzzle game of Sokoban, developed in C++ to challenge players with intricate levels where they push boxes to designated locations.
img: /assets/img/Sokoban.jpg
importance: 3
category: Side project
---
In this project, I developed a Sokoban game using C++ and the Simple and Fast Multimedia Library (SFML). My goal was to create a game that challenges players with engaging puzzles that require strategic thinking and careful planning. I focused on using C++ to implement complex game logic and SFML to manage the graphical interface, ensuring smooth and responsive gameplay. This game not only demonstrates my technical skills but also my passion for combining classic game design with modern programming techniques.


<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-12 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sokoban.gif" title="example image" class="img-fluid rounded z-depth-1" %}
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
