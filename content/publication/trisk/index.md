---
title: "Trisk: Task-Centric Data Stream Reconfiguration"
publication_types:
  - "1"
authors:
  - Yancan Mao
  - Yuan Huang
  - Runxin Tian
  - Xin Wang
  - admin
doi: https://doi.org/10.1145/3472883.3487010

url_video: 'https://www.youtube.com/watch?v=LLgts15o6mQ'

publication: In *the ACM Symposium on Cloud Computing, Seattle, WA, USA,
  Novermber 1st-4th, 2021*
publication_short: In *ACM Symposium on Cloud Computing (SoCC)*
abstract: Due to the long-run and unpredictable nature of stream processing, any
  statically configuredexecution of stream jobs fails to process data in a
  timely and efficient manner. To achieve performance requirements, stream jobs
  need to be reconfigured dynamically. In this paper, we present Trisk, a
  control plane that support versatile reconfigurations while keeping high
  efficiency with easy-to-use programming APIs. Trisk enables versatile
  reconfigurations with usability based on a task-centric abstraction, and
  encapsulates primitive operations such that reconfigurations can be described
  by compositing the primitive operations on the abstraction. Trisk adopts a
  partial pause-and-resume design for efficiency, through which synchronization
  mechanisms in the native stream systems can further be leveraged. We implement
  Trisk on Apache Flink and demonstrate its usage and performance under
  realistic application scenarios. We show that Trisk executes reconfigurations
  with shorter completion time and comparable latency compared to a
  state-of-the-art fluid mechanism for state management.
draft: false
featured: false
tags:
  - Apache Flink
image:
  filename: featured
  focal_point: Smart
  preview_only: false
url_code: https://github.com/sane-lab/Trisk  
date: 2021-11-06T15:01:13.565Z
---
