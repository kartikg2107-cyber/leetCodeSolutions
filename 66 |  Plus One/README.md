Problem Statement

You are given:

digits → an integer array where each element represents a digit of a non-negative integer.

Increment the integer by one and return the resulting array of digits.

⚙️ Approach Used: Carry Handling from Right to Left

This solution starts from the last digit and handles the carry generated when adding one.

Steps:

✅ Traverse the array from the last index toward the beginning.

✅ If the current digit is less than 9:

Increment the digit by 1.
Return the updated array immediately.

✅ If the current digit is 9:

Set it to 0 and continue moving left.

✅ If all digits become 0:

Create a new array of size n + 1.
Set the first element to 1.

✅ Return the newly created array.

⏱️ Time Complexity

O(n)

In the worst case, every digit is processed once.

💾 Space Complexity

O(1)

No extra space is required in most cases.

Worst case: O(n) when a new array is created (e.g., 999 → 1000).

✨ Key Concepts Used

🔢 Arrays

➕ Carry Propagation

🔁 Reverse Traversal

✅ Conditional Statements

📍 Digit Manipulation

🎯 Outcome

✔️ Successfully increments the represented integer by one.

✔️ Correctly handles carry generation across multiple digits.

✔️ Handles edge cases such as all digits being 9.

✔️ Demonstrates efficient array-based number manipulation.
