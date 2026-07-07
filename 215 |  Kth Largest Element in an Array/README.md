🧠 Problem Statement

You are given:

nums → an unsorted integer array.

k → an integer representing the kth largest element to find.

Return the kth largest element in the array.

Note: It is the kth largest element in the sorted order, not the kth distinct element.

⚙️ Approach Used: Sorting

This solution sorts the array in ascending order and then accesses the kth largest element by traversing from the end of the array.

Steps:

✅ Sort the array in ascending order.

✅ Start traversing from the last index of the sorted array.

✅ Move backwards until reaching the kth largest position.

✅ Return the element at that position.

⏱️ Time Complexity

O(n log n)

Sorting the array dominates the overall time complexity.

💾 Space Complexity

O(1)

Only a constant amount of extra space is used (excluding the space required by the sorting algorithm implementation).

✨ Key Concepts Used

🔢 Arrays

🔃 Sorting

📍 Index Manipulation

🔁 For Loop

✅ Array Traversal

🎯 Outcome

✔️ Correctly finds the kth largest element in the array.

✔️ Uses sorting to simplify the search process.

✔️ Demonstrates an easy-to-understand approach for solving ranking-based array problems.
