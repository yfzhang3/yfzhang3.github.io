---
layout: page
title: Using Automatic Pattern Recognition to Study DNA Repair in U2OS Cells
description: Research done at UCSD Cellular Biophotonics Laboratory under the mentorship of Dr. Michael Berns & Dr. Linda Shi
img: /assets/img/dna_repair/poster.png
importance: 1
category: work
---

Research Goal: In the lab, lasers are used to cut U2OS cells (from human bone tissue) and form double strand breaks. When the cell is damaged, many proteins with different roles come to the site of damage to repair the cells. Our goal is to use machine learning and image processing to automate the process of detecting laser cut lines in U2OS cells (human bone cells) using MATLAB.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
    
        {% include figure.html path="assets/img/dna_repair/poster.png" title="research poster" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Poster presented at the Biomedical Engineering Society Conference 2022
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
