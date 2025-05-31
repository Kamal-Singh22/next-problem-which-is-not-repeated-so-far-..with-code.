# next-problem-which-is-not-repeated-so-far-..with-code.
A pangram is a sentence that contains every letter of the alphabet at least once. Write a Java program to check if a given string is a pangram.
Explanation:
Convert the string to lowercase to handle case insensitivity.

Use a boolean array of size 26 to keep track of each letter's presence.

Iterate over the string and mark the corresponding index in the array.

Finally, check if all values in the array are true.
