---
title:          "MassBFT: Fast and Scalable Geo-Distributed Byzantine Fault-Tolerant Consensus"
date:           2025-07-01 00:01:00 +0800
selected:       true
pub:            "IEEE International Conference on Data Engineering (ICDE)"
pub_date:       "2025"
abstract: >-
  Geo-distributed consensus protocols provide high availability and resilience for distributed database services. These protocols group nodes by their data centers to leverage the network topology that spans across multiple data centers, thereby reducing costly cross-datacenter communication. However, they still face performance and scalability challenges due to inefficient log replication mechanisms. 1) These protocols rely on the leader node in each group to perform cross-datacenter log replication, creating a single-node performance bottleneck. 2) Byzantine receivers can behave arbitrarily, forcing the group leader to send multiple log copies during replication to prevent loss, thus causing redundant transmissions. 3) Since all groups must execute these logs in the same order, synchronizations across groups are necessary to maintain consistency when multiple groups are proposing concurrently, which also slow down log replication. This paper presents MassBFT, a Byzantine fault-tolerant geo-consensus protocol that achieves high performance and scalability. We design an encoded bijective log replication to eliminate the leader bottleneck and reduce the cross-datacenter network consumption. We also propose asynchronous log ordering to eliminate synchronization across groups. Experimental results show that MassBFT is scalable, fault-tolerant, and outperforms state-of-the-art protocols with 5.49-29.96 times higher throughput under YCSB, SmallBank, and TPC-C workloads.
cover:          /assets/images/covers/massbft-icde25.png
authors:
- Zeshun Peng
- Yanfeng Zhang
- Tinghao Feng
- Weixing Zhou
- Xiaohua Li
- Ge Yu
links:
  Paper: /assets/paper/massbft-icde25.pdf
  Code: https://github.com/iDC-NEU/MassBFT
  Slides: /assets/slides/massbft-icde25.pptx
---
