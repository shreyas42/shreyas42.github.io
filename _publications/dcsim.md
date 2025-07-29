---
title: "DCSim: Cooling Energy Aware VM Allocation Framework for a Cloud Data Center"
collection: publications
category: conference
permalink: /publication/dcsim
excerpt: 'Simulation framework for energy aware VM allocation in a cloud data center.'
date: 2019-04-04
venue: 'ICACCE'
paperurl: 'https://ieeexplore.ieee.org/document/9079962'
citation: 'Bhandia et al.'
---

Explosion of digital content has resulted in large amounts of resources being provisioned and managed for various applications in cloud Data Centers. Energy consumption in these large Cloud Data Centers is a rising concern, accounting for 1.3% of the worlds electricity consumption [1]. Data Center cooling accounts for 40% of this energy consumption [2]. Of the various mechanisms available for studying the energy consumption in Data Centers, a simulation based approach is quite popular. In this paper, we propose DCSim, a configurable extension to CloudSim, a popularly used cloud infrastructure and simulation framework. CloudSim provides coarse power models to calculate total energy consumption in a Data Center for a given workload, but has no provision to factor in the Data Center topology and current cooled area into this power model. This makes building intelligent cooling energy aware allocation policies in CloudSim difficult. In DCSim, we introduce a novel Data Center model that addresses the shortcomings of CloudSim by encapsulating concepts of Racks, Aisles, Sectors and Zones (collectively referred to as DCObjects). We also provide the capability to model the cooling of these DCObjects. This makes the study of cooling aware resource provisioning for workloads easier. The DCObjects and the Data Center model presented are designed to be fully extensible to support future developments in this area. In this work we also implement a Cooling aware VM allocation policy, and demonstrate using multiple algorithms, that this VM allocation policy will effectively reduce the total Data Center power consumption by 18.18% over an algorithm which does not factor in the cooled DCObjects.