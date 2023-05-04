Download Link: https://assignmentchef.com/product/solved-csci203-csci803-assignment-1-searching-the-dictionary
<br>
You are to write a word processing program in one file (only) named: ass1.cpp or ass1.java, etc.  Your main() procedure should record the start time of your program and, at the end of processing, display the total run time of your program (in seconds).  You should do this work in steps, as described below. You may use any data structures and algorithms that have been presented in class up to the end of week 4. If you use other data structures or algorithms, appropriate references must be provided

<h1>Step-1 (Week-4 demo)</h1>

Write a program that reads the dictionary file (named: “dictionary.txt) and places the words in an appropriate array and then prints the number of words read on the screen. (You can assume that the dictionary contains no more than 400,000 words and no word is longer than 35 characters.)  Then write a function that uses a linear search to find the first 10 palindromes in the dictionary array and display them on the screen. (Note: A palindrome is a word larger than 1 character that reads the same both forward and backward like: “racecar”.) Example output:

<strong> </strong>

<strong>Number of words in dictionary: 370103 </strong>

<strong>First 5 palindromes: </strong>

<strong>aa : aa aaa : aaa aas : saa ab : ba aba : aba </strong>

<strong> </strong>

<strong>Total run time (secs): 1 </strong>




Note:  You will receive the 2 demo marks no matter how your search for the palindromes in the array is done. Make sure your search stops when the first 5 palindromes are found.




<h1>Step-2 (More palindromes,)</h1>

Before you commence Step-2, estimate how long it would take for your step-1 linear search to find all the palindromes in the dictionary? Now, replace the linear search with a binary search and estimate the time to find ALL the palindromes in the dictionary. Write your estimate of the speedup factor in the report in Step-5. Print on the screen: the first 10 palindromes found (similar to step-1) and the longest palindrome found. (Note: if there is more than one palindrome with the longest length, print the first one only.) Implement other speed enhancements if you can think of any.




<h1>Step-3 (Spell-check)</h1>

Read the input data file: “sample.txt”, pre-process it (as explained below) and search for each word (once only) in the dictionary. Then print on the screen the total number of valid words read, the number of unique words read, and the number of unique words read that were found in the dictionary. You should store all unique words that were found in the dictionary in a suitable array.




<u>Note:</u> To pre-process the words read from “sample.txt”, all capitals should be converted to lower case. Punctuation marks in words should be removed and treated as a single word. Thus, <em>it’s </em>will become <em>its</em>, <em>you’ll </em>will become <em>youll </em>and <em>loop-hole </em>will become <em>loophole</em>. Any word that becomes zero characters as a result of the pre-processing should be rejected it as an invalid word.

<strong> </strong>

<h1>Step-4 (Anagrams,)</h1>

Use the dictionary to find anagrams of the unique words stored in the array from step-3. Print the first 10 anagram words together with their anagrams in alphabetic order e.g.: <strong> admire: armied damier dimera merida  after: afret frate trefa  …. </strong>

Also, print the word with the most anagrams, the longest word with anagram(s), the total number of words with anagram(s) and the total number of anagrams found. Optimise your code so that it completes this task as quickly as possible.

<strong> </strong>

<h1>Step-5 (Specifications, )</h1>

In a comment block at the bottom of your program, write the following details in no more than 20 lines of text. State the run time of your final program and what machine this was on. Quote the speedup achieved in step-2. List the data structures and algorithms used by your program to spellcheck, find palindromes and find anagrams. Also include any other enhancements you did to speed up your program (if any). For this step, marks will be awarded based on how accurately and clearly you describe your program.