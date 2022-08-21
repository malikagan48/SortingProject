# Merge Sort

### [16,21,11,8,12,22] Steps:

```
The array is first split into two.

First Series: [16,21,11]
Second Series: [8,12,22]

These sequences are also divided among themselves and sorted.

First Series One: [16,21]
Second Series Two: [11]

Second Series One: [8,12]
First Series Two: [22]

Arrays after sort:
First Series: [11,16,21]
Second Series: [8,12,22]

These sequences are sorted by comparison starting from the smallest.
First, 8 and 11 are compared. It becomes 8.11. It is compared with the 11 that comes after 2 and 8,11,12 is obtained.
This way the arrays are only compared to the next.

Sorted List: [8,11,12,16,21,22]
```

### Big-O notation:
Best, Average, Worst Case :  O(nlogn)
