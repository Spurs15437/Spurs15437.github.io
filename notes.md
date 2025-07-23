---
layout: page
title: 技术笔记
permalink: /notes/
---

<h1>技术笔记</h1>

<div class="note-list">
  {% for note in site.notes %}
    <div class="note-item">
      <h2><a href="{{ note.url }}">{{ note.title }}</a></h2>
      <p class="post-meta">发布于 {{ note.date | date: "%Y-%m-%d" }}</p>
    </div>
  {% endfor %}
</div>