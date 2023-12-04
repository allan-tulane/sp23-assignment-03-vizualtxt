# CMPS 2200 Assignment 3
## Answers

**Name:**____Ali Sulehria


Place all written answers from `assignment-03.md` here for easier grading.






- **b.**

Work and span are linear, O(n), as they are iterative and of equal size (no parallelism, S(n) = W(n))


- **d.**

As per the notes, the work of scan is )(n). However, scan is according to S(n) = S(n/2) + 1, indicating a span of O(logn).


- **f.**

A map done in parallel will have its work as W(n) = 2W(n/2) + n, as the set splits with each iteration with linear work at each level. As this will have a height of log2 n with n nodes across, work is of the order O(n log n). The span will be, as before, of O(log n) since the tree simply splits in half at each level.