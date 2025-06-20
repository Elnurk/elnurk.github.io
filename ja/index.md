---
layout: default
title: "ホーム"
permalink: /ja/
---

<a class="lang-switch" href="/">English</a>

<div class="hero">
  <img src="https://placehold.co/600x400?text=レンダー画像" alt="Robot Render">
  <div class="hero-text">
    <h2>京都先端科学大学 工学部 学生</h2>
    <p>ここに自己紹介文のサンプルが入ります。自由に日本語のプロフィールや画像を差し替えてください。</p>
  </div>
</div>

## 主なスキル
<span class="skill-tag">CAD (Creo, Fusion 360)</span>
<span class="skill-tag">C / C++ / Java</span>
<span class="skill-tag">MATLAB</span>
<span class="skill-tag">組込みシステム</span>
<span class="skill-tag">英語 (流暢)</span>
<span class="skill-tag">日本語 (JLPT N3)</span>

## プロジェクトスナップショット
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
