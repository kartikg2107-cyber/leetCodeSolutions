Problem Statement

You are given:

nums → an integer array.

For each index i, calculate:

The sum of all elements to the left of i.
The sum of all elements to the right of i.

Return an array answer where:

answer[i] = |leftSum[i] - rightSum[i]|

⚙️ Approach Used: Prefix Sum + Suffix Sum Arrays

This solution precomputes the sum of elements on the left and right side of every index and then calculates their absolute difference.

Steps:

✅ Create a leftsum array:

leftsum[0] = 0
Each position stores the sum of all elements before it.

✅ Create a rightsum array:

rightsum[n-1] = 0
Each position stores the sum of all elements after it.

✅ Traverse the array:

Compute answer[i] = |leftsum[i] - rightsum[i]|.

✅ Return the answer array.

⏱️ Time Complexity

O(n)

The array is traversed a constant number of times.

💾 Space Complexity

O(n)

Additional arrays are used for:

leftsum
rightsum
answer

✨ Key Concepts Used

📊 Prefix Sum

📊 Suffix Sum

🔢 Arrays

🔁 Forward Traversal

🔁 Backward Traversal

➖ Absolute Difference

✅ Math.abs()

🎯 Outcome

✔️ Efficiently calculates left and right sums for every index.

✔️ Computes the absolute difference between both sums.

✔️ Demonstrates the use of Prefix Sum and Suffix Sum techniques.

✔️ Produces the result in linear time complexity.
