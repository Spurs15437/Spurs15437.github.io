---
layout: home
title: 欢迎访问我的空间
---

<section class="home-hero">
  <h1>你好，我是 Spurs</h1>
  <p>开发者 | 技术爱好者 | 终身学习者</p>
</section>

<div class="home-grid">
  <div class="card">
    <h2>最新笔记</h2>
    {% for note in site.notes limit:3 %}
      <a href="{{ note.url }}">{{ note.title }}</a>
    {% endfor %}
    <p class="more-link"><a href="/notes/">查看所有笔记 →</a></p>
  </div>
  
  <div class="card">
    <h2>项目文档</h2>
    <a href="/wiki/project-a">项目A文档</a>
    <a href="/wiki/project-b">项目B文档</a>
    <a href="/wiki/api">API文档</a>
    <p class="more-link"><a href="/wiki/">查看所有文档 →</a></p>
  </div>
  
  <div class="card">
    <h2>关于我</h2>
    <p>专注于Web开发和数据分析，喜欢分享技术知识和实践经验。</p>
    <p class="more-link"><a href="/about/">了解更多 →</a></p>
  </div>
</div>