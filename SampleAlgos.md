# Sample Algos

## Tips
All of these questions are somewhat vague, make sure to clearly state your assumptions when doing the problems. 

## Easy
- [ ] Given an array or list, return the largest difference between any two consecutive numbers. 
- [ ] Print a staircase of size n using hashtags and spaces.
- [ ] The largest Palindrome that is the product of 2 2-digit numbers is 9009 (multiply 91 times 99). What is the largest Palindrome that is a product of 2 3-digit numbers?
- [ ] Write a function that takes an input array ex:([], [Peter, John]). Return a string that lists all the people who are in the array. (i.e. "No one is in the array.", "Peter and John are in the array.")
- [ ] Part 1: write a function that takes in a string and a number (n) (i.e. ("Hello, 3)). The function should return that string n number of times. (i.e. "HelloHelloHello"). Part 2: Use prototypes to create a string method that accomplishes the same task. 
- [ ] Write a function that takes in an array of prices for a particular stock and returns the best possible profit based on buy low sell high philosophies. (Ex: input: [10,7,5,8,11,9] => output: 6 (difference between 5 and 11)). 
- [ ] Write a function that takes 2 arguments: the desired length of an array (n) and 2 the maximum number of values in the array (max). Based on this, output an array that produces an array of n length that has unique values all under the max value. (Ex: inputs: n = 5, max = 10 => POSSIBLE output: [2,8,4,3,9]

## Medium
- [ ] Given 2 strings, create a function that returns the number of common characters in the strings. 
- [ ] Given 2 strings, create a function that determines if the strings are anagrams of one another. 
- [ ] Given 2 arrays/lists, create a function that returns a sorted list of all duplicates. 
- [ ] Given a grid of inputs, determine the maximum product of any 4 adjacent values (can be horizontal, diagonal, or vertical). 
`
Example Input: [[8,2,22,97,38,15,0,40,0,75],[49,19,99,40,17,81,18,57,60,87],[81,49,31,73,55,79,14,29,93,71],[52,70,95,23,4,60,11,42,69,24],[22,31,16,71,51,67,63,89,41,92],[24,47,32,60,99,3,45,2,44,75],[32,98,81,28,64,23,67,10,26,38],[67,26,20,68,2,62,12,20,95,63],[24,55,58,5,66,73,99,26,97,17],[21,36,23,9,75,0,76,44,20,45]]
`
- [ ] In the fibonacci sequence, find the sum of all even values under 4,000,000. 
- [ ] Write a function that converts a given integer into binary and then returns the longest length of consecutive 1's in the sequence. (Ex: input: 60 => 111100 in binary => output: 4)
- [ ] What is the value of the first triangle number to have over five hundred divisors? A triangle number is a number that can be arranged into a triangle. For example 3 can place 1 on the first row and 2 on the second row. 6 can place 1 on the first row, 2 on the second, 3 on the third. 


## Hard
- [ ] Given 2 randomized poker hands (5 cards per hand), determine the winner of the two hands. Assume there are 6 mechanisms to rank a winning hand (for simplicity): From lowest to highest: High Card, One Pair, Two Pair, Three of a Kind, Four of a Kind, Flush/Straight (treat all flushes the same way - I know poker doesn’t actually work this way, but to make this simple and not have to deal with straights, flushes, etc. this is easier.). If two players have the same ranked hands then the rank made up of the highest value wins; for example, a pair of eights beats a pair of fives (see example 1 below). But if two ranks tie, for example, both players have a pair of queens, then highest cards in each hand are compared (see example 4 below); if the highest cards tie then the next highest cards are compared, and so on.
- [ ] Question: What is the longest Collatz Sequence for a number that starts under 1 million? Once the chain starts the terms are allowed to go above one million. Collatz Sequence: The following iterative sequence is defined for the set of positive integers: n → n/2 (n is even) n → 3n + 1 (n is odd) Using the rule above and starting with 13, we generate the following sequence: 13 → 40 → 20 → 10 → 5 → 16 → 8 → 4 → 2 → 1

