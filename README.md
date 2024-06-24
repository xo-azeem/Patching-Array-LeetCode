# Patching Array

LeetCode Q # 330.

Given a sorted integer array nums and an integer n, add/patch elements to the array such that any number in the range [1, n] inclusive can be formed by the sum of some elements in the array.

Return the minimum number of patches required.

Example 1:

>Input: nums = [1,3], n = 6</br>
>Output: 1</br>
>Explanation:</br>
>Combinations of nums are [1], [3], [1,3], which form possible sums of: 1, 3, 4.</br>
>Now if we add/patch 2 to nums, the combinations are: [1], [2], [3], [1,3], [2,3], [1,2,3].</br>
>Possible sums are 1, 2, 3, 4, 5, 6, which now covers the range [1, 6].</br>
>So we only need 1 patch.

Example 2:

>Input: nums = [1,5,10], n = 20</br>
>Output: 2</br>
>Explanation: The two patches can be [2, 4].

Example 3:

>Input: nums = [1,2,2], n = 5</br>
>Output: 0

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Patching-Array-LeetCode/assets/171427226/1284df21-5086-4e2d-a67d-ae5fa1c7e74e)

  Time complexity: O(log(n)).</br>Space complexity: O(1).
</div>
