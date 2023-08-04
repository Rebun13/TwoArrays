# TwoArrays

## Description

There are two _n_-element arrays of integers, _A_ and _B_. Permute them into some _A'_ and _B'_ such that the relation _A'[i] + B´[i] ≥ k_ holds for all _i_ where _0 ≤ i < n_.

There will be _q_ queries consisting of _A_, _B_ and _k_. For each query, return YES if some permutation _A'_, _B´_ satisfying the relation exists. Otherwise, return NO.

## Returns

- string: either _YES_ or _NO_


## Input Format

The first line contains an integer _q_, the number of queries.

The next _q_ sets of _3_ lines are as follows:

- The first line contains two space-separated integers _n_ and _k_, the size of both arrays _A_ and _B_, and the relation variable.
- The second line contains _n_ space-separated integers _A[i]_.
- The third line contains _n_ space-separated integers _B[i]_.
