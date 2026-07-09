Problem Statement

You are given:

num → a positive integer.

Return true if num is a perfect square; otherwise, return false.

A perfect square is an integer that can be expressed as the square of another integer.

⚙️ Approach Used: Binary Search

This solution uses Binary Search to efficiently determine whether a number is a perfect square.

Steps:

✅ Handle the special case where num = 1.

✅ Initialize:

left = 1
right = num

✅ Perform Binary Search:

Calculate the middle value.
Compute mid × mid.

✅ Compare the square with num:

If equal, return true.
If smaller, search the right half.
If larger, search the left half.

✅ If no exact square is found, return false.

⏱️ Time Complexity

O(log n)

The search space is halved during each iteration.

💾 Space Complexity

O(1)

Only a few variables are used throughout the algorithm.

✨ Key Concepts Used

🔍 Binary Search

🔢 Mathematical Computation

📏 Square Calculation

🔁 While Loop

✅ Conditional Statements

⚡ Overflow Prevention Using long

🎯 Outcome

✔️ Efficiently determines whether a number is a perfect square.

✔️ Avoids checking every possible value.

✔️ Uses Binary Search for logarithmic performance.

✔️ Prevents integer overflow by using the long data type.
