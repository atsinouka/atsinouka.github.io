---
layout: about
title: about
permalink: /
subtitle: >-
  PhD Student @ <a href="https://www.ntua.gr/en/">NTUA</a>,
  <a href="https://heron-robotics-coe.eu/">HERON</a>

profile:
  align: right
  image: myphoto.jpg
  image_circular: true
  more_info: >
    <div class="profile-socials">
    <a href="mailto:atsinouka@athenarc.gr" title="Email"><i class="fa-solid fa-envelope"></i></a>
    <a href="https://scholar.google.com/citations?user=YOUR_SCHOLAR_ID" title="Google Scholar" target="_blank" rel="noopener"><i class="ai ai-google-scholar"></i></a>
    <a href="https://github.com/atsinouka" title="GitHub" target="_blank" rel="noopener"><i class="fa-brands fa-github"></i></a>
    <a href="https://www.linkedin.com/in/angeliki-tsinouka/" title="LinkedIn" target="_blank" rel="noopener"><i class="fa-brands fa-linkedin"></i></a>
    </div>

selected_papers: false
social: false

announcements:
  enabled: false
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

I am a first-year PhD student at the [National Technical University of Athens (NTUA)](https://www.ntua.gr/en/), affiliated with [Hellenic Robotics Center of Excellence (HERON)](https://heron-robotics-coe.eu/), under the supervision of Prof. [Petros Maragos](https://robotics.ntua.gr/members/maragos/). Before starting my PhD, I received my Diploma M.Eng Degree from the [School of Electrical and Computer Engineering](https://www.ece.ntua.gr/en) at NTUA in 2025. My [diploma thesis](https://dspace.lib.ntua.gr/xmlui/handle/123456789/64359?show=full) focused on audiovisual face reconstruction, under the supervision of Prof. Petros Maragos.

My research interests include Computer Vision, Machine Learning, and Robotics, particularly robotic perception, 3D scene understanding, object pose estimation, and robotic manipulation.

## Publications

<div class="publications">
{% bibliography --group_by none %}
</div>

<script>
  // Make the "CV" menu link open the PDF in a new tab
  document.querySelectorAll('.navbar a.nav-link[href$="/cv/"]').forEach(function (a) {
    a.href = "{{ '/assets/pdf/AngelikiTsinouka_CV.pdf' | relative_url }}";
    a.target = "_blank";
    a.rel = "noopener";
  });
</script>
