🧠 Problem Statement

You are given:

nums → an integer array of size n.

Return all elements that appear more than ⌊n / 3⌋ times.

The answer can contain at most two such elements.

⚙️ Approach Used: HashMap Frequency Counting

This solution uses a HashMap to count the frequency of each element and then collects all elements whose frequency is greater than n / 3.

Steps:

✅ Create a HashMap to store each element and its frequency.

✅ Traverse the array:

If the element already exists in the HashMap, increment its frequency.
Otherwise, insert the element with a frequency of 1.

✅ Traverse the HashMap.

✅ Add every element whose frequency is greater than n / 3 to the result list.

✅ Return the list of majority elements.

⏱️ Time Complexity

O(n)

The array is traversed once to build the frequency map, followed by iterating through the HashMap.

💾 Space Complexity

O(n)

The HashMap stores the frequency of distinct elements.

✨ Key Concepts Used

🗂️ HashMap

📋 ArrayList

📊 Frequency Counting

🔢 Arrays

🔁 For Loop

✅ Conditional Statements

🎯 Outcome

✔️ Correctly identifies all elements appearing more than n / 3 times.

✔️ Efficiently counts frequencies using a HashMap.

✔️ Stores the qualifying elements in a list and returns the result.

✔️ Demonstrates the use of hashing for solving frequency-based problems.
