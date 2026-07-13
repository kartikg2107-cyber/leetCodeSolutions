Problem Statement

You are given:

nums → a rotated sorted array that may contain duplicate values.

target → the value to search for.

Return true if target exists in the array; otherwise, return false.

⚙️ Approach Used: Linear Search

This solution traverses the array from beginning to end and checks each element against the target.

Steps:

✅ Start iterating through the array.

✅ Compare each element with the target.

✅ If a match is found:

Return true immediately.

✅ If the entire array is traversed without finding the target:

Return false.

⏱️ Time Complexity

O(n)

In the worst case, every element in the array may need to be checked.

💾 Space Complexity

O(1)

No extra data structures are used.

✨ Key Concepts Used

🔢 Arrays

🔍 Linear Search

🔁 For Loop

✅ Conditional Statements

📍 Element Comparison

🎯 Outcome

✔️ Successfully determines whether the target exists in the array.

✔️ Works correctly even when duplicate values are present.

✔️ Uses constant extra space.

✔️ Demonstrates a simple and straightforward searching technique.
