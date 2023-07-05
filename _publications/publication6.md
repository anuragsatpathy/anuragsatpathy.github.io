---
title: "A service sustainable live migration strategy for multiple virtual machines in cloud data centers"
collection: publications
permalink: /publications/publication6
excerpt: "This work proposes a modified serial migration strategy to schedule multiple virtual machines (VMs) migration based on the pre-copy live migration technique aimed at reducing migration overheads in terms of migration time and downtime."
date: 2021-07-15
venue: 'Big Data Research, Elsevier'
classes: wide
---
## Authors
 **Anurag Satpathy**, Manmath Narayan Sahoo, Ashutosh Mishra, Banshidhar Majhi, Joel JPC Rodrigues, Sambit Bakshi.

## Journal 
*Big Data Research, Elsevier* (**IF - 3.3**)

## Abstract
Virtual machine (VM) migration is an indispensable aspect of a virtualized cloud environment. It assists in resource management by dynamically relocating VMs from one physical machine to another. This is an essential aspect especially for big data applications that are prone to variable workloads and often demand relocation of resources in terms of VMs. However, such applications not only experience stochastic workloads but also have stringent requirements on the maximum tolerable latency. To address such issues, VMs are often relocated using live VM migration. VM migration is associated with overheads, hence, in this paper, we propose a modified serial migration strategy to migrate multiple VMs based on the pre-copy live migration technique. We propose to interleave the pre-copy stages in such a way that a balance is achieved between the migration time and downtime overheads. The proposed technique is compared with the state-of-the-art serial, parallel, and improved serial migration strategies. Concerning downtime, the proposed approach performs exceptionally well compared to both serial and improved serial methods. The downtime of the proposed scheme and parallel are comparative for read-intensive applications (low dirtying rates). However, for write-intensive applications (high dirtying rates) the former significantly outperforms the latter. The migration time performance of the proposed scheme is observed to be much better than that of the parallel technique and is slightly higher than those of serial and improved serial techniques.

[Download Paper Here](https://doi.org/10.1016/j.bdr.2021.100213)
