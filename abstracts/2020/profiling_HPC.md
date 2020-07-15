<!-- Copyright (c) 2020 R. Tohid
Distributed under the Boost Software License, Version 1.0. (See accompanying
file LICENSE_1_0.txt or copy at http://www.boost.org/LICENSE_1_0.txt) -->

# Profiling 

## Problem
Profiling HPC software is a complex, multi-dimensional (many-dimensional?) process involving measurements in multiple levels of granularity in various frequencies. Therefore, there is a need for utilities, allowing profiling such systems in terms of memory-access efficiency, distribution of tasks and state of the threads carrying out such tasks, ...

## Approach
Show how data collected by sampling tasks, threads, operations, .... can be used to select better optimization policies both at compile and runtime.

## Contribution
1. clean API for collection and visualization of profiling data
2. how it's used for task launch (task inlining, splitting, ...)
3. improve memory access: tiling size, ...

## Future
ai managing adaptivity. q-learning