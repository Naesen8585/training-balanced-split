# training-balanced-split

Balanced Split

Given an array of integers (which may include repeated integers), determine if there's a way to split the array into two subsequences A and B such that the sum of the integers in both arrays is the same, and all of the integers in A are strictly smaller than all of the integers in B.

Note: Strictly smaller denotes that every integer in A must be less than, and not equal to, every integer in B.

Signature

bool balancedSplitExists(int[] arr)

Input

All integers in array are in the range [0, 1,000,000,000].

Output

Return true if such a split is possible, and false otherwise.

Example 1

arr = [1, 5, 7, 1]

output = true

We can split the array into A = [1, 1, 5] and B = [7].

Example 2

arr = [12, 7, 6, 7, 6]

output = false

We can't split the array into A = [6, 6, 7] and B = [7, 12] since this doesn't satisfy the requirement that all integers in A are smaller than all integers in B.


---
**INSTRUCTIONS:**

Fork this repo to your own. Create a solution to the problem. The test cases will prove whether your solution is correct.


**MY IDE IS THROWING ERRORS WHEN FIRST LOADING THIS CODE**

That's right. It's incomplete. Its your job to fill in the blanks.

**WHY DOES THIS README LOOK TERRIBLE**
fine. do a fork/ readme fix up / PR to here and I'll accept it.