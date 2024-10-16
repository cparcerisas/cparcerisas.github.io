---
layout: page
permalink: /fieldwork/
title: datasets and fieldwork
description: 
nav: true
nav_order: 2
---

<!-- _pages/data_and_fieldwork.md -->



Here some images of the fieldwork
{% include image-gallery.html folder="/assets/img/fieldwork" %}

Here you can find a list of all the published datasets which have resulted from the acquired data
<div class="publications">
 {% bibliography --template bib --group_by type --group_order ascending,descending --query @*[type=misc] --prefix post2 %}
</div>