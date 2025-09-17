---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-download-section" style="text-align: center; margin-bottom: 2em; padding: 20px; background-color: var(--global-bg-color); border: 2px solid #0092ca; border-radius: 10px;">
  <h2 style="color: #0092ca; margin-bottom: 15px;">📄 Download CV</h2>
  <p style="margin-bottom: 20px;">Click the button below to download my complete CV as a PDF file.</p>
  <a href="{{ base_path }}/files/Xiangfei_Kong_CV.pdf" class="btn btn--primary" style="font-size: 1.1em; padding: 12px 24px;" download>
    <i class="fas fa-download"></i> Download CV (PDF)
  </a>
  <p style="margin-top: 15px; font-size: 0.9em; color: var(--global-text-color-light);">
    Last updated: <span id="cv-update-date">{{ "now" | date: "%B %Y" }}</span>
  </p>
</div>

---

## Education

**Ph.D. in Computer Science** (2025 - Present)  
University of South Florida, Tampa, FL  
*Research Focus: Augmented Reality for Human-Robot Interaction*

**M.S. in Computer Science** (2023 - 2025)  
University of South Florida, Tampa, FL  
*Thesis: Bridging Virtual Robots and Physical Faces via Augmented Reality*

**M.S. in Marketing** (2023 - 2025)  
University of South Florida, Tampa, FL

**Pathway to Computing Graduate Certificate** (2023)  
University of South Florida, Tampa, FL

**Bachelor of Arts** (2009 - 2013)  
Qufu Normal University, China

## Research Experience

**Graduate Research Assistant** (Oct 2023 - Present)  
RARE Lab, University of South Florida  
*Supervisor: Dr. [Supervisor Name]*
- Investigating augmented reality applications for human-robot interaction
- Developing AR virtual robots as replacements for physical robots in empirical studies
- Focus on replicability and reproducibility of empirical experiment results

## Teaching Experience

**Teaching Assistant** (Oct 2024 - Present)  
University of South Florida, Computer Science Department
- CIS4930.002F25/CAP6110.001F25 Augmented Reality (Fall 2025, 25 students)
- CIS3433 System Integration & Architecture (Spring 2025, 68 students)  
- COP4600 Operating Systems (Fall 2024, 90 students)

**Instructor - College Chinese** (Sep 2009 - May 2015)  
Qilu Institute of Technology, China
- Full-time Chinese language instruction
- Curriculum development and classroom management

## Skills & Expertise

**Programming Languages**
- Python, C++, Java, C#, JavaScript, HTML/CSS

**Technologies & Frameworks**
- Unity 3D, Augmented Reality (AR), ROS (Robot Operating System)
- HoloLens 2, Mixed Reality Toolkit (MRTK)
- Git/GitHub, Jekyll, Gazebo Simulation

**Research Areas**
- Human-Robot Interaction, Augmented Reality, Virtual Robotics
- Empirical Study Design, Replicability in HRI Research

## Publications
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## Mentoring Experience
<ul>{% for post in site.mentoring reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## Awards & Recognition

**Rada Scholarship in AI and Healthcare** (2025-2026)  
University of South Florida

## Professional Development

**Graduate Student Mentorship Training** (2025)  
University of South Florida
