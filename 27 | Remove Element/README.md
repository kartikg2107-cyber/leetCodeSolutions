📍 Remove Element (LeetCode 27)

🧠 Problem Statement

You are given:

nums → an integer array.

val → the value that needs to be removed from the array.

Remove all occurrences of val in-place and return the number of elements that are not equal to val.

The relative order of the remaining elements should be preserved.

⚙️ Approach Used: Two-Pointer Technique

This solution uses a pointer (count) to keep track of the position where the next valid element should be placed.

Steps:

✅ Initialize count = 0.

✅ Traverse the entire array.

✅ If the current element is not equal to val:

Copy the element to nums[count].
Increment count.

✅ After the traversal, count represents the number of valid elements remaining.

⏱️ Time Complexity

O(n)

The array is traversed only once.

💾 Space Complexity

O(1)

No extra space is used; the modification is performed in-place.

✨ Key Concepts Used

🔢 Arrays

👉 Two-Pointer Technique

🔁 For Loop

✅ In-place Array Modification

⚡ Conditional Statements

🎯 Outcome

✔️ Removes all occurrences of the specified value without using extra space.

✔️ Preserves the relative order of the remaining elements.

✔️ Demonstrates an efficient in-place array manipulation technique.
