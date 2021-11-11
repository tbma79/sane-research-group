---
title: "Parallelizing Intra-Window Join on Multicores: An Experimental Study"
subtitle: ""
publication_types:
  - "1"
authors:
  - Shuhao Zhang
  - Yancan Mao
  - Jiong He
  - Philipp M. Grulich
  - Steffen Zeuch
  - Bingsheng He
  - admin
  - Volker Markl
doi: https://doi.org/10.1145/3448016.3452793
publication: In *ACM SIGMOD Conference, June 2021.*
publication_short: In *ACM SIGMOD Conference*
abstract: "The intra-window join (IaWJ), i.e., joining two input streams over a
  single window, is a core operation in modern stream processing applications.
  This paper presents the first comprehensive study on parallelizing the IaWJ on
  modern multicore architectures. In particular, we classify IaWJ algorithms
  into lazy and eager execution approaches. For each approach, there are further
  design aspects to consider, including different join methods and partitioning
  schemes, leading to a large design space. Our results show that none of the
  algorithms always performs the best, and the choice of the most performant
  algorithm depends on: (i) workload characteristics, (ii) application
  requirements, and (iii) hardware architectures. Based on the evaluation
  results, we propose a decision tree that can guide the selection of an
  appropriate algorithm."
draft: false
featured: false
tags: []
projects:
  - stream-systems
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-06-01T11:44:39.819Z
url_code: https://github.com/ADSC-Cloud/Elasticutor
---
