---
layout: default
title: Home
section: home
---
<div class="text-white ">
  <h1><img src="images/qfrequency-logo-white-800.png" class="logo-main" alt="Q Frequency Music"/></h1>
  <p class="fs-5"><strong>Melodic & Techno Electronic Music</strong></p>
  <p class="fs-3"><a href="https://twitter.com/qfrequency" class="link-light"><i class="bi bi-twitter"></i></a></p>
</div>
<div class="row video-grid">
  {% for video in site.data.videos %}
    <div class="col-lg-6 col-md-12 col-sm-12">
      <iframe width="560" height="315" src="{{ video.url }}" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  {% endfor %}
</div>
