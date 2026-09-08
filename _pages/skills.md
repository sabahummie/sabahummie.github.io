---
layout: archive
title: "Technical Skills"
permalink: /skills/
author_profile: true
---

<style>
.skills-card {
  margin: 1.5rem 0 2rem;
  padding: 1.5rem 1.6rem;
  border: 1px solid rgba(127, 127, 127, 0.25);
  border-left: 4px solid #52adc8;
  border-radius: 8px;
  background: rgba(127, 127, 127, 0.04);
  box-shadow: 0 3px 12px rgba(0, 0, 0, 0.06);
}

.skills-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 1rem;
}

.skills-title {
  margin: 0 !important;
  font-size: 1.2rem;
  line-height: 1.4;
}

.skills-subtitle {
  margin: 0.4rem 0 0 !important;
  font-style: italic;
  opacity: 0.8;
}

.skills-badge {
  flex-shrink: 0;
  padding: 0.25rem 0.7rem;
  border-radius: 1rem;
  background: rgba(82, 173, 200, 0.15);
  color: #3790aa;
  font-size: 0.85rem;
  font-weight: 700;
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1.5rem 2rem;
  margin-top: 1.25rem;
  padding-top: 1.25.25rem;
  border-top: 1px solid rgba(127, 127, 127, 0.2);
}

.skill-group {
  min-width: 0;
}

.skill-label {
  display: block;
  margin-bottom: 0.7rem;
  font-size: 0.72rem;
  font-weight: 700;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  opacity: 0.65;
}

.skill-list {
  display: flex;
  flex-wrap: wrap;
  gap: 0.45rem;
}

.skill-tag {
  display: inline-block;
  padding: 0.32rem 0.65rem;
  border: 1px solid rgba(82, 173, 200, 0.25);
  border-radius: 5px;
  background: rgba(82, 173,173, 200, 0.08);
  font-size: 0.86rem;
   line-height: 1.3;
}

@media (max-width: 650px) {
  .skills-grid {
    grid-template-columns: 1fr;
  }

  .skills-header {
    align-items: flex-start;
  }
}
</style>

<article class="skills-card">

  <header class="skills-header">
    <div>
      <h2 class="skills-title">Technical Expertise</h2>
      <p class="skills-subtitle-subtitle">
        Programming, software engineering, and data analysis
      </p>
    </div>

    <span class="skills-badge">6 Areas</span>
  </header>

  <div class="skills-grid">

    <section class="skill-group">
      <span class="skill-label">Programming Languages</span>

      <div class="skill-list">
        <span class="skill-tag">Python</span>
        <span class="skill-tag">Java</span>
        <span class="skill-tag">SQL</span>
      </div>
    </section>

    <section class="skill-group">
      <span class="skill-label">Computer Science Fundamentals</span>

      <div class="skill-list">
        <span class="skill-tag">Object-Oriented Programming</span>
        <span class="skill-tag">Data Structures and Algorithms</span>
        <span class="skill-tag">Java Collections Framework</span>
        <span class="skill-tag">Java 8 Stream API</span>
        <span class="skill-tag">Multithreading</span>
        <span class="skill-tag">Object-Oriented Design</span>
      </div>
    </section>

    <section class="skill-group">
      <span class="skill-label">Front-End and Back-End Development</span>

      <div class="skill-list">
        <span class="skill-tag">HTML</span>
        <span class="skill-tag">CSS</span>
        <span class="skill-tag">JavaScript</span>
        <span class="skill-tag">Flask</span>
        <span class="skill-tag">Spring Boot</span>
        <span class="skill-tag">RESTful APIs</span>
        <span class="skill-tag">Microservices Architecture</span>
        <span class="skill-tag">MVC</span>
      </div>
    </section>

    <section class="skill-group">
      <span class="skill-label">Data Analysis and Machine Learning</span>

      <div class="skill-list">
        <span class="skill-tag">Pandas</span>
        <span class="skill-tag">Matplotlib</span>
        <span class="skill-tag">Flower (FLWR)</span>
        <span class="skill-tag">Federated Learning</span>
      </div>
    </section>

    <section class="skill-group">
      <span class="skill-label">Development Tools and Servers</span>

      <div class="skill-list">
        <span class="skill-tag">Git</span>
        <span class="skill-tag">GitHub</span>
        <span class="skill-tag">Maven</span>
        <span class="skill-tag">Asana</span>
        <span class="skill-tag">Apache Tomcat</span>
      </div>
    </section>

    <section class="skill-group">
      <span class="skill-label">Operating Systems</span>

      <div class="skill-list">
        <span class="skill-tag">Windows</span>
        <span class="skill-tag">Linux</span>
      </div>
    </section>

  </div>

</article>