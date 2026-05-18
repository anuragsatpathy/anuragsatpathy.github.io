---
layout: archive
title: "ReACT-TTC: Capacity-Aware Reassignment in Shared CPS"
permalink: /publications/react-ttc-iccps-2026/
author_profile: true
classes: wide
---

<section class="paper-spotlight">
  <p class="eyebrow">Featured Paper | ICCPS 2026 | CPS-IoT Week</p>
  <h1>ReACT-TTC: Capacity-Aware Top Trading Cycles for Post-Choice Reassignment in Shared Cyber-Physical Systems</h1>
  <p class="lead">
    A post-deviation reassignment framework for shared-resource CPS where human users may ignore assigned resources, update preferences, and require fast, voluntary, satisfaction-preserving reassignment.
  </p>
  <p class="spotlight-meta">
    <strong>Authors:</strong> Anurag Satpathy*, Arindam Khanda*, Chittaranjan Swain, and Sajal K. Das<br>
    <strong>Venue:</strong> 17th ACM/IEEE International Conference on Cyber-Physical Systems (ICCPS), CPS-IoT Week 2026, Saint-Malo, France<br>
    <strong>Keywords:</strong> Cyber-Physical Systems, Top Trading Cycles, EV charging, non-compliance, mechanism design, human-in-the-loop CPS
  </p>
  <p class="hero-actions">
    <a class="btn btn--primary" href="/files/react-ttc-iccps-2026.pdf">Paper PDF</a>
    <a class="btn btn--primary" href="/files/react-ttc-iccps-2026-slides.pptx">Slides</a>
    <a class="btn btn--inverse" href="https://arxiv.org/abs/2602.00859">arXiv</a>
  </p>
</section>

## Why This Matters

Cyber-Physical Systems increasingly assign shared physical resources such as EV chargers, parking spaces, edge servers, UAV communication links, and mobility services. These assignments are computed digitally, but executed by people and agents in the physical world. In practice, users often deviate from assigned resources because of queue length, travel distance, price, convenience, or local information.

When users do not comply, the system needs a fast way to recover without recomputing the entire allocation from scratch or disrupting users who already accepted their assignments. ReACT-TTC treats non-compliance as a first-class CPS problem and provides a lightweight reassignment layer for human-aware shared infrastructure.

## One-Minute Explanation

Imagine an EV driver is assigned to one charging station but decides to go elsewhere because another option looks closer or less crowded. ReACT-TTC lets the system collect updated preferences from affected users and perform voluntary, preference-driven exchanges while preserving important mechanism-design guarantees.

<div class="spotlight-flow">
  <div>Initial assignment</div>
  <div>User deviation</div>
  <div>Updated preferences</div>
  <div>Capacity-aware TTC exchange</div>
  <div>Improved reassignment</div>
</div>

## What We Did

We extend classical Top Trading Cycles (TTC) from one-to-one exchange settings to capacity-constrained shared-resource CPS. The framework works as a post-deviation layer on top of any base allocation algorithm and activates only when users deviate from prescribed assignments.

The paper addresses two structural CPS cases that classical TTC does not naturally handle:

- Resources with capacity, where multiple users may share one resource.
- Unassigned or idle capacity, where reassignment can use available resource slots without requiring strict one-to-one ownership.

We also incorporate a prospect-theoretic satisfaction model to better capture realistic user preferences compared with simple linear scoring.

## Key Contributions

<div class="contribution-grid">
  <div>
    <h3>Post-deviation CPS layer</h3>
    <p>Introduces a reassignment layer that augments existing CPS allocation algorithms and activates only when users deviate.</p>
  </div>
  <div>
    <h3>Capacity-aware TTC</h3>
    <p>Extends Top Trading Cycles to many-to-one shared resources with quotas, co-assigned capacity, and idle slots.</p>
  </div>
  <div>
    <h3>Mechanism guarantees</h3>
    <p>Preserves termination, Pareto efficiency, individual rationality, strategy-proofness, and core stability under the studied cases.</p>
  </div>
  <div>
    <h3>Human-aware satisfaction</h3>
    <p>Uses prospect-theoretic preferences to model how users perceive gains, losses, and satisfaction after reassignment.</p>
  </div>
</div>

## Key Result

<div class="result-callout">
  <strong>At least 43% improvement in user satisfaction</strong>
  <span>on real-world EV charging traces under non-compliant behavior, with minimal computation overhead.</span>
</div>

## CPS-IoT Week Presentation

I presented this work at CPS-IoT Week 2026 as part of ICCPS. The talk introduces classical TTC, explains why it fails in capacity-constrained CPS, and walks through the ReACT-TTC framework, theoretical guarantees, and EV charging case study.

<ul>
  <li><a href="/files/react-ttc-iccps-2026-slides.pptx">Download the CPS-IoT Week slides</a></li>
  <li><a href="/files/react-ttc-iccps-2026.pdf">Download the paper PDF</a></li>
  <li><a href="https://arxiv.org/abs/2602.00859">Read the arXiv version</a></li>
</ul>

## How This Fits My Research Agenda

ReACT-TTC is part of my broader research program on mechanism design for human-aware Cyber-Physical Systems. It connects algorithmic foundations with practical shared infrastructure problems where strategic behavior, capacity constraints, uncertainty, and user satisfaction interact.

This work directly supports my faculty research thrust on mechanism design for shared CPS infrastructure and motivates follow-on work in EV charging, intelligent transportation, public safety systems, and UAV-assisted logistics.

## Abstract

Cyber-physical systems (CPS) increasingly manage shared physical resources in the presence of human decision-making, where system-assigned actions must be executed by users or agents in the physical world. A fundamental challenge in such settings is user non-compliance: individuals may deviate from assigned resources due to personal preferences or local information, degrading system efficiency and requiring light-weight reassignment schemes.

This paper proposes a post-deviation reassignment framework for shared-resource CPS that operates on top of any initial allocation algorithm and is invoked only when users diverge from prescribed assignments. We advance the Top-Trading-Cycle (TTC) mechanism to enable voluntary, preference-driven exchanges after deviation events, and extend it to handle many-to-one resource capacities and unassigned resource conditions that are not supported by the classical TTC.

We formalize these structural cases, introduce capacity-aware cycle-detection rules, and prove termination along with the preservation of Pareto efficiency, individual rationality, and strategy-proofness. A Prospect-Theoretic preference model is further incorporated to capture realistic user satisfaction behavior. We demonstrate the applicability of this framework on an electric-vehicle charging case study using real-world data, where it increases user satisfaction and effective assignment quality under non-compliant behavior.

## Citation

```bibtex
@inproceedings{satpathy2026reactttc,
  title     = {ReACT-TTC: Capacity-Aware Top Trading Cycles for Post-Choice Reassignment in Shared CPS},
  author    = {Satpathy, Anurag and Khanda, Arindam and Swain, Chittaranjan and Das, Sajal K.},
  booktitle = {Proceedings of the 17th ACM/IEEE International Conference on Cyber-Physical Systems},
  series    = {ICCPS '26},
  year      = {2026},
  address   = {Saint-Malo, France},
  note      = {Accepted for publication}
}
```

<p><em>*Anurag Satpathy and Arindam Khanda contributed equally to this work.</em></p>
