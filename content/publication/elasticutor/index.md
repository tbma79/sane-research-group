---
title: "Elasticutor: Rapid Elasticity for Realtime Stateful Stream Processing"
subtitle: ""
publication_types:
  - "1"
authors:
  - Li Wang
  - Tom Z. J. Fu
  - admin
  - Marianne Winslett
  - Zhenjie Zhang
doi: https://doi.org/10.1145/3299869.3319868
publication: In *ACM SIGMOD Conference, June 30 - July 5, Amsterdam, The Netherlands, 2019.*
publication_short: In *ACM SIGMOD Conference*
abstract: "Elasticity is highly desirable for stream systems to guarantee low
  latency against workload dynamics, such as surges in arrival rate and
  fluctuations in data distribution. Existing systems achieve elasticity using a
  resource-centric approach that repartitions keys across the parallel
  instances, i.e., executors, to balance the workload and scale operators.
  However, such operator-level repartitioning requires global synchronization
  and prohibits rapid elasticity. We propose an executor-centric approach that
  avoids operator-level key repartitioning and implements executors as the
  building blocks of elasticity. By this new approach, we design the Elasticutor
  framework with two level of optimizations: i) a novel implementation of
  executors, i.e., elastic executors, that perform elastic multi-core execution
  via efficient intra-executor load balancing and executor scaling and ii) a
  global model-based scheduler that dynamically allocates CPU cores to executors
  based on the instantaneous workloads. We implemented a prototype of
  Elasticutor and conducted extensive experiments. We show that Elasticutor
  doubles the throughput and achieves up to two orders of magnitude lower
  latency than previous methods for dynamic workloads of real-world
  applications."
draft: false
featured: true
tags:
  - Apache Storm
projects:
  - stream-systems
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2019-06-03T04:07:44.641Z
url_code: https://github.com/ADSC-Cloud/Elasticutor
---
