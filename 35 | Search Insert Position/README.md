📍 Search Insert Position (LeetCode 35)

🧠 Problem Statement

You are given:

nums → a sorted integer array.

target → the value to search for.

Return the index if the target is found. If not, return the index where it would be inserted while maintaining the sorted order.

⚙️ Approach Used: Binary Search

This solution uses the Binary Search algorithm to efficiently search for the target in a sorted array.

Steps:

✅ Initialize two pointers:

low = 0
high = nums.length - 1

✅ Calculate the middle index.

✅ Compare nums[mid] with target:

If equal, return mid.
If nums[mid] is smaller, search the right half.
Otherwise, search the left half.

✅ If the target is not found, low will point to the correct insertion position.

✅ Return low.

⏱️ Time Complexity

O(log n)

The search space is halved in every iteration.

💾 Space Complexity

O(1)

Only a few variables are used, regardless of the input size.

✨ Key Concepts Used

🔍 Binary Search

🔢 Arrays

👉 Two-Pointer Technique

🔁 While Loop

✅ Conditional Statements

🎯 Outcome

✔️ Efficiently searches for the target in a sorted array.

✔️ Returns the correct insertion position if the target is absent.

✔️ Demonstrates the power of Binary Search for logarithmic-time searching.
