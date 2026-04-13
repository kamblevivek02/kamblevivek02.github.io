---
layout: page
title: Test Style 2
permalink: /test2/
nav: false
---

<style>
  .hero-subtle {
    background-image: /assets/img/background1.jpg;
    background-size: cover;
    background-position: center;
    padding: 40px 20px;
    border-radius: 10px;
    text-align: center;
    margin-bottom: 30px;
    position: relative;
    z-index: 1;
  }
  .hero-subtle::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: rgba(0,0,0,0.4);
    border-radius: 10px;
    z-index: -1;
  }
  .hero-subtle h2, .hero-subtle h3, .hero-subtle p {
    position: relative;
    z-index: 2;
    color: white;
    text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
  }
</style>

## Style 2: Hero with Semi-Transparent Overlay

<div class="hero-subtle">
  <h2>Vivek Kamble</h2>
  <h3>Cybersecurity & GRC Professional</h3>
  <p>Bridging Governance, Risk & Compliance with AI-driven security solutions</p>
</div>

**Image used:** [Your image description]
**Pros:** Text is more readable, professional
**Cons:** Image is partially obscured
