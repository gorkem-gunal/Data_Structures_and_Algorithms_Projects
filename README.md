# Data_Structures_and_Algorithms_Projects
Data Structures and Algorithms projects of the patika.dev course
## Selection/İnsertion Sort
**Q1)**
```
[22,27,16,2,18,6]
```
**a)** Write the stages according to the type of the sequence given above. (Yukarı verilen dizinin insertion sort türüne göre aşamalarını yazınız.)
 ```
 Answer a)
   Step 1: [22,27,16,2,18,6] //Since 22 is already lesser than 27 no sorting was done.
   Step 2: [22,16,27,2,18,6] // 16 is less than 27 so change places with 27.
   Step 3: [16,22,27,2,18,6] // 16 is less than 22 so change places with 22.
   Step 4: [16,22,2,27,18,6] // 2 is less than 27 so change places with 27.
   Step 5: [16,2,22,27,18,6] // 2 is less than 22 so change places with 22.
   Step 6: [2,16,22,27,18,6] // 2 is less than 16 so change places with 16.
   Step 7: [2,16,22,18,27,6] // 18 is less than 27 so change places with 27.
   Step 8: [2,16,18,22,27,6] // 18 is less than 22 so change places with 22.
   Step 9: [2,16,18,22,6,27] // 6 is less than 27 so change places with 27.
   Step 10: [2,16,18,6,22,27] // 6 is less than 22 so change places with 22.
   Step 11: [2,16,6,18,22,27]  // 6 is less than 18 so change places with 18.
   Step 12: [2,6,16,18,22,27]  // 6 is less than 16 so change places with 16.
 ```

**b)** Write the Big-O notation.(Big-O gösterimini yazınız.)
```
Answer b)
    Step 1: 1
    Step 2: 2
    Step 3: 3
    .
    .
    Last Step: n
    Sum: (n*(n+1)/2) --> O(n^2)
```

**c)** Time Complexity: After the array is sorted, which of the following cases does the number 18 fall under?  (Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.)
```
1. Average Case: The number that we are looking for is at the middle. (Aranan sayının ortada olması)
2. Worst Case: The number that we are looking for is at the end. (Aranan sayının sonda olması)
3. Best Case: The number that we are looking for is the first one. (Aranan sayının dizinin en başında olması)
```
```
Answer c)
    Worst case
```

**Q2)**
```
[7,3,5,8,2,9,4,15,6]
```
Write the first 4 steps of the sequence according to Selection Sort.
(dizisinin Selection Sort'a göre ilk 4 adımını yazınız.)
```
Answer 
    Step 1: min = 2 -> swap 2 and 7. [2, | 3,5,8,7,9,4,15,6]
    Step 2: min = 3 -> change nothing. [2,3, | 5,8,7,9,4,15,6]
    Step 3: min = 4 -> swap 5 and 4. [2,3,4, | 8,7,9,5,15,6]
    Step 4: min = 5 -> swap 5 and 8. [2,3,4,5, | 7,9,8,15,6]
```
# Merge Sort

**Q1)** 
```
[16,21,11,8,12,22]
```
**a)** Write the stages of the above sequence according to the sort type. (Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.)
```
Answer a) 
Step 1:               [16,21,11]                             [8,12,22]
                    /           \                         /           \
Step 2:          [16,21]    -    [11]                  [8,12]    -    [22]
                /        \             \               /      \            \
Step 3:      [16]    -    [21]    -    [11]        [8]     -    [12]    -    [22]   
                \       /              /             \         /            /
Step 4:          [16,21]    -    [11]                  [8,12]    -    [22]
                     \            /                        \           /
Step 5:                [11,16,21]                            [8,12,22]
                                  
Step 6:                               [8,11,12,16,21,22]
```

**b)** Write the Big-O notation. (Big-O gösterimini yazınız.)

```
Answer b)
    O(nlogn)
```
# Binary Search Tree
```
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
```
**a)** Write the Binary-Search-Tree stages of the sequence given above. (Yukarıda verilen dizinin Binary-Search-Tree aşamalarını yazınız.)

```
Answer a)
           7
          / \
         5   8
        / \   \
       1   6   9
      / \     /
     0   3   9
        / \
       2   4
```
