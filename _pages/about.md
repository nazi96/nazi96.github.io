---
permalink: /
title: "Hi, I'm Nazanin 👋"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<div class="home-grid">
  <div class="home-col">
    <img class="home-photo" src="/images/profile-photo.jpg" alt="Portrait of Nazanin Amini">
    <p class="home-links">
      <a href="mailto:nazanin.amini@utsa.edu">Email</a> /
      <a href="/files/CV_Nazanin_Amini.pdf">CV</a> /
      <a href="https://scholar.google.com/citations?user=l0W0P1EAAAAJ">Scholar</a> /
      <a href="https://github.com/nazi96">GitHub</a> /
      <a href="https://www.linkedin.com/in/nazanin-amini-2355b5347/">LinkedIn</a>
    </p>
  </div>
  <div class="home-col">
    <p>
      I’m a Ph.D. student in Computer Science at the <a href="https://www.utsa.edu/">University of Texas at San Antonio</a>,
      advised by <a href="https://klab.cs.utsa.edu/">Dr. Kevin Desai</a>.
      My research focuses on <strong>human-scene interaction (HSI) motion generation</strong>:
      generating realistic human motion that interacts naturally with 3D environments.
    </p>
    <p>
      I’m open to research collaborations and internships, so feel free to reach out by email.
    </p>
  </div>
</div>

<hr>

## Publications

<div class="pub-list" markdown="0">
{%- assign pubs = site.publications | sort: "date" | reverse -%}
{%- for pub in pubs -%}
{% include pub-card.html pub=pub %}
{%- endfor -%}
</div>
