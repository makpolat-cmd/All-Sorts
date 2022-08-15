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

# Merge-Sort

The Merge Sort algorithm is a sorting algorithm that is considered an example of the divide and conquer strategy.

Our array is = [16 21 11 8 12]

1. [16 21 11] [8 12 22]
2. [16 21] [11] [8 12] [22]
3. [16] [21] [11] [8] [12] [22]
4. [16 21] [8 11] [12 22]
5. [8 11 16 21] [12 22]
6. [8 11 12 16 21 22]

Big-O = O(nlogn) = O(6*log6)


# Binary-Search-Tree 

Our array is = [7 5 1 8 3 6 0 9 4 2]

|             |  |  |     |  |  |  |  |  |  |  |  |
|--           |--|--|-    |- |- |- |- |- |- |- |- |
|             |  |  |     |  |  |  | 7|  |  |  |  |  
|             |  |  |     |  |  | /|  |\ |  |  |  | 
|             |  |  |     |  | 5|  |  |  |8 |  |  | 
|             |  |  |     | /|  |\ |  |  |  |\ |  | 
|             |  |  | 1   |  |  |  |6 |  |  |  | 9|
|             |  | /|     |\ |  |  |  |  |  |  |  |
|             | 0|  |     |  | 3|  |  |  |  |  |  |
|             |  |  |     | /|  |\ |  |  |  |  |  |
|             |  |  |   2 |  |  |  |4 |  |  |  |  |
