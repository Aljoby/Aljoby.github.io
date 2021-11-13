---
title: "On SDN-Enabled Online and Dynamic Bandwidth Allocation for Stream Analytics"
collection: publications
permalink: /publication/2018-09-25-paper-title-number-1
excerpt: 'Data communication in cloud-based distributed stream data analytics often involves a collection of parallel and pipelined TCP flows. As the standard TCP congestion control mechanism is designed for achieving "fairness" among competing flows and is agnostic to the application layer contexts, the bandwidth allocation among a set of TCP flows traversing bottleneck links often leads to sub-optimal application-layer performance measures, e.g., stream processing throughput or average tuple complete latency. Motivated by this and enabled by the rapid development of the Software-Defined Networking (SDN) techniques, in this paper, we re-investigate the design space of the bandwidth allocation problem and propose a cross-layer framework which utilizes the additional information obtained from the application layer and provides on-the-fly and dynamic bandwidth adjustment algorithms for helping the stream analytics applications achieving better performance during the runtime. We implement a prototype cross-layer bandwidth allocation framework based on a popular open-source distributed stream processing platform, Apache Storm, together with the OpenDaylight controller, and carry out extensive experiments with real-world analytical workloads on top of a local cluster consisting of 10 workstations interconnected by a SDN-enabled switch. The experiment results clearly validate the effectiveness and efficiency of our proposed framework and algorithms.'
date: 2018-09-25
venue: 'IEEE ICNP'
paperurl: ''
citation: 'Walid Aljoby, Xin Wang, Tom Fu, Richard Ma. "On SDN-Enabled Online and Dynamic Bandwidth Allocation for Stream Analytics". <i>IEEE 26th International Conference on Network Protocols (ICNP)</i>, Cambridge, UK.'
---
<i> Abstract: </i> 

Data communication in cloud-based distributed stream data analytics often involves a collection of parallel and pipelined TCP flows. As the standard TCP congestion control mechanism is designed for achieving "fairness" among competing flows and is agnostic to the application layer contexts, the bandwidth allocation among a set of TCP flows traversing bottleneck links often leads to sub-optimal application-layer performance measures, e.g., stream processing throughput or average tuple complete latency. Motivated by this and enabled by the rapid development of the Software-Defined Networking (SDN) techniques, in this paper, we re-investigate the design space of the bandwidth allocation problem and propose a cross-layer framework which utilizes the additional information obtained from the application layer and provides on-the-fly and dynamic bandwidth adjustment algorithms for helping the stream analytics applications achieving better performance during the runtime. We implement a prototype cross-layer bandwidth allocation framework based on a popular open-source distributed stream processing platform, Apache Storm, together with the OpenDaylight controller, and carry out extensive experiments with real-world analytical workloads on top of a local cluster consisting of 10 workstations interconnected by a SDN-enabled switch. The experiment results clearly validate the effectiveness and efficiency of our proposed framework and algorithms.

[Download paper here](https://ieeexplore.ieee.org/document/8526818)