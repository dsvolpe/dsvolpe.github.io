---
layout: page
title: COMBINE
description: Graduate fellowships in network biology
img: assets/img/pm_combine.jpg
importance: 3
category: fun
---

- Program name: COMBINE (Computation and Mathematics for Biological Networks)
- Funding: $2.9M
- Website: [www.combine.umd.edu](https://www.combine.umd.edu)
- Duration: 2017 - 2021
- My involvement: 2017 - 2021

COMBINE was a graduate fellowship program funded by NSF's NRT (NSF Research Traineeship) that ran from 2017 to 2022 at UMD.
The scientific focus was network science across biological scales.

As Research Educator of COMBINE, I designed and taught curriculum.

I was also heavily involved in co-managing the program, leading and/or helping with: recruitment, admissions, event planning, progress tracking, assessment, and reporting.

Here is a subset of key contributions:
- Helped develop the grant proposal that funded the program ($2,959,866)
- Designed the program visual brand, along with recruitment flyers and event banners (samples below)
- Co-designed and co-taught 4 semesters of graduate course on scientific communication (PHYS782: Interdisciplinary Research and Communication Practicum for Data-Driven Science; [2020 syllabus](https://drive.google.com/file/d/17JdIJpWBLdDDctDQ994MhI4oStpBNIh8/view?usp=share_link))
- Tracked and supported graduate fellow program progress
- Co-developed, co-implemented, and co-analyzed assessment surveys, leading to program improvements
- Co-wrote journal article reporting on assessment data ([PLOS One 2021](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0257872))

Associated grants:


To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
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
