🧠 Problem Statement

You are given:

nums → an integer array.

Every element appears exactly twice except for two elements, which appear only once.

Return the two elements that appear only once.

The order of the returned elements does not matter.

⚙️ Approach Used: HashMap + ArrayList

This solution uses a HashMap to track the occurrence of each element and an ArrayList to maintain the elements that currently appear only once.

Steps:

✅ Create a HashMap to store the frequency of each element.

✅ Create an ArrayList to store elements that currently appear only once.

✅ Traverse the array:

If the element is encountered for the first time:
Add it to the HashMap with a frequency of 1.
Add it to the ArrayList.
If the element is encountered again:
Update its frequency in the HashMap.
Remove it from the ArrayList.

✅ Convert the ArrayList into an integer array.

✅ Return the resulting array containing the two unique elements.

⏱️ Time Complexity

O(n)

The array is traversed once, and the remaining operations are linear.

💾 Space Complexity

O(n)

The HashMap and ArrayList together require additional space proportional to the number of elements.

✨ Key Concepts Used

🗂️ HashMap

📋 ArrayList

🔢 Arrays

📊 Frequency Counting

🔁 For Loop

✅ Duplicate Removal

🎯 Outcome

✔️ Successfully identifies the two elements that appear only once.

✔️ Efficiently tracks element occurrences using a HashMap.

✔️ Maintains the unique elements dynamically with an ArrayList.

✔️ Returns the result as an integer array.
