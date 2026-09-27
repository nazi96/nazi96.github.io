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
      I work on generative models that understand and create visual content, with a focus on
      <strong>diffusion models</strong>, <strong>vision-language representations</strong> such as CLIP,
      and <strong>controllable image generation</strong>.
    </p>
    <p>
      My recent work applies these ideas to human motion and appearance.
      <a href="https://arxiv.org/abs/2607.26304">MoSAIC</a> is a latent diffusion framework that transfers
      motion style to selected body parts while preserving the rest of the movement.
      In <a href="https://arxiv.org/abs/2604.15875">Cloth-HUGS</a>, we use Gaussian Splatting to represent the body
      and clothing as separate layers, producing photorealistic clothed humans that render in real time.
    </p>
    <p>
      Before starting my Ph.D., I earned an M.Sc. in Electrical Engineering from
      <a href="https://shirazu.ac.ir/en">Shiraz University</a>, where my thesis focused on
      background subtraction for robust video analysis.
    </p>
    <p>
      I’m open to research collaborations and internship opportunities, so feel free to reach out by email.
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
