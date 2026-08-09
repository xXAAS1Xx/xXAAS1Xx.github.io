---
layout: default
title: "Projects | Armaan Shamsaasef"
permalink: /projects/
---

<section class="section page-header">
  <div class="container">
    <h1 class="section-title">Featured <span class="cyan">Projects</span></h1>
    <p class="section-desc">Technical implementations in cloud infrastructure, systems analysis, and software development.</p>
  </div>
</section>

<section class="section">
  <div class="container">
    <div class="grid">
      {% for project in site.projects %}
        <div class="project-card">
          <div class="project-tag">{{ project.category }}</div>
          <h3>{{ project.title }}</h3>
          <p>{{ project.description }}</p>
          <a href="{{ project.url | relative_url }}" class="project-link">View Architecture & Details &rarr;</a>
        </div>
      {% endfor %}
    </div>
  </div>
</section>
