🧠 Problem Statement

You are given:

nums1 → the first integer array.

nums2 → the second integer array.

Return an array containing the unique elements that are present in both arrays.

The order of the result does not matter.

⚙️ Approach Used: HashSet + ArrayList

This solution uses a HashSet to store the unique elements of the first array and an ArrayList to collect the intersection elements.

Steps:

✅ Create a HashSet and insert all elements from nums1.

✅ Traverse nums2.

✅ For each element in nums2:

Check if it exists in the HashSet.
If it does, add it to the ArrayList.
Remove it from the HashSet to avoid duplicates in the result.

✅ Convert the ArrayList into an integer array.

✅ Return the resulting array.

⏱️ Time Complexity

O(n + m)

n = length of nums1
m = length of nums2

Each array is traversed once.

💾 Space Complexity

O(n)

The HashSet stores the unique elements of nums1, and the ArrayList stores the intersection.

✨ Key Concepts Used

🗂️ HashSet

📋 ArrayList

🔢 Arrays

🔍 Set Membership Checking

🔁 For Loop

✅ Duplicate Elimination

🎯 Outcome

✔️ Successfully finds the unique intersection of two arrays.

✔️ Eliminates duplicate values from the result.

✔️ Efficiently performs membership checks using a HashSet.

✔️ Converts the collected results into an integer array for the final output.
