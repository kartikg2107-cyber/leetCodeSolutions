Problem Statement

You are given:

haystack → the main string.

needle → the substring to search for.

Return the index of the first occurrence of needle in haystack.

If needle is not part of haystack, return -1.

⚙️ Approach Used: Built-in String Method

This solution uses Java's built-in indexOf() method to find the first occurrence of a substring within a string.

Steps:

✅ Use the indexOf() method on haystack.

✅ Pass needle as the parameter.

✅ If the substring exists:

indexOf() returns its starting index.

✅ If the substring does not exist:

indexOf() returns -1.

✅ Return the result directly.

⏱️ Time Complexity

O(n × m)

Where:

n = length of haystack
m = length of needle

In the worst case, the method may compare multiple characters while searching.

💾 Space Complexity

O(1)

No additional data structures are used.

✨ Key Concepts Used

📝 Strings

🔍 Substring Search

⚡ Built-in Methods

✅ indexOf()

📍 String Manipulation

🎯 Outcome

✔️ Successfully finds the first occurrence of a substring.

✔️ Returns the correct starting index when found.

✔️ Returns -1 when the substring is absent.

✔️ Utilizes Java's built-in string searching functionality for a concise solution.
