---
layout: page
permalink: /fieldwork/
title: fieldwork
description: 
nav: true
nav_order: 2
---

<!-- _pages/fieldwork.md -->



Here some images of the fieldwork
{% include image-gallery.html folder="/assets/img/fieldwork" %}

Here you can find a list of all the published datasets which have resulted from the acquired data
<div class="publications">
  {% bibliography --group_by none --query @*[type=misc]* %}
</div>