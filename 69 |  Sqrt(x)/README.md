Problem Statement

You are given:

x → a non-negative integer.

Return the integer square root of x.

The integer square root is the greatest integer whose square is less than or equal to x.

⚙️ Approach Used: Binary Search

This solution uses Binary Search to efficiently find the integer square root without using built-in square root functions.

Steps:

✅ Initialize:

left = 0
right = x

✅ Perform Binary Search:

Calculate the middle value.
Compute mid × mid using long to avoid integer overflow.

✅ Compare the square with x:

If equal, return mid.
If smaller, search the right half.
If larger, search the left half.

✅ If no exact square root is found, return right, which represents the integer square root.

⏱️ Time Complexity

O(log x)

The search space is reduced by half in each iteration.

💾 Space Complexity

O(1)

Only a constant amount of extra space is used.

✨ Key Concepts Used

🔍 Binary Search

🔢 Mathematical Computation

📏 Square Calculation

🔁 While Loop

✅ Conditional Statements

⚡ Overflow Prevention Using long

🎯 Outcome

✔️ Efficiently computes the integer square root of a non-negative integer.

✔️ Uses Binary Search for logarithmic-time performance.

✔️ Prevents integer overflow by casting to long during multiplication.

✔️ Returns the floor value when the number is not a perfect square.
