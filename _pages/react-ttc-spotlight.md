---
layout: archive
title: "ReACT-TTC Spotlight"
permalink: /react-ttc-iccps-2026/
author_profile: true
classes: wide
---

<section class="page-intro">
  <p class="eyebrow">Featured paper</p>
  <h1>ReACT-TTC: Capacity-Aware Top Trading Cycles for Post-Choice Reassignment in Shared CPS</h1>
  <p class="lead">
    A mechanism-design approach for recovering shared cyber-physical systems when the original assignment is disrupted by human behavior, capacity limits, or changing preferences.
  </p>
  <div class="hero-actions">
    <a class="btn-primary" href="https://arxiv.org/abs/2602.00859">Read paper</a>
    <a class="btn-secondary" href="/files/react-ttc-iccps-2026-slides.pptx">Slides</a>
    <a class="btn-secondary" href="/publications/">Publications</a>
  </div>
</section>

<section class="spotlight-card">
  <div>
    <span class="tag">ICCPS 2026</span>
    <h2>Why this problem matters</h2>
    <p>
      Shared CPS often rely on an initial assignment: an EV is routed to a charger, a user is assigned a resource, or a system reserves capacity for a task. In practice, users may change their decisions, resources may become unavailable, and the system must recover without restarting from scratch.
    </p>
  </div>
  <div class="paper-facts">
    <div><strong>Domain</strong><span>Shared CPS and EV charging</span></div>
    <div><strong>Method</strong><span>Top trading cycles with capacity awareness</span></div>
    <div><strong>Goal</strong><span>Post-choice reassignment after disruption</span></div>
  </div>
</section>

## Main Contributions

<div class="mechanism-grid">
  <article>
    <span class="tag">Model</span>
    <h3>Post-choice reassignment</h3>
    <p>
      Frames reassignment as a recovery problem after an initial allocation, instead of treating every disruption as a fresh assignment problem.
    </p>
  </article>
  <article>
    <span class="tag">Mechanism</span>
    <h3>Capacity-aware TTC</h3>
    <p>
      Extends top trading cycles to support shared CPS settings where resource capacity and agent preferences both shape feasible exchanges.
    </p>
  </article>
  <article>
    <span class="tag">CPS relevance</span>
    <h3>Human-aware recovery</h3>
    <p>
      Targets real CPS behavior: agents do not always follow the plan, and infrastructure systems need principled ways to adapt.
    </p>
  </article>
</div>

## Where This Research Is Going

<section class="research-thread">
  <div class="thread-flow">
    <div><strong>ReACT-TTC</strong><span>capacity-aware recovery after initial choice</span></div>
    <div><strong>W-TTC</strong><span>weighted utility and priority-aware exchange</span></div>
    <div><strong>KATCH</strong><span>open-slot and capacity-aware reassignment framework</span></div>
    <div><strong>Applications</strong><span>EVs, UAV logistics, emergency response, edge/IoT</span></div>
  </div>
</section>

This line of work is part of my broader research agenda on game-theoretic, optimization-based, and learning-enabled decision-making for shared cyber-physical systems under uncertainty.
