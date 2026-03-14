---
layout: default
title: Home
permalink: /
---

<section class="home-section">
  <h3>Welcome!</h3>

  <div class="home-hero">
    <img src="{{ site.author.photo | relative_url }}" alt="{{ site.author.name }}" />
    <div class="home-intro">
      <p>
        I am <strong>{{ site.author.name }}</strong>, currently studying
        <strong>Master's Data Science in Health</strong> at the
        <a href="https://www.ucla.edu/">University of California, Los Angeles (UCLA)</a>,
        and supported by a <strong>Fulbright scholarship</strong>.
      </p>
      <p>
        I love solving problems to help others reach their goals, especially in
        <strong>digital startups</strong>, <strong>big tech</strong>,
        <strong>e-commerce</strong>, and <strong>fintech</strong>.
      </p>
      <p>
        Feel free to reach me at
        <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a>.
      </p>
    </div>
  </div>

  <h3>Interests</h3>
  <ul>
    <li>Analytics engineer</li>
    <li>Business intelligence</li>
    <li>Data science</li>
    <li>Biostatistics</li>
    <li>Public health</li>
    <li>Healthcare</li>
  </ul>
</section>
