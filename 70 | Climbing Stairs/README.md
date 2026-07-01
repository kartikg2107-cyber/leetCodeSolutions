📍 Climbing Stairs (LeetCode 70)

🧠 Problem Statement

You are given:

n → the total number of stairs.

You can climb either 1 step or 2 steps at a time.

Return the total number of distinct ways to reach the top of the staircase.

⚙️ Approach Used: Iterative Dynamic Programming

This solution uses an iterative approach based on the Fibonacci sequence.

Steps:

✅ Handle the base cases for 1 and 2 stairs.

✅ Initialize two variables:

a = number of ways to reach the previous stair.
b = number of ways to reach the current stair.

✅ Traverse from the 3rd stair to the nth stair.

✅ For each stair:

Calculate the current number of ways as the sum of the previous two values.
Update the variables for the next iteration.

✅ Return the final calculated value.

⏱️ Time Complexity

O(n)

The staircase is traversed only once.

💾 Space Complexity

O(1)

Only a constant amount of extra space is used.

✨ Key Concepts Used

🧮 Dynamic Programming

🔢 Fibonacci Sequence

🔁 Iteration

✅ Variable Optimization

⚡ Conditional Statements

🎯 Outcome

✔️ Efficiently calculates the total number of distinct ways to climb the stairs.

✔️ Uses constant extra space by optimizing the Dynamic Programming approach.

✔️ Demonstrates the relationship between the problem and the Fibonacci sequence.
