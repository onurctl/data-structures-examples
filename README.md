# Data Structures Examples
Some sorting &amp; searching algorithms, time complexities

# Insertion sort
Start: [22,27,16,2,18,6]

[22,16,27,2,18,6]

[16,22,27,2,18,6]

[16,22,2,27,18,6]

[16,2,22,27,18,6]

[2,16,22,27,18,6]

[2,16,22,18,27,6]

[2,16,18,22,27,6]

[2,16,18,22,6,27]

[2,16,18,6,22,27]

[2,16,6,18,22,27]

Finish: [2,6,16,18,22,27]

O(n^2)

After sorting, number 18 is in average case for time complexity.

# Selection sort
First 4 steps:

Start: [7,3,5,8,2,9,4,15,6]

[7,3,5,8,2,9,4,6,15]

[7,3,5,8,2,6,4,9,15]

[7,3,5,4,2,6,8,9,15]

[6,3,5,4,2,7,8,9,15]

# Merge sort

                                  16,21,11,8,12,22
                  16,21,11                                8,12,22
            16,21          11                         (already sorted)
          16     21          11


                  11,16,21                                8,12,22


                                  8,11,12,16,21,22

O(nLogn)

# Binary search tree

[7,5,1,8,3,6,0,9,4,2]

                      7
              5              8
          1       6              9
        0   3
           2 4

