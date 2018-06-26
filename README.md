## Synopsis
The goal of this problem is to implement the "Median Maintenance" algorithm (covered in the Week 3
lecture on heap applications). The text file contains a list of the integers from 1 to 10000 in
unsorted order; you should treat this as a stream of numbers, arriving one by one.

Compute the sum of these 10000 medians, modulo 10000 (i.e., only the last 4 digits). That is, you
should compute (m1 + m2 + ... + m10000) mod 10000, where constants next to m represent the ith
order statistic in the set of 10000 medians.

Also, compare the performance achieved by heap-based and search-tree-based implementations of the
algorithm.

## Motivation

The median maintenance algorithm utilizes a heap to achieve O(logn) time complexity for most operations.

## Acknowledgements

This algorithm is part of the Stanford University Algorithms 4-Course Specialization on Coursera, instructed by Tim Roughgarden.
