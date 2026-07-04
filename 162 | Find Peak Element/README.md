🧠 Problem Statement

You are given:

nums → an integer array.

A peak element is an element that is strictly greater than its adjacent elements.

Return the index of any one peak element.

⚙️ Approach Used: Maximum Element Search

This solution first finds the maximum element in the array and then returns its index.

Steps:

✅ Initialize a variable to store the maximum value.

✅ Traverse the array to find the largest element.

✅ Traverse the array again to locate the index of the maximum element.

✅ Return the index once the maximum element is found.

⏱️ Time Complexity

O(n)

The array is traversed twice, resulting in linear time complexity.

💾 Space Complexity

O(1)

Only a constant amount of extra space is used.

✨ Key Concepts Used

🔢 Arrays

🔍 Linear Search

📈 Maximum Element Search

🔁 For Loop

✅ Math.max()

🎯 Outcome

✔️ Successfully returns the index of the maximum element.

✔️ Uses a simple linear traversal without additional data structures.

✔️ Demonstrates how to find the largest element and its position in an array.
