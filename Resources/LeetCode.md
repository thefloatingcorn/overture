# Classifying LeetCode

## Intro
This classification is built to focus on the essential problems on LeetCode,
referring existing works such as:

* [https://mincongzhang.gitbooks.io/data_structures_and_algorithms/content/](https://mincongzhang.gitbooks.io/data_structures_and_algorithms/content/)
* [https://algorithm.yuanbin.me/en/](https://algorithm.yuanbin.me/en/)
* [https://blog.csdn.net/weixin_38118016/article/details/90761111](https://blog.csdn.net/weixin_38118016/article/details/90761111)
* [https://cspiration.com/leetcodeClassification](https://cspiration.com/leetcodeClassification)

---
## Tier I: Methods

### Binary Search:
Hint: sorted items; runtime complexity in the order of O(log n).

* Easy:
  * [278. First Bad Version](https://leetcode.com/problems/first-bad-version)
  * [69. Sqrt(x)](https://leetcode.com/problems/sqrtx)
  * [35. Search Insert Position](https://leetcode.com/problems/search-insert-position)
  * [704. Binary Search](https://leetcode.com/problems/binary-search)
* Mid:
  * [33. Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array)
  * [34. Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array)  
  * [74. Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/)
  * [153. Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array)
  * [456. 132 Pattern](https://leetcode.com/problems/132-pattern/)
  * [1283. Find the Smallest Divisor Given a Threshold](https://leetcode.com/problems/find-the-smallest-divisor-given-a-threshold/)
  * [81. Search in Rotated Sorted Array II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/)
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
* Mid:
  * [142. Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/)
  * [849. Maximize Distance to Closest Person](https://leetcode.com/problems/maximize-distance-to-closest-person/)
  * [845. Longest Mountain in Array](https://leetcode.com/problems/longest-mountain-in-array/)
  * [11. Container With Most Water](https://leetcode.com/problems/container-with-most-water/)
* Hard:
  * [42. Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water)

### Sliding Window
* Mid:
  * [3.	Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
  * [209. Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/)
  * [395. Longest Substring with At Least K Repeating Characters](https://leetcode.com/problems/longest-substring-with-at-least-k-repeating-characters/)
<!-- * [283.	Move Zeroes]
[443. String Compression]
  -->

### Dynamic Programming
Hint: how many possible ways.
* Easy:
  * [509. Fibonacci Number](https://leetcode.com/problems/fibonacci-number/)
  * [70. Climbing Stairs](https://leetcode.com/problems/climbing-stairs)  
  * [118.	Pascal's Triangle](https://leetcode.com/problems/pascals-triangle)
  * [198.	House Robber](https://leetcode.com/problems/house-robber)
* Mid:
  * [5. Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/)
  * [62. Unique Paths](https://leetcode.com/problems/unique-paths)
  * [322. Coin Change](https://leetcode.com/problems/coin-change)
  * [688. Knight Probability in Chessboard](https://leetcode.com/problems/knight-probability-in-chessboard)
  * [673. Number of Longest Increasing Subsequence](https://leetcode.com/problems/number-of-longest-increasing-subsequence/)
  * [416. Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/)
  * [91. Decode Ways](https://leetcode.com/problems/decode-ways/)
  * [413. Arithmetic Slices](https://leetcode.com/problems/arithmetic-slices/)
  * [376. Wiggle Subsequence](https://leetcode.com/problems/wiggle-subsequence/)
  <!-- 152. Maximum Product Subarray -->
* Hard:
  * [188. Best Time to Buy and Sell Stock IV](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iv/solution/)
  * [1510. Stone Game IV](https://leetcode.com/problems/stone-game-iv/)
  * [902. Numbers At Most N Given Digit Set](https://leetcode.com/problems/numbers-at-most-n-given-digit-set/)
  * [1463. Cherry Pickup II](https://leetcode.com/problems/cherry-pickup-ii/)
<!-- 204. Count Primes -->
<!-- 119 Pascal's Triangle II-->
<!-- 674. Longest Continuous Increasing Subsequence -->
<!-- 213. House Robber II -->
<!-- 337. House Robber III -->


### Divide and Conquer / (Recursion)
* [53. Maximum Subarray](https://leetcode.com/problems/maximum-subarray)
* [169.	Majority Element](https://leetcode.com/problems/majority-element)
* [148. Sort List](https://leetcode.com/problems/sort-list/)
* [395. Longest Substring with At Least K Repeating Characters](https://leetcode.com/problems/longest-substring-with-at-least-k-repeating-characters/)
* [218. The Skyline Problem](https://leetcode.com/problems/the-skyline-problem/)

### Greedy
* Easy:
  * [409. Longest Palindrome](https://leetcode.com/problems/longest-palindrome/)
  * [860. Lemonade Change](https://leetcode.com/problems/lemonade-change)
  * [435. Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/)
  * [763. Partition Labels](https://leetcode.com/problems/partition-labels/)
* Mid:
  * [452. Minimum Number of Arrows to Burst Balloons](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/)
  * [948. Bag of Tokens](https://leetcode.com/problems/bag-of-tokens/)
  * [881. Boats to Save People](https://leetcode.com/problems/boats-to-save-people/)
  * [870. Advantage Shuffle](https://leetcode.com/problems/advantage-shuffle/)
  
### Breadth/Depth-First Search
* [1306. Jump Game III](https://leetcode.com/problems/jump-game-iii/)
* [117. Populating Next Right Pointers in Each Node II](https://leetcode.com/problems/populating-next-right-pointers-in-each-node-ii/)
* [1345. Jump Game IV](https://leetcode.com/problems/jump-game-iv/)
* [127. Word Ladder](https://leetcode.com/problems/word-ladder/)
* [1631. Path With Minimum Effort](https://leetcode.com/problems/path-with-minimum-effort/)
* [784. Letter Case Permutation](https://leetcode.com/problems/letter-case-permutation/)
* [1091. Shortest Path in Binary Matrix](https://leetcode.com/problems/shortest-path-in-binary-matrix/)
* [785. Is Graph Bipartite?](https://leetcode.com/problems/is-graph-bipartite/)
* [841. Keys and Rooms](https://leetcode.com/problems/keys-and-rooms/)

### Backtracking
* Easy:
  * [949. Largest Time for Given Digits](https://leetcode.com/problems/largest-time-for-given-digits/)
  * [216. Combination Sum III](https://leetcode.com/problems/combination-sum-iii/)
  * [980. Unique Paths III](https://leetcode.com/problems/unique-paths-iii/)
* Mid:
  * [39. Combination Sum](https://leetcode.com/problems/combination-sum/)
  * [47. Permutations II](https://leetcode.com/problems/permutations-ii/)
  * [131. Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/)

### One-Pass
* Easy:
  * [179. Largest Number](https://leetcode.com/problems/teemo-attacking/)
  * [1446. Consecutive Characters](https://leetcode.com/problems/consecutive-characters/solution/)
  * [605. Can Place Flowers](https://leetcode.com/problems/can-place-flowers/)
  * [941. Valid Mountain Array](https://leetcode.com/problems/valid-mountain-array/)
* Mid:
  * [1007. Minimum Domino Rotations For Equal Row](https://leetcode.com/problems/minimum-domino-rotations-for-equal-row/)

### Sorting
* Mid:
  * [1288. Remove Covered Intervals](https://leetcode.com/problems/remove-covered-intervals/)
  * [1329. Sort the Matrix Diagonally](https://leetcode.com/problems/sort-the-matrix-diagonally/)
  * [147. Insertion Sort List](https://leetcode.com/problems/insertion-sort-list/)
  * [56. Merge Intervals](https://leetcode.com/problems/merge-intervals/)

### Simulation
* [858. Mirror Reflection](https://leetcode.com/problems/mirror-reflection/)
* [498. Diagonal Traverse](https://leetcode.com/problems/diagonal-traverse/)

---
## Tier II: Structures

### Array/List
* Easy:
  * [268.	Missing Number](https://leetcode.com/problems/missing-number)
  * [350.	Intersection of Two Arrays II](https://leetcode.com/problems/intersection-of-two-arrays-ii)
  * [189. Rotate Array](https://leetcode.com/problems/rotate-array/)
  * [1539. Kth Missing Positive Number](https://leetcode.com/problems/kth-missing-positive-number/)
  * [1437. Check If All 1's Are at Least Length K Places Away](https://leetcode.com/problems/check-if-all-1s-are-at-least-length-k-places-away/)
  * [594. Longest Harmonious Subsequence](https://leetcode.com/problems/longest-harmonious-subsequence/)
* Mid:
  * [334. Increasing Triplet Subsequence](https://leetcode.com/problems/increasing-triplet-subsequence/)
  * [1658. Minimum Operations to Reduce X to Zero](https://leetcode.com/problems/minimum-operations-to-reduce-x-to-zero/)
  * [1679. Max Number of K-Sum Pairs](https://leetcode.com/problems/max-number-of-k-sum-pairs/)
  * [1673. Find the Most Competitive Subsequence](https://leetcode.com/problems/find-the-most-competitive-subsequence/)

<!--  
  easy
  136	Single Number
  349. Intersection of Two Arrays
  448	Find All Numbers Disappeared in an Array
  905. Sort Array By Parity
-->

### Queue/Stack
* Easy:
  * [155.	Min Stack](https://leetcode.com/problems/min-stack)
  * [225.	Implement Stack using Queues](https://leetcode.com/problems/implement-stack-using-queues)
  * [232.	Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks)
* Mid:
  * [316. Remove Duplicate Letters](https://leetcode.com/problems/remove-duplicate-letters/)
  * [735. Asteroid Collision](https://leetcode.com/problems/asteroid-collision/)
  * [394. Decode String](https://leetcode.com/problems/decode-string/)
  * [227. Basic Calculator II](https://leetcode.com/problems/basic-calculator-ii/)
  * [71. Simplify Path](https://leetcode.com/problems/simplify-path/)
* Deque:
  * [239. Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/)
  * [977. Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/)

### LinkedList
* Easy:
  * [237.	Delete Node in a Linked List](https://leetcode.com/problems/delete-node-in-a-linked-list)
  * [203.	Remove Linked List Elements](https://leetcode.com/problems/remove-linked-list-elements)
  * [206.	Reverse Linked List](https://leetcode.com/problems/reverse-linked-list)
  * [21. Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/)
  * [141. Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)
* Mid:
  * [61. Rotate List](https://leetcode.com/problems/rotate-list/)
  * [445. Add Two Numbers II](https://leetcode.com/problems/add-two-numbers-ii/)
  * [382. Linked List Random Node](https://leetcode.com/problems/linked-list-random-node/)
  * [24. Swap Nodes in Pairs](https://leetcode.com/problems/swap-nodes-in-pairs/)
  * [138. Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/)
* Hard:
  * [23. Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/)

<!-- 
[21.	Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists)
[160.	Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists) -->
<!--
83 Remove Duplicates from Sorted List -->
<!--
* Mid:
  * 19.	Remove Nth Node From End of List
  * 24.	Swap Nodes in Pairs
  * 328.	Odd Even Linked List
  * 143. Reorder List
  -->

### Hash table
* Easy:
  * [706. Design HashMap](https://leetcode.com/problems/design-hashmap/)
  * [290. Word Pattern](https://leetcode.com/problems/word-pattern/)
  * [804. Unique Morse Code Words](https://leetcode.com/problems/unique-morse-code-words/)
* Mid:
  * [532. K-diff Pairs in an Array](https://leetcode.com/problems/k-diff-pairs-in-an-array/)
  * [187. Repeated DNA Sequences](https://leetcode.com/problems/repeated-dna-sequences/)
  * [1010. Pairs of Songs With Total Durations Divisible by 60](https://leetcode.com/problems/pairs-of-songs-with-total-durations-divisible-by-60/)
  * [454. 4Sum II](https://leetcode.com/problems/4sum-ii/)
  * [966. Vowel Spellchecker](https://leetcode.com/problems/vowel-spellchecker/)
  * [1396. Design Underground System](https://leetcode.com/problems/design-underground-system/)

### Tree
* Easy:
  * [104.	Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree)
  * [111. Minimum Depth of Binary Tree](https://leetcode.com/problems/minimum-depth-of-binary-tree/)
  * [101.	Symmetric Tree](https://leetcode.com/problems/symmetric-tree)
  * [226.	Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree)
  <!-- 1022. Sum of Root To Leaf Binary Numbers -->
* Mid:
  * [1026. Maximum Difference Between Node and Ancestor](https://leetcode.com/problems/maximum-difference-between-node-and-ancestor/)
  * [310. Minimum Height Trees](https://leetcode.com/problems/minimum-height-trees/)

* Binary Tree:
  * Traversal: 94 Inorder, 102 Level Order, 144 Preorder, 145 Postorder, 987 Vertical
  * [563. Binary Tree Tilt](https://leetcode.com/problems/binary-tree-tilt/)
  * [116. Populating Next Right Pointers in Each Node](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/)
  * [110. Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/)  
  * [1457. Pseudo-Palindromic Paths in a Binary Tree](https://leetcode.com/problems/pseudo-palindromic-paths-in-a-binary-tree/)
  * [199. Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/)
* BST:
  * [897. Increasing Order Search Tree](https://leetcode.com/problems/increasing-order-search-tree/)
  * [938. Range Sum of BST](https://leetcode.com/problems/range-sum-of-bst/)
  * [99. Recover Binary Search Tree]()
  * [235. Lowest Common Ancestor of a Binary Search Tree]()
  * [108. Convert Sorted Array to Binary Search Tree]()
  * [538. Convert BST to Greater Tree](https://leetcode.com/problems/convert-bst-to-greater-tree/)
  * [450. Delete Node in a BST]()
  * [701. Insert into a Binary Search Tree]()
  * [449. Serialize and Deserialize BST]()
  * [173. Binary Search Tree Iterator](https://leetcode.com/problems/binary-search-tree-iterator/)
  * [98. Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/)
  * [669. Trim a Binary Search Tree](https://leetcode.com/problems/trim-a-binary-search-tree/)
  
<!--
*257. Binary Tree Paths*
111	Minimum Depth of Binary Tree    
112	Path Sum  
100 Same Tree
107	Binary Tree Level Order Traversal II
110	Balanced Binary Tree   
* 543.	Diameter of Binary Tree
* 617.	Merge Two Binary Trees
404. Sum of Left Leaves
1305. All Elements in Two Binary Search Trees
-->
  
### Graph
* Mid
    * [133. Clone Graph](https://leetcode.com/problems/clone-graph/)
    * [399. Evaluate Division](https://leetcode.com/problems/evaluate-division/)
* Hard
    * [952. Largest Component Size by Common Factor](https://leetcode.com/problems/largest-component-size-by-common-factor/)

### Heap
* [218. The Skyline Problem](https://leetcode.com/problems/the-skyline-problem/)

### Char/Str
* Easy
  * [14. Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix)
  * [28. Implement strStr()](https://leetcode.com/problems/implement-strstr)
  * [58. Length of Last Word](https://leetcode.com/problems/length-of-last-word)
* Mid:
  * [880. Decoded String at Index](https://leetcode.com/problems/decoded-string-at-index/solution/)
  * [1657. Determine if Two Strings Are Close](https://leetcode.com/problems/determine-if-two-strings-are-close/)
* ord() / chr()
  * [168. Excel Sheet Column Title](https://leetcode.com/problems/excel-sheet-column-title)
  * [171. Excel Sheet Column Number](https://leetcode.com/problems/excel-sheet-column-number)
  * [389. Find the Difference](https://leetcode.com/problems/find-the-difference)  

<!--
205. Isomorphic Strings
* 344. Reverse String
* 383. Ransom Note
* 387. First Unique Character in a String
* 459. Repeated Substring Pattern
* 771. Jewels and Stones
20	Valid Parentheses
242	Valid Anagram
299. Bulls and Cows
345. Reverse Vowels of a String
520. Detect Capital
824. Goat Latin
Mid:
49. Group Anagrams
166. Fraction to Recurring Decimal
179. Largest Number
  -->

### Bit
* [190.	Reverse Bits](https://leetcode.com/problems/reverse-bits)
* [191.	Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits)
* [371. Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers)
* [1009. Complement of Base 10 Integer](https://leetcode.com/problems/complement-of-base-10-integer)
* [1290. Convert Binary Number in a Linked List to Integer](https://leetcode.com/problems/convert-binary-number-in-a-linked-list-to-integer/)
* [1342. Number of Steps to Reduce a Number to Zero](https://leetcode.com/problems/number-of-steps-to-reduce-a-number-to-zero/)

---

## Tier III: Topics

### Math
* Easy:
  * [7.	Reverse Integer](https://leetcode.com/problems/reverse-integer)
  * [172.	Factorial Trailing Zeroes](https://leetcode.com/problems/factorial-trailing-zeroes)
  * [202.	Happy Number](https://leetcode.com/problems/happy-number)
* Mid:
  * [1492. The kth Factor of n](https://leetcode.com/problems/the-kth-factor-of-n/)
  * [754. Reach a Number](https://leetcode.com/problems/reach-a-number/)
  * [2. Add Two Numbers](https://leetcode.com/problems/add-two-numbers/)
  * [869. Reordered Power of 2](https://leetcode.com/problems/reordered-power-of-2/)
<!--
412.	Fizz Buzz
258. Add Digits
263. Ugly Number
292. Nim Game
Mid:
592. Fraction Addition and Subtraction
1291. Sequential Digits
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
* Design data structure: 706, 284
* DFS: 200,
* Majority Element: 229
* Subarray: 713
* Heap: 1337
---

## Tier IV: Unclassified
* [509. Fibonacci Number]
* [581. Shortest Unsorted Continuous Subarray]
* [189. Rotate Array]
* [78. Subsets]
* [90. Subsets II]
* [134. Gas Station]
* [50. Pow(x, n)]
* [705. Design HashSet]
* [211. Add and Search Word - Data structure design]
* [969. Pancake Sorting]
* [220. Contains Duplicate III]
* [835. Image Overlap]
* [1041. Robot Bounded In Circle]
* [1094. Car Pooling]
* [41. First Missing Positive]
* [933. Number of Recent Calls]
* [859. Buddy Strings]
* [799. Champagne Tower]
* [228. Summary Ranges]
* [1217. Minimum Cost to Move Chips to The Same Position]
* [832. Flipping an Image]
* [593. Valid Square]
* [458. Poor Pigs]
* [1015. Smallest Integer Divisible by K]
* [59. Spiral Matrix II]
* [556. Next Greater Element III]
* [910. Smallest Range II]
* [1680. Concatenation of Consecutive Binary Numbers]
* [1663. Smallest String With A Given Numeric Value]
* [923. 3Sum With Multiplicity]
* [12. Integer to Roman]

---
## Tier V: To Do List
* InOrderEasyOnly@: 371
* D&C: 17, 50, 78 
* 2pointer: 11
* Graph: 200, 547
* Greedy: 455, 874
* Trie: 139, 208, 421

https://leetcode.com/explore/interview/card/top-interview-questions-easy/
