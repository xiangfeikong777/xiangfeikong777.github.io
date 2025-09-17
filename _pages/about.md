---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I am **Xiangfei Kong**! I am a Computer Science and Engineering Ph.D. student at the University of South Florida and joined the RARE Lab in October 2023 as a M.S. student. 

## Academic Background
I completed my Bachelor of Arts degree from Qufu Normal University in China and my dual M.S. in Marketing and Computer Science from USF. In addition, I received a Pathway to Computing Graduate Certificate in Spring 2023 before transitioning from marketing to CS.

## Research Interests
My main research interest is leveraging augmented reality (AR) for the replicability and reproducibility of empirical experiment results. Specifically, I am investigating whether AR virtual robots can be a possible replacement for physical robots in some empirical research focusing on subjective experience.

## Recent Publications

{% include base_path %}

<!-- Display recent publications -->
{% assign recent_publications = site.publications | sort: 'date' | reverse | slice: 0, 3 %}
{% for post in recent_publications %}
  <div class="publication-item" style="margin-bottom: 1.5em; padding-bottom: 1em; border-bottom: 1px solid #eee;">
    <h3 style="margin-bottom: 0.5em;">
      <a href="{{ base_path }}{{ post.url }}" rel="permalink" style="text-decoration: none;">{{ post.title }}</a>
    </h3>
    <p style="margin-bottom: 0.5em; color: #666; font-size: 0.9em;">
      <strong>{{ post.venue }}</strong> • {{ post.date | date: "%B %Y" }}
    </p>
    {% if post.excerpt %}
      <p style="margin-bottom: 0.5em;">{{ post.excerpt | strip_html | truncate: 200 }}</p>
    {% endif %}
  </div>
{% endfor %}

<p style="text-align: center; margin-top: 1.5em;">
  <a href="{{ base_path }}/publications/" class="btn btn--primary">View All Publications</a>
</p>

## Latest News

<!-- Display recent news items -->
<div class="news-section">
  <div class="news-item" style="margin-bottom: 1em; padding-bottom: 0.8em; border-bottom: 1px dotted #ccc;">
    <h4 style="margin-bottom: 0.3em; color: #333;">August 25, 2025</h4>
    <p style="margin-bottom: 0;">Started the PhD Computer Science program at University of South Florida!</p>
  </div>
  
  <div class="news-item" style="margin-bottom: 1em; padding-bottom: 0.8em; border-bottom: 1px dotted #ccc;">
    <h4 style="margin-bottom: 0.3em; color: #333;">August 14, 2025</h4>
    <p style="margin-bottom: 0;">Awarded the Rada Scholarship in AI and Healthcare for the 2025-2026 school year!</p>
  </div>
  
  <div class="news-item" style="margin-bottom: 1em; padding-bottom: 0.8em; border-bottom: 1px dotted #ccc;">
    <h4 style="margin-bottom: 0.3em; color: #333;">August 9, 2025</h4>
    <p style="margin-bottom: 0;">Graduated with dual degrees: MS Marketing and MS Computer Science from University of South Florida!</p>
  </div>
  
  <div class="news-item" style="margin-bottom: 1em; padding-bottom: 0.8em; border-bottom: 1px dotted #ccc;">
    <h4 style="margin-bottom: 0.3em; color: #333;">June 3, 2025</h4>
    <p style="margin-bottom: 0;">Successfully defended my MS thesis!</p>
  </div>
  
  <div class="news-item" style="margin-bottom: 1em; padding-bottom: 0.8em; border-bottom: 1px dotted #ccc;">
    <h4 style="margin-bottom: 0.3em; color: #333;">March 16, 2024</h4>
    <p style="margin-bottom: 0;">Presented research work at <strong>HRI 2024</strong> conference!</p>
  </div>
</div>

<p style="text-align: center; margin-top: 1.5em;">
  <a href="{{ base_path }}/News/" class="btn btn--primary">View All News</a>
</p>
