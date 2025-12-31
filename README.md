This is a simple Java console application that checks whether two input strings are anagrams of each other.

An anagram is a word or phrase formed by rearranging the letters of another word or phrase, using all original letters exactly once.


🚀 Features
Takes two strings as input from the user
Converts strings into character arrays
Sorts and compares the arrays
Determines whether the strings are anagrams
Outputs clear results in the console


🛠️ Technologies Used
Java
java.util.Scanner
java.util.Arrays


📌 How It Works
The program prompts the user to enter two strings.
Each string is converted into a character array.
The program checks if both arrays have the same length.
If the lengths match:
   >>>Both arrays are sorted.
   >>>The sorted arrays are compared.
If all characters match, the strings are anagrams.




▶️ Example Usage

Input:

<>Enter a string:
listen
<>Enter another string:
silent

Output:

Not an anagram


📂 Project Structure
.
├── Main.java
└── README.md


🧪 How to Run
Clone the repository:
$git clone https://github.com/your-username/anagram-checker-java.git
$cd anagram-checker-java
$javac Main.java
$java Main


📘 Notes
The comparison is case-sensitive.
Spaces and special characters are not ignored.
You can enhance the program by:
   >>>Ignoring case
   >>>Removing spaces
   >>>Handling punctuation
