---
title:          "NeuChain: A Fast Permissioned Blockchain System with Deterministic Ordering"
date:           2022-07-01 00:01:00 +0800
selected:       true
pub:            "Proceedings of the VLDB Endowment (PVLDB)"
pub_date:       "2022"
abstract: >-
  Blockchain serves as a replicated transactional processing system in a trustless distributed environment. Existing blockchain systems all rely on an explicit ordering step to determine the global order of transactions that are collected from multiple peers. The ordering consensus can be the bottleneck since it must be Byzantine-fault tolerant and can scarcely benefit from parallel execution. In this paper, we propose an ordering-free architecture that makes ordering implicit through deterministic execution. Based on this novel architecture, we develop a permissioned blockchain system NeuChain. A number of key optimizations such as asynchronous block generation and pipelining are leveraged for high throughput and low latency. Several security mechanisms are also designed to make our system robust to malicious attacks. Our geo-distributed experimental results show that NeuChain can achieve 47.2-64.1x throughput improvement over HyperLedger Fabric and 1.6-12.2x throughput improvement over the state-of-the-art high performance blockchains.
cover:          /assets/images/covers/neuchain-vldb22.png
authors:
- Zeshun Peng
- Yanfeng Zhang
- Qian Xu
- Haixu Liu
- Yuxiao Gao
- Xiaohua Li
- Ge Yu
links:
  Paper: /assets/paper/neuchain-vldb22.pdf
  DOI: https://doi.org/10.14778/3551793.3551816
  Code: https://github.com/iDC-NEU/NeuChain
  Slides: /assets/slides/neuchain-vldb22.pdf
---