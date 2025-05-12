---
layout: page          # Minimal theme layout
title: "Virtualization Portfolio"
permalink: /
---

<!-- Custom CSS link -->
<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">

<header class="hero">
  <h1>Virtualization Technology Portfolio</h1>
  <p class="subtitle">VMware • VirtualBox • KVM • Hyper‑V</p>
</header>

<section class="gallery">
{% comment %}
  Repeat the block below for each screenshot.
  Use markdown for captions; HTML for layout.
{% endcomment %}
  <figure class="shot">
    <img src="{{ '/assets/images/vmware-console.png' | relative_url }}"
         alt="VMware vSphere console" />
    <figcaption>VMware vSphere console showing nested ESXi lab.</figcaption>
  </figure>

  <figure class="shot">
    <img src="{{ '/assets/images/virtualbox-ubuntu.png' | relative_url }}"
         alt="Ubuntu VM in VirtualBox" />
    <figcaption>Ubuntu 22.04 LTS running in VirtualBox on Windows 11.</figcaption>
  </figure>

  <!-- Add more <figure> blocks as needed -->
</section>
