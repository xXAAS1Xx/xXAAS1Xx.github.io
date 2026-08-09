---
layout: default
title: "Armaan Shamsaasef | San Diego State University | MIS Major & CS Minor"
---

<header class="hero">
  <div class="hero-content">
    <span class="badge">San Diego State University</span>
    <h1>Management Information Systems <span class="accent-text">Major</span></h1>
    <p class="subtitle">Computer Science Minor | Cloud Architecture & Cybersecurity Focus</p>
    
    <div class="hero-summary">
      <p>
        MIS Student at San Diego State University combining business strategy, database architecture, and computer science fundamentals. Focused on scalable enterprise solutions, cloud security, and systems optimization.
      </p>
    </div>

    <div class="hero-buttons">
      <a href="#projects" class="btn-primary">View Projects</a>
      <a href="#skills" class="btn-secondary">Technical Skills</a>
    </div>
  </div>
</header>

<section id="about" class="section">
  <div class="container">
    <h2 class="section-title">Bridging <span class="scarlet">Business</span> & <span class="cyan">Technology</span></h2>
    <p class="section-desc">
      Applying business analytics, infrastructure planning, and software development to optimize systems and implement secure cloud environments.
    </p>
  </div>
</section>

<section id="skills" class="section dark-bg">
  <div class="container">
    <h2 class="section-title">Technical Expertise</h2>
    <div class="grid">
      <div class="card">
        <div class="card-icon">⚡</div>
        <h3>MIS & Business Systems</h3>
        <ul>
          <li>Systems Analysis & Design</li>
          <li>Database Architecture (SQL)</li>
          <li>Process Optimization</li>
        </ul>
      </div>
      <div class="card">
        <div class="card-icon">💻</div>
        <h3>CS & Development</h3>
        <ul>
          <li>Python, Java, C++, JavaScript</li>
          <li>Data Structures & Algorithms</li>
          <li>Web Development</li>
        </ul>
      </div>
      <div class="card">
        <div class="card-icon">🛡️</div>
        <h3>Cloud & Cybersecurity</h3>
        <ul>
          <li>Cloud Infrastructure</li>
          <li>Security & Latency Optimization</li>
          <li>Identity & Access Management</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section id="projects" class="section">
  <div class="container">
    <h2 class="section-title">Featured Projects</h2>
    <div class="grid">
      {% for project in site.projects %}
        <div class="project-card">
          <div class="project-tag">{{ project.category }}</div>
          <h3>{{ project.title }}</h3>
          <p>{{ project.description }}</p>
          <a href="{{ project.url | relative_url }}" class="project-link">View Details &rarr;</a>
        </div>
      {% endfor %}
    </div>
  </div>
</section>
