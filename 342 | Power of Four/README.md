🧠 Problem Statement

You are given:

n → an integer.

Return true if n is a power of four; otherwise, return false.

A number is a power of four if it can be expressed as 4ˣ for some integer x ≥ 0.

⚙️ Approach Used: Repeated Division

This solution repeatedly divides the number by 4 until it is no longer divisible.

Steps:

✅ If n is less than or equal to 0, return false.

✅ While n is divisible by 4:

Divide n by 4.

✅ After the loop:

If n becomes 1, return true.
Otherwise, return false.

⏱️ Time Complexity

O(log₄ n)

The number is divided by 4 in each iteration until it reaches 1.

💾 Space Complexity

O(1)

Only a constant amount of extra space is used.

✨ Key Concepts Used

➗ Integer Division

➗ Modulo Operator (%)

🔁 While Loop

✅ Conditional Statements

🔢 Mathematical Logic

🎯 Outcome

✔️ Correctly determines whether the given number is a power of four.

✔️ Efficiently reduces the number through repeated division.

✔️ Uses constant extra space.

✔️ Demonstrates a simple mathematical approach for power validation.
