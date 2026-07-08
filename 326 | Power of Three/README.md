🧠 Problem Statement

You are given:

n → an integer.

Return true if n is a power of three; otherwise, return false.

A number is a power of three if it can be expressed as 3ˣ for some integer x ≥ 0.

⚙️ Approach Used: Repeated Division

This solution repeatedly divides the number by 3 until it is no longer divisible.

Steps:

✅ If n is less than or equal to 0, return false.

✅ While n is divisible by 3:

Divide n by 3.

✅ After the loop:

If n becomes 1, return true.
Otherwise, return false.

⏱️ Time Complexity

O(log₃ n)

The number is divided by 3 in each iteration until it reaches 1.

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

✔️ Correctly determines whether the given number is a power of three.

✔️ Efficiently reduces the number through repeated division.

✔️ Uses constant extra space while maintaining optimal performance for this approach.
