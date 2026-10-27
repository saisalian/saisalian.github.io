---
layout: home
list_title: Writing
---

<section class="hero">
  <p class="intro-kicker">Security engineer · Dublin</p>
  <h1 class="intro-title">Practical notes on Microsoft security, risk and AI governance.</h1>
  <p class="intro-text">My background is the Microsoft security stack (Defender, Sentinel, Entra ID, Intune and Purview), and I'm moving deeper into risk and governance. This is where I write up what I learn doing the work: what worked, what didn't, and the checklists I wish I'd had.</p>
  <p class="intro-cta"><a class="button" href="{{ '/about/' | relative_url }}">More about me <span aria-hidden="true">→</span></a></p>
</section>

<section class="topics" aria-label="What I write about">
  <div class="topic-card">
    <span class="topic-num">01</span>
    <h2>Microsoft 365 security</h2>
    <p>Configurations, detections and KQL, and the trade-offs behind them.</p>
  </div>
  <div class="topic-card">
    <span class="topic-num">02</span>
    <h2>Risk &amp; governance</h2>
    <p>Risk registers, policies and audits, and making security measurable.</p>
  </div>
  <div class="topic-card">
    <span class="topic-num">03</span>
    <h2>Copilot &amp; AI governance</h2>
    <p>Getting data access and labelling right before switching AI on.</p>
  </div>
</section>

{% if site.posts.size == 0 %}
<p class="empty-note">The first post is on its way. Check back soon.</p>
{% endif %}
