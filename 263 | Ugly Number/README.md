Problem Statement

You are given:

n → an integer.

An ugly number is a positive integer whose prime factors are limited to 2, 3, and 5.

Return true if n is an ugly number; otherwise, return false.

⚙️ Approach Used: Repeated Prime Factor Division

This solution repeatedly removes the factors 2, 3, and 5 from the given number.

Steps:

✅ If n is less than or equal to 0, return false.

✅ While n is divisible by 2:

Divide n by 2.

✅ While n is divisible by 3:

Divide n by 3.

✅ While n is divisible by 5:

Divide n by 5.

✅ After removing all possible factors:

If n becomes 1, return true.
Otherwise, return false.

⏱️ Time Complexity

O(log n)

The number is repeatedly divided by 2, 3, and 5 until it can no longer be reduced.

💾 Space Complexity

O(1)

Only a constant amount of extra space is used.

✨ Key Concepts Used

🔢 Prime Factorization

➗ Integer Division

➗ Modulo Operator (%)

🔁 While Loop

✅ Conditional Statements

📊 Mathematical Logic

🎯 Outcome

✔️ Correctly determines whether a number is an ugly number.

✔️ Efficiently removes all factors of 2, 3, and 5.

✔️ Uses constant extra space.

✔️ Demonstrates a factorization-based mathematical approach.
