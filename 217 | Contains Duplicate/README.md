📍 Contains Duplicate (LeetCode 217)

🧠 Problem Statement

You are given:

nums → an integer array.

Return true if any value appears at least twice in the array; otherwise, return false.

⚙️ Approach Used: Brute Force Comparison

This solution compares each element with every other element that comes after it.

Steps:

✅ Start from the first element of the array.

✅ Compare the current element with all the remaining elements.

✅ If any two elements are equal, return true immediately.

✅ If no duplicate is found after checking all elements, return false.

⏱️ Time Complexity

O(n²)

Each element is compared with the remaining elements in the array.

💾 Space Complexity

O(1)

No extra data structures are used.

✨ Key Concepts Used

🔢 Arrays

🔍 Nested Traversal

🔁 While Loop

🔁 For Loop

✅ Conditional Statements

🎯 Outcome

✔️ Correctly detects whether the array contains duplicate elements.

✔️ Uses a straightforward brute-force comparison approach.

✔️ Demonstrates basic array traversal and element comparison techniques.
