---
title: "Weighted Fair Caching: Occupancy-Centric Allocation for Space-Shared
  Resources"
subtitle: ""
publication_types:
  - "2"
  - "1"
authors:
  - Lianjie Shi
  - Xin Wang
  - admin
  - Y. C. Tay
doi: https://doi.org/10.1016/j.peva.2018.09.011
publication: In *Performance Evaluation Volumes 127–128, November 2018, Pages 194-211*
publication_short: In *IFIP Performance Conference*
abstract: >-
  Traditional cache replacement policies such as LRU and LFU were often designed
  with the focus on efficiency and aimed at maximizing the hit rates. However,
  the resource owners of modern computing systems such as cloud infrastructures
  and content delivery networks often have new objectives such as fairness and
  revenue to be optimized rather than the overall hit rate. A general resource
  management framework that allows resource owners to determine various resource
  allocations is desirable. Although such a mechanism like Weighted Fair
  Queueing (WFQ) exists for indivisible time-shared resources such as CPU and
  network bandwidth, no such counterpart exists for space-shared resources such
  as cache and main memory. 1
  In this paper, we propose Weighted Fair Caching (WFC), a capacity-driven cache policy that provides explicitly tunable resource allocations for cache owners in terms of the occupancy rates of contents. Through analysis of the continuous-time Markov Chain model of cache dynamics, we derive the closed-form occupancy rates as a function of the weights of contents, and various properties such as monotonicity and scaling of WFC. We show that WFC can be used to provide fair sharing of cache space among contents, as well as class-based service differentiations. We evaluate the performance of WFC using real data traces from two major video providers. We find that, compared to traditional cache policies, WFC provides better fairness while sacrificing an acceptable amount of hit rates.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2018-11-01T14:53:41.855Z
---
