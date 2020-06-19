#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) 0(n) - Although the value of 'n' is initially being multiplied by itself three times in the conditional:
    1 - The value of 'n' doesn't continue to grow as the comparison runs.
    2 - No matter the value of 'n', the value of 'a' is consistently (one could say linearly) gaining, based on 'n's fixed value of comparison.


b) 0(n^2) - The nested WHILE conditional is running for the length of the FOR loop 0(n(log(n))).


c) 0(n) - The 'bunnies' parameter is a single input which is being decremented at the same rate (not the same size, but still) the integer is being incremented. Also, it's only being affected by a single operation.

## Exercise II
I would probably use a binary search. The floors are probably (definitely) already sorted from lowest to highest, so from the first story, I'd find the middle floor and drop an egg from there. If the egg breaks, that mid point will be set as my new high point and I'd repeat the process.

The runtime of a binary search in 0(log(n)).
