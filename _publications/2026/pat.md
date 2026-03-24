---
title:          "PAT: Towards Transaction Routing with Page Affinity in Shared-Cache Databases"
date:           2026-07-06 00:01:00 +0800
selected:       true
pub:            "IEEE International Conference on Data Engineering (ICDE) (CCF-A)"
pub_date:       "2026"

#abstract: >-
#  Shared-cache architectures decouple compute from storage and employ local caches in compute nodes to reduce the latency of accessing shared storage, achieving high availability and elasticity. However, this design suffers from local cache misses and cache coherence overhead. Transaction routing has been widely used to mitigate these issues by routing transactions that access the same data to the same nodes, improving cache locality. Most existing routing approaches rely on row affinity, i.e., routing transactions that access the same set of rows to the same nodes. Since shared-cache databases typically maintain distributed cache coherence at the page level, this mismatch can cause redundant coherence traffic and degrade performance. In this paper, we present PAT, a shared-cache database system with page affinity-based routing, which routes transactions that access frequently co-accessed pages to the same compute node, reducing local cache misses and cache coherence overhead. Since SQL does not reveal which pages will be accessed before execution, PAT abstracts pages using key ranges to enable page affinity-based routing. This is based on the ordering property of widely used clustered indexes. Moreover, page updates may cause key ranges to become misaligned with pages, leading to significant cache coherence overhead. To address this issue, we introduce the route-aware page reorganization mechanism. Experiments show that PAT achieves 1.03×-14.36× higher throughput than state-of-the-art approaches under TPC-C and YCSB.

cover:          /assets/images/covers/pat-icde26.png
authors:
  - Zhongqin Tan
  - Haoyuan Zhang
  - Yanfeng Zhang#
  - Zeshun Peng#
  - Weixing Zhou
  - Jinyu Zhang
  - Yang Ren
  - Guoliang Li
  - Ge Yu
links:
  Paper: /assets/paper/pat-icde26.pdf
#  Code: https://github.com/iDC-NEU/PAT
#  Slides: /assets/slides/pat-icde26.pdf
---
