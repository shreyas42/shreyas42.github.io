---
title: "An Extensible Framework for Task Partitioning on Heterogeneous Systems"
collection: publications
category: conference
permalink: /publication/hetero
excerpt: 'Task partitioning framework for heterogeneous systems.'
date: 2022-05-27
venue: 'INCET'
paperurl: 'https://ieeexplore.ieee.org/document/9825025'
citation: 'Yekbote et al.'
---

High performance computing applications have witnessed significant speedups in performance from leveraging the compute capabilities of heterogeneous platforms. These speedups are seldom taken advantage of in practice partly due to the inefficacy of mapping parallel sections of an application to specific processing units. Ascertaining this mapping necessitates taking into account the run time and compile time features of the application on a heterogeneous platform. This paper proposes a framework capable of classifying a high performance computing application to its optimal partitioning in a heterogeneous CPU-GPU target system. This classifier has been trained on a combination of run time execution metrics and compile time static code features of applications from different domains collected from benchmark suites such as Rodinia [1] and OmpSCR [2]. The contribution of this work is twofold - an extensible framework demonstrating the utility of accurate mapping and a pair of data sets that exhibit the significance of run time and compile time features on the framework estimating the effect of varied input type and size.