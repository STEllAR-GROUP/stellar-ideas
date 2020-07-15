<!-- Copyright (c) 2020 R. Tohid
Distributed under the Boost Software License, Version 1.0. (See accompanying
file LICENSE_1_0.txt or copy at http://www.boost.org/LICENSE_1_0.txt) -->

# Case Study: Performance of HPC Software Run on HPX

## Problem

Asynchronous many-task (AMT) runtime systems manage computation and
communications in parallel and distributed systems and it is critical to
evaluate their performance.

## Approach

Study the performance of a runtime system (1) in different application
domains and (2) on multiple architectures.

## Contribution

We study performance of HPX in Blaze linear algebra, Phylanx array processing, 
and possibly computational science libraries such as FleCSI, or OctoTiger.

## Why HPX

* It is already used in many applications running HPC systems.

* Comes with APEX performance measuring tool which simplifies further analyses.

* In the case of Phylanx, we can also measure performance at the coarser primitive level.
