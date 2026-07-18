Problem Statement

You are given:

nums → an integer array.

Find the contiguous subarray with the largest sum and return that sum.

A subarray is a continuous part of the array.

⚙️ Approach Used: Kadane's Algorithm

This solution uses Kadane's Algorithm to efficiently find the maximum sum of a contiguous subarray.

Steps:

✅ Initialize:

cs (current sum) = nums[0]
max (maximum sum) = nums[0]

✅ Traverse the array starting from index 1.

✅ For each element:

Decide whether to start a new subarray from the current element or extend the existing subarray.
Update the current sum using:
current element
current sum + current element

✅ Update the maximum sum whenever a larger sum is found.

✅ Return the maximum sum after the traversal.

⏱️ Time Complexity

O(n)

The array is traversed exactly once.

💾 Space Complexity

O(1)

Only two variables are used regardless of the input size.

✨ Key Concepts Used

📈 Kadane's Algorithm

🔢 Arrays

➕ Running Sum

🔁 For Loop

✅ Dynamic Programming

📊 Maximum Subarray Sum

🎯 Outcome

✔️ Efficiently finds the maximum sum among all contiguous subarrays.

✔️ Uses Kadane's Algorithm for optimal linear-time performance.

✔️ Requires only constant extra space.

✔️ Demonstrates an important Dynamic Programming optimization technique.
