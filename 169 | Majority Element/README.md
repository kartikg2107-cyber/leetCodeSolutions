Problem Statement

You are given:

nums → an integer array of size n.

Return the element that appears more than ⌊n / 2⌋ times.

It is guaranteed that the majority element always exists in the array.

⚙️ Approach Used: HashMap Frequency Counting

This solution uses a HashMap to count the frequency of each element and then identifies the element whose frequency exceeds n / 2.

Steps:

✅ Create a HashMap to store each element and its frequency.

✅ Traverse the array:

If the element already exists in the HashMap, increment its count.
Otherwise, insert the element with a frequency of 1.

✅ Traverse the HashMap.

✅ Return the element whose frequency is greater than n / 2.

⏱️ Time Complexity

O(n)

The array is traversed once to count frequencies, followed by iterating through the HashMap.

💾 Space Complexity

O(n)

The HashMap stores the frequency of each distinct element.

✨ Key Concepts Used

🗂️ HashMap

🔢 Arrays

📊 Frequency Counting

🔁 For Loop

✅ Conditional Statements

🎯 Outcome

✔️ Correctly identifies the majority element in the array.

✔️ Efficiently counts element frequencies using a HashMap.

✔️ Demonstrates the use of hashing for solving frequency-based problems.
