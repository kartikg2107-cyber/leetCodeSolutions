Problem Statement

You are given:

s → a character array.

Reverse the array in-place without using extra memory for another array.

⚙️ Approach Used: Two-Pointer Technique

This solution uses two pointers, one starting from the beginning and the other from the end of the array.

Steps:

✅ Initialize:

left = 0
right = s.length - 1

✅ While left is less than right:

Swap the characters at left and right.
Move left one step forward.
Move right one step backward.

✅ Continue until both pointers meet or cross each other.

⏱️ Time Complexity

O(n)

Each character is visited at most once during the swapping process.

💾 Space Complexity

O(1)

The reversal is performed in-place using only a temporary variable.

✨ Key Concepts Used

👉 Two-Pointer Technique

🔄 In-place Reversal

🔤 Character Arrays

🔁 While Loop

✅ Swapping Elements

🎯 Outcome

✔️ Successfully reverses the character array in-place.

✔️ Does not use any additional array or collection.

✔️ Uses constant extra space.

✔️ Demonstrates an efficient two-pointer swapping technique.
