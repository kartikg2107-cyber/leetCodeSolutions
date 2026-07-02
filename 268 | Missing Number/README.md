📍 Missing Number (LeetCode 268)

🧠 Problem Statement

You are given:

nums → an array containing n distinct numbers in the range 0 to n.

Exactly one number is missing from the range.

Return the missing number.

⚙️ Approach Used: Sorting + Linear Search

This solution first sorts the array and then checks whether each element matches its expected index.

Steps:

✅ Sort the array in ascending order.

✅ Traverse the sorted array from index 0.

✅ Compare each element with its corresponding index:

If nums[i] is not equal to i, then i is the missing number.

✅ If all elements match their indices, then the missing number is n (the array length).

⏱️ Time Complexity

O(n log n)

Sorting the array takes O(n log n), followed by a linear traversal.

💾 Space Complexity

O(1)

Only a few extra variables are used (excluding the space required by the sorting algorithm implementation).

✨ Key Concepts Used

🔢 Arrays

🔃 Sorting

🔍 Linear Search

🔁 For Loop

✅ Conditional Statements

🎯 Outcome

✔️ Correctly identifies the missing number from the given range.

✔️ Uses sorting followed by a simple linear scan.

✔️ Demonstrates how sorting can simplify index-based comparisons.
