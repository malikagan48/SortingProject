# Insertion Sort
### [22,27,16,2,18,6] Stages of the sequence:

```
Factor: 22
 Sort: 22,27,16,2,18,18,6
Factor: 16 (22 ve 27 moved to the next Factor in order not to disperse because the ranking was made)
  Sort: 16,22,27,2,18,6
Factor: 2
  Sort: 2,16,22,27,18,6
Factor: 18
  Sort: 2,16,18,22,27,6
Factor: 6
  Sort 2,6,16,18,22,27
  
Sorted List: 2,6,16,18,22,27
```

### Big-O Notation: 

Best Case --> O(n)

Average Case --> O(n<sup>2</sup>)

Worst Case --> O(n<sup>2</sup>)

### After the series is sorted, the number 18 is included in the Average.

***

### [7,3,5,8,2,9,4,15,6] first 4 steps of array according to Insertion Sort:

```
First Step: Factor: 7 
  Sort: 3,5,7,8,2,9,4,15,6
Second Step: Factor: 2
  Sort: 2,3,5,7,8,9,4,15,6
Third Step: Factor: 9
  Sort: 2,3,5,7,8,9,4,15,6
Fourth Step: Factor: 4
  Sort: 2,3,4,5,7,8,9,15,6
```
