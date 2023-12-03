---
title: "Performance Analysis of Disruptive Instances in Cloud Environment"
collection: publications
permalink: /publications/publication_new1
excerpt: "This work studies the performance of spot instances via rigorous experimentation over commercial SPs such as Amazon AWS and Microsoft Azure. Real-world evaluations affirm that spot instances perform poorly compared to their on-demand counterpart concerning memory, CPU, disk read, and write operations."
date: 2023-11-07
venue: '2024 16th International Conference on Communication Systems & Networks (COMSNETS), Bengaluru, India'
classes: wide
---
## Authors
Pranab Nandy, Rounak Saha, **Anurag Satpathy**, Sandip Chakraborty, and Sourav Kanti Addya.

## Conference
*2024 16th International Conference on Communication Systems & Networks* (COMSNETS), **(Core Ranking - National India)**

## Abstract
Virtualization enables the service providers (SPs) to logically partition the resources into virtual machines (VM) instances. Real-world SPs such as Amazon, Google, Microsoft Azure, IBM, and Oracle provide different flavors of VM instances, such as on-demand, reserved, and low-cost or spot, depending on the type of application hosted. The on-demand instances are short-term and typically incur a higher cost than reserved instances that are provisioned for a longer duration at a discounted rate. Low-cost or spot instances are cost-effective compared to on-demand but are reclaimable by the SPs. The SPs often claim that the on-demand and spot instances achieve similar performance, but it is far from that. This paper studies the performance of spot instances via rigorous experimentation over commercial SPs such as Amazon AWS and Microsoft Azure. Real-world evaluations affirm that spot instances perform poorly compared to their on-demand counterpart concerning memory, CPU, disk read, and write operations. We identify such instances as disruptive and name them so because it does not fulfill the performance, durability, and flexibility expectations like an on-demand instance having the same configuration. We also perform hypothesis testing over the experimental data obtained to corroborate our claim further.