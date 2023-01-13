# TwoSumArraySorted

Problem Approach

To solve this problem I used two pointers to search the array from both the front and the back. 
As the array is sorted this allows me to add up the two pointers and adjust either the start pointer or end pointer to reach the target by moving one of them 
and repeating the comparison again.
As the pointers only traverse the array once in their direction the time complexity is O(n).
