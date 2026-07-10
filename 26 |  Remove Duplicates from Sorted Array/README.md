Problem Statement

You are given:

nums → a sorted integer array.

Remove the duplicates in-place such that each unique element appears only once.

Return the number of unique elements in the array.

The relative order of the elements should remain unchanged.

⚙️ Approach Used: Two-Pointer Technique

This solution uses a pointer to track the position where the next unique element should be placed.

Steps:

✅ Initialize k = 1 since the first element is always unique.

✅ Traverse the array starting from index 1.

✅ Compare the current element with the previous element:

If they are different, a new unique element is found.
Place it at nums[k].
Increment k.

✅ Continue until all elements are processed.

✅ Return k, which represents the total number of unique elements.

⏱️ Time Complexity

O(n)

The array is traversed exactly once.

💾 Space Complexity

O(1)

The duplicates are removed in-place without using extra space.

✨ Key Concepts Used

👉 Two-Pointer Technique

🔢 Arrays

🔁 For Loop

✅ In-place Array Modification

📍 Index Manipulation

🎯 Outcome

✔️ Successfully removes duplicate elements from a sorted array.

✔️ Preserves the relative order of unique elements.

✔️ Uses constant extra space.

✔️ Demonstrates an efficient in-place array processing technique.
