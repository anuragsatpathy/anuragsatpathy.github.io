---
title: "Geo-distributed Multi-tier Workload Migration over Multi-timescale Electricity Markets"
collection: publications
permalink: /publications/publication2
date: 2023-04-17
excerpt: "Develops a VM migration model called Low Energy Application Workload Migration (LEWAM) aimed at reducing the per-bit migration cost in migrating VMs over Geo-distributed clouds. With a Geo-distributed cloud-connected through multiple ISPs, the work develops an approach to find out the migration path across ISPs leading to the most feasible destination."
venue: 'IEEE Transactions on Services Computing'
classes: wide
---
## Authors
Sourav Kanti Addya, **Anurag Satpathy**, Bishakh Chandra Ghosh, Sandip Chakraborty, Soumya K. Ghosh, and Sajal K. Das

## Journal

*IEEE Transactions on Services Computing* (**IF - 11.019**) (Accepted for Publication)

## Abstract
Virtual machine (VM) migration enables cloud service providers (CSPs) to balance workload, perform zero-downtime maintenance, and reduce applications' power consumption and response time. Migrating a VM consumes energy at the source, destination, and backbone networks, i.e., intermediate routers and switches, especially in a Geo-distributed setting. In this context, we propose a VM migration model called Low Energy Application Workload Migration ({\our}) aimed at reducing the per-bit migration cost in migrating VMs over Geo-distributed clouds. With a Geo-distributed cloud connected through multiple Internet Service Providers (ISPs), we develop an approach to find out the migration path across ISPs leading to the most feasible destination.
For this, we use the variation in the electricity price at the ISPs to decide the migration paths. 
However, reduced power consumption at the expense of higher migration time is intolerable for real-time applications. As finding an optimal relocation is NP-Hard, we propose an Ant Colony Optimization (ACO) based bi-objective optimization technique to strike a balance between migration delay and migration power.
A thorough simulation analysis of the proposed approach shows that the proposed model can reduce the migration time by 25%-30%$ and electricity cost by approximately 25% compared to the baseline. 

[Download Paper Here]()