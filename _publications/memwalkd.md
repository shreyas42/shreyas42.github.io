---
title: "memwalkd : Accelerating Key-value stores using Page Table Walkers"
collection: publications
category: conference
permalink: /publication/memwalkd
excerpt: 'Accelerating Key-value stores using Page Table Walkers.'
date: 2022-12-18
venue: 'HiPC'
paperurl: 'https://ieeexplore.ieee.org/document/10106345'
citation: 'Anupindi et al.'
---
In-memory key-value stores (KVS) or caches form the backbone of many commercial and HPC applications. The basic operation of KVS revolves around storing or updating the mapping from keys to their corresponding values and looking up that mapping when requested by a client. We observe that the memory management unit (MMU) in modern processors does something similar – it looks up the mapping between virtual addresses and physical addresses stored in the per-process page table. We leverage the MMU to gain hardware acceleration for key-value lookup for free in a new key-value store design called memwalkd. We hash keys to unique virtual addresses. These addresses map to the physical addresses that hold the corresponding values. Thus, GET/SETs are performed by simply issuing loads/stores to the hash of a key. Across a wide range of workloads, memwalkd achieves 1.8× better throughput over a highly-optimized implementation of memcached called MICA.