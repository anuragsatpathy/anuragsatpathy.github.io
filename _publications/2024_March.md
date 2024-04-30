---
title: "LEASE: Leveraging Energy-Awareness in Serverless Edge for Latency-Sensitive IoT Services"
collection: publications
permalink: /publications/2024_March
excerpt: "This paper proposes a framework LEASE that dynamically schedules resources in serverless functions catering to different microservices and adhering to their deadline constraint. "
date: 2024-04-23
venue: '2024 IEEE International Conference on Pervasive Computing and Communications Workshops and other Affiliated Events (PerCom Workshops)'
classes: wide
---
## Authors
Aastik Verma, **Anurag Satpathy**, Sajal K Das, Sourav Kanti Addya

## Conference
*2024 IEEE International Conference on Pervasive Computing and Communications Workshops and other Affiliated Events* (PerCom Workshops), **(Core Ranking - A_*)**

## Abstract
Resource scheduling catering to real-time IoT services in a serverless-enabled edge network is particularly challenging owing to the workload variability, strict constraints on tolerable latency, and unpredictability in the energy sources powering the edge devices. This paper proposes a framework LEASE that dynamically schedules resources in serverless functions catering to different microservices and adhering to their deadline constraint. To assist the scheduler in making effective scheduling decisions, we introduce a priority-based approach that offloads functions from over-provisioned edge nodes to under-provisioned peer nodes, considering the expended energy in the process without compromising the completion time of microservices. For real-world implementations, we consider a testbed comprising a Raspberry Pi cluster serving as edge nodes, equipped with container orchestrator tools such as Kubernetes and powered by OpenFaaS, an open-source serverless platform. Experimental results demonstrate that compared to the benchmarking algorithm, LEASE achieves a 23.34% reduction in the overall completion time, with 97.64% of microservices meeting their deadline. LEASE also attains a 30.10% reduction in failure rates.

[Download Paper Here](https://ieeexplore.ieee.org/abstract/document/10502788)
