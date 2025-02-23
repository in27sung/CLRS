## 2.1 Insertion sort

### Sorting problem 
**Input**: A sequence of $n$ numbers $$<a_1, a_2, \dots, a_n>$$.

**Output**: A permutation (reordering) $$<a_1^\{'}, a_2^{'}, \dots, a_n^{'}>$$. of the input sequence such that $$a_1^\{'} \leq a_2^{'} \leq \dots \leq a_n^{'}$$.

**keys**: The number to be storted
**satellite data**: The input comes in the form of an array with $n$ elements. When we want to srot numbers, it's often beacuse they are the keys accociated with other data.
**recode**: A key and satellite data form

<img width="540" alt="image" src="https://github.com/user-attachments/assets/34172b0d-4abd-4f10-80f1-758d9cd140df" />

```pseudocode
INSERTION-SORT(A,$n$)
for i = 2 to n
  key = A[i]
  // Insert A[i] into the sorted subarray A[1:i - 1]
  j = i - 1
```
