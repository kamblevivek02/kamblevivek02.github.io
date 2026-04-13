---
layout: page
title: Test Style 5 - Left Aligned Hero
permalink: /test5/
nav: false
---

<style>
  .hero-left {
    background-image: url('/assets/img/background1.jpg');
    background-size: cover;
    background-position: center;
    padding: 80px 40px;
    border-radius: 10px;
    margin-bottom: 40px;
    position: relative;
    z-index: 1;
  }
  .hero-left::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: rgba(0, 0, 0, 0.5);
    border-radius: 10px;
    z-index: -1;
  }
  .hero-left h1, .hero-left h3, .hero-left p {
    position: relative;
    z-index: 2;
    color: white;
    text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
  }
  .hero-left h1 {
    font-size: 3rem;
    margin-bottom: 0.5rem;
  }
  .hero-left h3 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
    color: #f0f0f0;
  }
  .hero-left p {
    font-size: 1.2rem;
    max-width: 600px;
    line-height: 1.5;
  }
  .btn-custom {
    display: inline-block;
    margin-top: 20px;
    padding: 12px 24px;
    background-color: #3498db;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s;
  }
  .btn-custom:hover {
    background-color: #2980b9;
  }
  .btn-custom-secondary {
    background-color: #2c3e50;
    margin-left: 10px;
  }
  .btn-custom-secondary:hover {
    background-color: #1a252f;
  }
  .feature-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    margin: 40px 0;
  }
  .feature-card {
    padding: 20px;
    border-radius: 10px;
    background: var(--global-card-bg, #f8f9fa);
    border: 1px solid var(--global-border-color, #e8e8e8);
  }
  .feature-card h3 {
    margin-top: 0;
  }
</style>

## Style 5: Left-Aligned Hero with Overlay

<div class="hero-left">
  <h1>Vivek Kamble</h1>
  <h3>Cybersecurity & GRC Professional</h3>
  <p>Bridging Governance, Risk & Compliance with AI-driven security solutions. 16+ years of experience helping organizations turn security into a business enabler.</p>
  <a href="/about/" class="btn-custom">Learn More About Me →</a>
  <a href="/projects/" class="btn-custom btn-custom-secondary">View My Projects →</a>
</div>

## 🔐 What I Do

<div class="feature-grid">
  <div class="feature-card">
    <h3>📋 Governance</h3>
    <p>Security frameworks, policies, and enterprise compliance strategies</p>
  </div>
  <div class="feature-card">
    <h3>⚠️ Risk Management</h3>
    <p>Vendor risk assessments, gap analysis, and mitigation planning</p>
  </div>
  <div class="feature-card">
    <h3>✅ Compliance</h3>
    <p>Audit navigation, regulatory readiness, and process optimization</p>
  </div>
  <div class="feature-card">
    <h3>🤖 AI & Security</h3>
    <p>Leveraging AI for threat detection, automation, and risk prediction</p>
  </div>
  <div class="feature-card">
    <h3>📊 Audits</h3>
    <p>Internal/external audit coordination, evidence collection, and finding remediation</p>
  </div>
  <div class="feature-card">
    <h3>🛡️ Cybersecurity Projects</h3>
    <p>End-to-end program delivery, ISO 27001 certification, and TPRM implementation</p>
  </div>
</div>

## 🚀 Emerging Focus Areas

- **AI Governance & Ethics** - Responsible AI frameworks
- **Cloud Security Posture Management** - CSPM implementation
- **Zero Trust Architecture** - Modern security models
- **Cyber Resilience** - Business continuity & incident response

## 📢 Featured Insight

> "In 2025 and beyond, cybersecurity isn't just about defense—it's about enabling business innovation securely. GRC professionals must embrace AI as both a tool and a governance challenge."

---

**Image used:** background1.jpg
**Pros:** Professional, text is highly readable, left alignment feels modern
**Cons:** Dark overlay may mute image colors
