<!-- Copyright (c) 2020 R. Tohid
Distributed under the Boost Software License, Version 1.0. (See accompanying
file LICENSE_1_0.txt or copy at http://www.boost.org/LICENSE_1_0.txt) -->

# JIT Code Generation for PhySL Expression Trees.
to our knowledge no framework tries to jointly optimize the choice of which fragments of a computation should run on which device with the choice of how to structure the sub-computations within a device[[1](https://dl.acm.org/doi/pdf/10.1145/3317550.3321441?casa_token=0qiAy0aZ5icAAAAA:OFRfMm_LXd7nqZnCblXTTj9_a9ytx6YMy6jgrFVn7BxOgISkr5bAnByfo2o7oEiT0xHTDiWiTfU)]


## Data

Extend :class: `numpy.nd` to support distributed and GPU arrays.

## Computation
- user-defined tasks
- task order / dependency 
- representations

## Code generation
- PhySL
- ISL

## Optimization
- Polyhedral
