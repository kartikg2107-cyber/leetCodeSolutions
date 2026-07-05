Problem Statement

You are given:

nums → an integer array containing n + 1 integers where each integer is in the range [1, n].

There is only one repeated number in the array. Return that duplicate number.

⚙️ Approach Used: HashMap Frequency Check

This solution uses a HashMap to keep track of the numbers that have already been encountered.

Steps:

✅ Create a HashMap to store the visited elements.

✅ Traverse the array.

✅ For each element:

If it already exists in the HashMap, return it immediately as the duplicate.
Otherwise, add it to the HashMap.

✅ If no duplicate is found (though the problem guarantees one exists), return 0.

⏱️ Time Complexity

O(n)

The array is traversed only once, and each HashMap operation takes O(1) on average.

💾 Space Complexity

O(n)

The HashMap stores the visited elements.

✨ Key Concepts Used

🗂️ HashMap

🔢 Arrays

📊 Frequency Tracking

🔁 For Loop

✅ Conditional Statements

🎯 Outcome

✔️ Successfully identifies the duplicate number in the array.

✔️ Uses a HashMap for efficient duplicate detection.

✔️ Returns the duplicate as soon as it is encountered, avoiding unnecessary iterations.
