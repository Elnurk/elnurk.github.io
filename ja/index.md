---
layout: home
title: "エルヌール・カルメトフ"
excerpt: "ロボティクス＆エンジニアリングプロジェクト"
---

### 京都先端科学大学 工学部 学生

国際ロボティクス・エンジニアリング専攻の学生です。

![ロボットレンダー](/assets/images/hero-render.png){: .img-fluid }

## 主なスキル
**機械・ロボティクス**  
<span class="skill-tag">CAD: Creo, Fusion 360</span>
<span class="skill-tag">加工 & プロトタイピング</span>  
**プログラミング**  
<span class="skill-tag">C / C++ / Java</span>  
**言語**  
<span class="skill-tag">英語 – 流暢</span>
<span class="skill-tag">日本語 – JLPT N3</span>

## プロジェクト
{% for project in site.data.projects %}
### [{{ project.title }}]({{ project.url }})
{{ project.description }}

{% endfor %}
