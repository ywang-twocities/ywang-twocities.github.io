---
layout: default
title: Home
---

<div id="bio">
  <h3>Bio</h3>
  {% capture bio %}
    {% include_relative bio.md %}
  {% endcapture %}
  {{ bio | markdownify }}
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
