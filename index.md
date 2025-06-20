---
layout: default
title: "Home"
---

<a class="lang-switch" href="/ja/">日本語</a>

<div class="hero">
  <img src="https://placehold.co/600x400?text=Hero+Render" alt="Robot Render">
  <div class="hero-text">
    <h2>Mechanical Engineering Student @ KUAS</h2>
    <p>This is a sample introduction block with some placeholder text. Swap in your own render and biography to make it yours.</p>
  </div>
</div>

## Core Skills
<span class="skill-tag">CAD (Creo, Fusion 360)</span>
<span class="skill-tag">C / C++ / Java</span>
<span class="skill-tag">MATLAB</span>
<span class="skill-tag">Embedded Systems</span>
<span class="skill-tag">English (Fluent)</span>
<span class="skill-tag">Japanese (JLPT N3)</span>

## Projects Snapshot
<div class="project-grid">
{% for project in site.data.projects %}
  <a class="project-card" href="{{ project.url }}">
    <img src="https://placehold.co/600x340?text={{ project.title | uri_escape }}" alt="">
    <div class="body">
      <h3>{{ project.title }}</h3>
      <p>{{ project.description }}</p>
    </div>
  </a>
{% endfor %}
</div>
