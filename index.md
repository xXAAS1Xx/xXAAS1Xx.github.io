---
layout: default
title: "Armaan | SDSU MIS & CS Portfolio"
---

<header class="hero">
  <div class="hero-content">
    <span class="badge">San Diego State University</span>
    <h1>Management Information Systems <span class="accent-text">Major</span></h1>
    <p class="subtitle">Computer Science Minor | Cloud & Cybersecurity Focus</p>
    <div class="code-terminal">
      <p><span class="code-keyword">const</span> student = {</p>
      <p class="indent"><span class="code-prop">name</span>: <span class="code-string">'Armaan'</span>,</p>
      <p class="indent"><span class="code-prop">university</span>: <span class="code-string">'SDSU'</span>,</p>
      <p class="indent"><span class="code-prop">focus</span>: [<span class="code-string">'Systems Analysis'</span>, <span class="code-string">'Cloud Security'</span>, <span class="code-string">'Esports Infrastructure'</span>],</p>
      <p class="indent"><span class="code-prop">status</span>: <span class="code-string">'Building scalable digital solutions'</span></p>
      <p>};</p>
    </div>
    <div class="hero-buttons">
      <a href="#projects" class="btn-primary">View Projects</a>
    </div>
  </div>
</header>

<section id="about" class="section">
  <div class="container">
    <h2 class="section-title">Bridging <span class="scarlet">Business</span> & <span class="cyan">Technology</span></h2>
    <p class="section-desc">
      Combining business strategy, database systems, and computer science fundamentals to design secure cloud architectures and optimize enterprise workflows.
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
