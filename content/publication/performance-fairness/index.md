---
title: Towards Application Performance Fairness on Clouds
subtitle: ""
publication_types:
  - "1"
authors:
  - Rengan Dou
  - Xin Wang
  - admin
doi: https://doi.org/10.1145/3409963.3410495
publication: In *The 11th ACM SIGOPS Asia-Pacific Workshop on Systems (APSys), 2020.*
publication_short: In *ACM SIGOP APSys*
abstract: In cloud computing, resource allocation is the key building block.
  Existing resource allocation strategies are designed for multi-tenant cases
  and the majority of them target resource fairness and utilization. We consider
  the problem of resource allocation among multiple applications that belong to
  a single user. In this case, instead of resource fairness, the user cares
  about performance fairness. We focus on memory, one of the most universal
  resources used by applications. We mainly face two challenges. The first one
  is how to characterize the performance of various applications. We carefully
  choose User time, the number of CPU jiffies spending on the User mode, as a
  representative of the application's progress to reflect the performance of the
  application. Through a series of processing, we make performance comparable
  among different applications. The other challenge is to ensure high system
  memory utilization. We address this challenge by designing an adaptive memory
  allocation algorithm that guarantees high memory utilization and performance
  fairness simultaneously through dynamically reallocating memory among
  applications. We have implemented our algorithm by developing a scheduler on a
  physical machine where multiple applications share resources. Experimental
  evaluation shows that our algorithm can achieve good performance fairness on
  the premise of ensuring high memory utilization with different applications
  and importance.
draft: false
featured: false
tags:
  - Apache Storm
projects:
  - cloud-native-systems
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2020-08-01T13:11:56.558Z
---
