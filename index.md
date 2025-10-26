---
layout: default
title: Home
---

<div id="bio">
  <h3>Bio</h3>
  <p>I'm a PhD candidate in Geospatial Data Science at the University of Glasgow. My research explores the intersection of geospatial AI, data ethics, and urban analytics, with emphasis on positioning, navigation, and fairness in spatial data.</p>
</div>

<div id="publications">
  <h3>Publications</h3>
  {% capture pubs %}
    {% include_relative publications.md %}
  {% endcapture %}
  {{ pubs | markdownify }}
</div>


<div id="cv">
  <h3>Vitæ</h3>
  <p>Full Curriculum Vitæ in <a href="/assets/cv/cv.pdf" target="_blank">pdf</a></p>
</div>
