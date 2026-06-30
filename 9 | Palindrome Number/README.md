📍 Palindrome Number (LeetCode 9)

🧠 Problem Statement

You are given an integer:

x → represents the number to be checked.

A number is called a palindrome if it reads the same forward and backward.

Return true if x is a palindrome; otherwise, return false.

⚙️ Approach Used: Reverse the Number

This solution reverses the given integer digit by digit and compares the reversed number with the original number.

Steps:

✅ Store the original number in a temporary variable.

✅ Reverse the number using:

Modulo (%) to extract the last digit.
Division (/) to remove the last digit.

✅ Compare the reversed number with the original number.

✅ If both are equal, return true; otherwise, return false.

⏱️ Time Complexity

O(log₁₀ n)

The loop processes each digit of the number exactly once.

💾 Space Complexity

O(1)

Only a few integer variables are used, regardless of the input size.

✨ Key Concepts Used

🔢 Number Reversal

➗ Modulo Operator (%)

➗ Integer Division (/)

🔁 While Loop

✅ Conditional Comparison

🎯 Outcome

✔️ Efficiently checks whether a number is a palindrome.

✔️ Uses constant extra space.

✔️ Reinforces fundamental concepts of integer manipulation and loops.
