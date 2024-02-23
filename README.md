# Java Code

# [1] missing_number_in_array

Given an array of size N-1 such that it only contains distinct integers in the range of 1 to N. Find the missing element.

Example 1:

Input:
N = 5
A[] = {1,2,3,5}
Output: 4
Example 2:

Input:
N = 10
A[] = {6,1,2,8,3,4,7,10,5}
Output: 9

Your Task :
You don't need to read input or print anything. Complete the function MissingNumber() that takes array and N as input  parameters and returns the value of the missing number.


Expected Time Complexity: O(N)
Expected Auxiliary Space: O(1)


Constraints:
1 ≤ N ≤ 106
1 ≤ A[i] ≤ 106


# [2] Find First Alert

This Java code defines a class Main with two main methods: findFirstWord and main. Here's an explanation of the code:
findFirstWord method:
This method takes a paragraph as input along with a HashSet of words to search for.
It converts the paragraph to lowercase to make the search case-insensitive.
It compiles a regex pattern \b\w+\b to match words in the paragraph.
It creates a Matcher object using the pattern and the lowercased paragraph.
It iterates over the matches found by the Matcher and checks if the word is in the HashSet of search words. If found, it returns the word; otherwise, it continues searching.
If no matching word is found, it returns null.
main method:
This is the entry point of the program.
It creates a Scanner object to read input from the console.
It reads a paragraph input from the user using scanner.nextLine().
It initializes a HashSet named searchWords and adds three search words: "warning", "critical", and "exhausted".
It calls the findFirstWord method with the input paragraph and searchWords HashSet.
If a word is found, it prints "First word found: " followed by the word. Otherwise, it prints "None of the search words found in the paragraph."
Finally, it closes the Scanner object.
Overall, this code snippet demonstrates how to find and return the first occurrence of a specific word from a given paragraph based on a predefined set of search words using regular expressions and HashSet in Java.
