Problem Statement

You are given:

s → the first string.

t → the second string.

Return true if t is an anagram of s; otherwise, return false.

An anagram is a word or phrase formed by rearranging the letters of another word, using all the original characters exactly once.

⚙️ Approach Used: HashMap Frequency Counting

This solution uses a HashMap to count the frequency of characters in the first string and then decreases the count while traversing the second string.

Steps:

✅ Create a HashMap to store the frequency of each character in s.

✅ Traverse s:

Add each character to the HashMap.
Increase its frequency using getOrDefault().

✅ Traverse t:

If the character exists in the HashMap:
If its frequency is 1, remove it from the HashMap.
Otherwise, decrease its frequency by 1.
If the character does not exist, return false.

✅ After processing both strings:

If the HashMap is empty, return true.
Otherwise, return false.

⏱️ Time Complexity

O(n)

Where n is the length of the strings. Each string is traversed once.

💾 Space Complexity

O(n)

The HashMap stores the frequency of characters.

✨ Key Concepts Used

🗂️ HashMap

📊 Frequency Counting

🔤 Strings

🔁 For Loop

✅ getOrDefault()

🔍 Character Comparison

🎯 Outcome

✔️ Correctly determines whether two strings are anagrams.

✔️ Efficiently tracks character frequencies using a HashMap.

✔️ Handles repeated characters accurately.

✔️ Demonstrates the use of hashing for string comparison problems.
