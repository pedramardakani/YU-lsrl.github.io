---
layout: page
title: project 1
description: a project with a background image
img: assets/img/12.jpg
importance: 1
category: work
---

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---
<table style="width: 98%; margin-right: calc(2%);">
    <tbody>
        <tr>
            <td style="width: 50%;">{% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}</td>
            <td style="width:50%;">
                <div style="text-align: left; margin-left: 40px;"><span>Mohammad Ali Haddad</span></div>
                <div style="text-align: left; margin-left: 40px;"><span>Group Leader</span></div>
                <div style="text-align: left; margin-left: 40px;"><span>Ph.D in atomic and molecular physics</span></div>
            </td>
        </tr>
    </tbody>
</table>
<p><br></p>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    
