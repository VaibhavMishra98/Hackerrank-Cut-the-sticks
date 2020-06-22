# Hackerrank-Cut-the-sticks
Implementation in C++
You are given a number of sticks of varying lengths. You will iteratively cut the sticks into smaller sticks, discarding the shortest pieces until there are none left. At each iteration you will determine the length of the shortest stick remaining, cut that length from each of the longer sticks and then discard all the pieces of that shortest length. When all the remaining sticks are the same length, they cannot be shortened so discard them.

Complete the cutTheSticks function in the editor below. It should return an array of integers representing the number of sticks before each cut operation is performed.

cutTheSticks has the following parameter(s):

arr: an array of integers representing the length of each stick

Sample Input
      6
      5 4 4 2 2 8
      
Sample Output

      6
      4
      2
      1

Problem Statement Link : https://www.hackerrank.com/challenges/cut-the-sticks/problem
