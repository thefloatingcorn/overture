# Classifying LeetCode

## Intro
To focus on the essential problems on LeetCode,
a classification is built based on my own experience,
referring existing works such as:

https://mincongzhang.gitbooks.io/data_structures_and_algorithms/content/

https://algorithm.yuanbin.me/en/

https://blog.csdn.net/weixin_38118016/article/details/90761111

https://cspiration.com/leetcodeClassification

---
## Tier I: Methods

### Binary Search:
Hint:
* items have to be sorted.
* runtime complexity in the order of O(log n)

* Easy:
  * [278.	First Bad Version](https://leetcode.com/problems/first-bad-version)
  * [69. Sqrt(x)](https://leetcode.com/problems/sqrtx)
  * [35. Search Insert Position](https://leetcode.com/problems/search-insert-position)
* Mid:
  * [33. Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array)
  * [34. Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array)  
  * [153. Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array)
* Hard:
  * [4. Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays)
  <!--
  367. Valid Perfect Square
  * Mid:
   -->

### Two Pointers
Hint: in-place
* Easy:
  * [26. Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array)
  * [27. Remove Element](https://leetcode.com/problems/remove-element)
  * [88. Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array)
* Hard:
  * [42. Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water)

<!-- * [283.	Move Zeroes]
[443. String Compression]
* Mid:


Sliding Window:
* Mid:
  * 209. Minimum Size Subarray Sum
  * 3\.	Longest Substring Without Repeating Characters 
  -->

### Dynamic Programming
Hint: how many possible ways.
* Easy:
  * [70. Climbing Stairs](https://leetcode.com/problems/climbing-stairs)  
  * [118.	Pascal's Triangle](https://leetcode.com/problems/pascals-triangle)
  * [198.	House Robber](https://leetcode.com/problems/house-robber)
* Mid:
  * [62. Unique Paths](https://leetcode.com/problems/unique-paths)
  * [322. Coin Change](https://leetcode.com/problems/coin-change)
  * [688. Knight Probability in Chessboard](https://leetcode.com/problems/knight-probability-in-chessboard)
<!-- 204. Count Primes -->
<!-- 119 Pascal's Triangle II-->
<!-- 674. Longest Continuous Increasing Subsequence -->
<!--


-->

### Divide and Conquer / (Recursion)
* [53.	Maximum Subarray](https://leetcode.com/problems/maximum-subarray)
* [169.	Majority Element](https://leetcode.com/problems/majority-element)

### Greedy
* [860. Lemonade Change](https://leetcode.com/problems/lemonade-change)

---
## Tier II: Structures

### Array/List
* [268.	Missing Number](https://leetcode.com/problems/missing-number)
* [350.	Intersection of Two Arrays II](https://leetcode.com/problems/intersection-of-two-arrays-ii)
<!-- 136	Single Number
349. Intersection of Two Arrays
448	Find All Numbers Disappeared in an Array -->

### Queue/Stack
* [155.	Min Stack](https://leetcode.com/problems/min-stack)
* [225.	Implement Stack using Queues](https://leetcode.com/problems/implement-stack-using-queues)
* [232.	Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks)

### LinkedList
* [237.	Delete Node in a Linked List](https://leetcode.com/problems/delete-node-in-a-linked-list)
* [203.	Remove Linked List Elements](https://leetcode.com/problems/remove-linked-list-elements)
* [206.	Reverse Linked List](https://leetcode.com/problems/reverse-linked-list)

<!-- * [21.	Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists)
* [141.	Linked List Cycle](https://leetcode.com/problems/linked-list-cycle)
* [160.	Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists) -->

<!--
83 Remove Duplicates from Sorted List -->

<!--
* Mid:
  * 19.	Remove Nth Node From End of List
  * 24.	Swap Nodes in Pairs
  * 328.	Odd Even Linked List -->

### Tree
* [104.	Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree)
* [101.	Symmetric Tree](https://leetcode.com/problems/symmetric-tree)
* [226.	Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree)

* Binary Tree Traversal:
  * 94 Inorder, 102 Level Order, 144 Preorder, 145 Postorder

<!--
*257. Binary Tree Paths*
111	Minimum Depth of Binary Tree    
112	Path Sum  
100 Same Tree
107	Binary Tree Level Order Traversal II
110	Balanced Binary Tree   
* 543.	Diameter of Binary Tree
* 617.	Merge Two Binary Trees

* BST:
  * 235. Lowest Common Ancestor of a Binary Search Tree
  * 108.	Convert Sorted Array to Binary Search Tree
  * 538.	Convert BST to Greater Tree -->

### Char/Str
* Easy
  * [14.	Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix)
  * [28.	Implement strStr()](https://leetcode.com/problems/implement-strstr)
  * [58.	Length of Last Word](https://leetcode.com/problems/length-of-last-word)
* ord() / chr()
  * [168.	Excel Sheet Column Title](https://leetcode.com/problems/excel-sheet-column-title)
  * [171.	Excel Sheet Column Number](https://leetcode.com/problems/excel-sheet-column-number)
  * [389.	Find the Difference](https://leetcode.com/problems/find-the-difference)  

<!--
205. Isomorphic Strings
* 344.	Reverse String
* 383.	Ransom Note
* 387.	First Unique Character in a String
* 771.	Jewels and Stones
20	Valid Parentheses
242	Valid Anagram
290. Word Pattern
299. Bulls and Cows
345. Reverse Vowels of a String
Mid:
49. Group Anagrams
166. Fraction to Recurring Decimal
  -->

### Bit
* [190.	Reverse Bits](https://leetcode.com/problems/reverse-bits)
* [191.	Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits)
* [371. Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers)
---

## Tier III: Topics

### Math
* [7.	Reverse Integer](https://leetcode.com/problems/reverse-integer)
* [172.	Factorial Trailing Zeroes](https://leetcode.com/problems/factorial-trailing-zeroes)
* [202.	Happy Number](https://leetcode.com/problems/happy-number)
<!--
412.	Fizz Buzz
258. Add Digits
263. Ugly Number
292. Nim Game
Mid:
592. Fraction Addition and Subtraction
-->

### SQL
* 175, 176, 181, 182, 183, 196, 197

### BASH
* 193, 195

### Other
* N Sum: 1, 167
* Contains Duplicate: 217, 219
* stock: 121, 122
* '+' Operation: 66, 2
* Palindrome: 9, 125, 234
* Power of x: 326, 231, 342
* Sort: 215
* Design data structure: 706
---

## Tier IV: Unclassified
* 509. Fibonacci Number
* 581	Shortest Unsorted Continuous Subarray
* 189	Rotate Array
* 78	Subsets    
* 90	Subsets II  


---
## Tier V: To Do List
* InOrderEasyOnly@: 371
* D&C: 17, 50, 78
* trie: 208
* 2pointer: 11
* Graph: 200, 547
* Greedy: 455, 874

https://leetcode.com/explore/interview/card/top-interview-questions-easy/
