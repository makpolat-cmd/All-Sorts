# Insertion-Sort

1)- It allows us to sort the sequence of numbers we have in the simplest way. First value of array took and change with smallest value. This process repeat again and again until sequence sort like smallest to highest value.

Our array = [22 27 16 2 18 6]

1. [2 27 16 22 18 6]
2. [2 6 16 22 18 27]
3. [2 6 16 18 22 27]

2)- Big-O notation = n + (n-1) + (n-2) + ... + 1 = (n*(n+1))/2 = ((n^2) + n)/2 
The dominant part is n^2 so O(n^2).

3)- After we sort numbers with insertion-sort, 18 will be average case.

4)- [7,3,5,8,2,9,4,15,6] write first 4 step of insertion-sort of this array.

1. [2 3 5 8 7 9 4 15 6]
2. [2 3 4 8 7 9 5 15 6]
3. [2 3 4 5 7 9 8 15 6]
4. [2 3 4 5 6 9 8 15 7]
