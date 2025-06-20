---
layout: home
title: "Elnur Khalmetov"
excerpt: "Robotics & Engineering Projects"
---

### Mechanical Engineering Student @ Kyoto University of Advanced Science

I'm an international engineering student specialising in robotics, CAD, and prototyping.

![Robot render](/assets/images/hero-render.png){: .img-fluid }

## Core Skills
**Mechanical & Robotics**  
<span class="skill-tag">CAD: Creo, Fusion 360</span>
<span class="skill-tag">Machining & Prototyping</span>  
**Programming**  
<span class="skill-tag">C / C++ / Java</span>  
**Languages**  
<span class="skill-tag">English – Fluent</span>
<span class="skill-tag">Japanese – JLPT N3</span>

## Projects
{% for project in site.data.projects %}
### [{{ project.title }}]({{ project.url }})
{{ project.description }}

{% endfor %}
