📍 Search in Rotated Sorted Array (LeetCode 33)

🧠 Problem Statement

You are given:

nums → a rotated sorted integer array with distinct values.

target → the value to search for.

Return the index of target if it exists in the array. Otherwise, return -1.

⚙️ Approach Used: Linear Search

This solution traverses the array from the beginning and checks each element until the target is found.

Steps:

✅ Start iterating from the first element of the array.

✅ Compare each element with the target.

✅ If the current element matches the target, return its index.

✅ If the entire array is traversed without finding the target, return -1.

⏱️ Time Complexity

O(n)

In the worst case, every element is checked once.

💾 Space Complexity

O(1)

Only a constant amount of extra space is used.

✨ Key Concepts Used

🔢 Arrays

🔍 Linear Search

🔁 For Loop

✅ Conditional Statements

🎯 Outcome

✔️ Successfully searches for the target element in the rotated sorted array.

✔️ Returns the correct index if the target exists.

✔️ Returns -1 when the target is not present.

✔️ Demonstrates a simple Linear Search approach that works regardless of array rotation.
