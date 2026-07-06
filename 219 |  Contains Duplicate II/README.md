Problem Statement

You are given:

nums → an integer array.

k → the maximum allowed distance between two equal elements.

Return true if there exist two distinct indices i and j such that:

nums[i] == nums[j]
|i - j| ≤ k

Otherwise, return false.

⚙️ Approach Used: HashMap (Store Latest Index)

This solution uses a HashMap to store the most recent index of each element while traversing the array.

Steps:

✅ Create a HashMap to store each element and its latest index.

✅ Traverse the array.

✅ For each element:

If it already exists in the HashMap, retrieve its previous index.
Calculate the distance between the current index and the previous index.
If the distance is less than or equal to k, return true.

✅ Update the HashMap with the current index of the element.

✅ If no valid pair is found after traversing the array, return false.

⏱️ Time Complexity

O(n)

The array is traversed only once, and each HashMap operation takes O(1) on average.

💾 Space Complexity

O(n)

The HashMap stores the latest index of each distinct element.

✨ Key Concepts Used

🗂️ HashMap

🔢 Arrays

📍 Index Tracking

🔁 For Loop

✅ Conditional Statements

🎯 Outcome

✔️ Successfully determines whether duplicate elements exist within the specified distance.

✔️ Efficiently tracks the latest occurrence of each element using a HashMap.

✔️ Avoids unnecessary comparisons by checking index differences directly.
