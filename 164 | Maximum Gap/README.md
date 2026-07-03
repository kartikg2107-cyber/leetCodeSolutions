Maximum Gap (LeetCode 164)

🧠 Problem Statement

You are given:

nums → an unsorted integer array.

Return the maximum difference between two successive elements in its sorted form.

If the array contains fewer than two elements, return 0.

⚙️ Approach Used: Sorting + Linear Traversal

This solution first sorts the array and then computes the difference between every pair of consecutive elements.

Steps:

✅ If the array contains only one element, return 0.

✅ Sort the array in ascending order.

✅ Traverse the sorted array.

✅ For each pair of consecutive elements:

Calculate the difference.
Update the maximum gap if the current difference is larger.

✅ Return the maximum gap after completing the traversal.

⏱️ Time Complexity

O(n log n)

Sorting the array dominates the overall time complexity.

💾 Space Complexity

O(1)

Only a few extra variables are used (excluding the space required by the sorting algorithm implementation).

✨ Key Concepts Used

🔢 Arrays

🔃 Sorting

📏 Consecutive Element Comparison

🔁 For Loop

✅ Math.max()

🎯 Outcome

✔️ Correctly finds the maximum gap between consecutive elements after sorting.

✔️ Handles the edge case of a single-element array.

✔️ Demonstrates how sorting simplifies consecutive difference calculations.
