# Google SWE 3 Interview Question Bank (Topic-Based)

Use this as a menu: pick a topic, then choose a question number to solve here in chat.
If you want a full mock interview, jump to the "Realistic Interview Simulations" section.

## 1) Arrays & Strings
1. Two Sum (indices) with constraints on duplicates.
2. Longest Substring Without Repeating Characters.
3. Minimum Window Substring.
4. Product of Array Except Self (no division).
5. Rotate Array by `k` steps (in-place).
6. String to Integer (atoi) with edge cases.
7. Valid Anagram (Unicode vs ASCII considerations).
8. Group Anagrams (time/space trade-offs).
9. Longest Palindromic Substring.
10. Spiral Matrix traversal.

## 2) Hashing & Sets
1. First Missing Positive (O(n) time, O(1) space).
2. Longest Consecutive Sequence.
3. Subarray Sum Equals K.
4. Continuous Subarray Sum (multiple of k).
5. Top K Frequent Elements.
6. Encode/Decode Strings.
7. Isomorphic Strings.
8. Design a HashMap (without built-ins).

## 3) Two Pointers / Sliding Window
1. Container With Most Water.
2. Trapping Rain Water.
3. Longest Repeating Character Replacement.
4. Max Consecutive Ones III.
5. Minimum Size Subarray Sum.
6. Remove Duplicates From Sorted Array (in-place).
7. Merge Sorted Array (in-place).

## 4) Sorting / Searching / Binary Search
1. Binary Search in Rotated Sorted Array.
2. Find First and Last Position of Element in Sorted Array.
3. Kth Largest Element in an Array.
4. Merge Intervals.
5. Search a 2D Matrix.
6. Median of Two Sorted Arrays.
7. Koko Eating Bananas (binary search on answer).

## 5) Linked Lists
1. Reverse Linked List.
2. Merge Two Sorted Lists.
3. Remove Nth Node From End of List.
4. Linked List Cycle + Cycle II.
5. Reorder List.
6. Add Two Numbers (digits in reverse order).
7. Copy List with Random Pointer.

## 6) Stacks & Queues
1. Valid Parentheses.
2. Min Stack (O(1) getMin).
3. Evaluate Reverse Polish Notation.
4. Daily Temperatures (monotonic stack).
5. Next Greater Element II (circular).
6. Sliding Window Maximum (deque).

## 7) Trees (Binary, BST, N-ary)
1. Maximum Depth of Binary Tree.
2. Diameter of Binary Tree.
3. Lowest Common Ancestor (BST vs Binary Tree).
4. Validate Binary Search Tree.
5. Serialize/Deserialize Binary Tree.
6. Binary Tree Level Order Traversal.
7. Construct Binary Tree from Preorder & Inorder.

## 8) Graphs (BFS/DFS/Topo/Union-Find)
1. Number of Islands.
2. Clone Graph.
3. Course Schedule (topological sort).
4. Pacific Atlantic Water Flow.
5. Word Ladder (BFS shortest path).
6. Redundant Connection (union-find).
7. Accounts Merge (union-find).
8. Shortest Path in Binary Matrix.

## 9) Dynamic Programming
1. Climbing Stairs.
2. House Robber + House Robber II.
3. Coin Change.
4. Longest Increasing Subsequence.
5. Edit Distance.
6. Word Break.
7. Maximum Subarray.
8. Minimum Path Sum (grid).

## 10) Greedy
1. Jump Game.
2. Gas Station.
3. Partition Labels.
4. Task Scheduler.
5. Merge Triplets to Form Target Triplet.

## 11) Backtracking
1. Subsets.
2. Subsets II (with duplicates).
3. Permutations.
4. Permutations II.
5. Combination Sum.
6. Generate Parentheses.
7. N-Queens.

## 12) Heaps / Priority Queues
1. Kth Largest Element in a Stream.
2. Find Median from Data Stream.
3. Merge K Sorted Lists.
4. Task Scheduler (heap + greedy).
5. Top K Frequent Words.

## 13) Bit Manipulation
1. Single Number.
2. Single Number II.
3. Counting Bits.
4. Reverse Bits.
5. Sum of Two Integers (no `+`/`-`).

## 14) Intervals
1. Insert Interval.
2. Non-overlapping Intervals.
3. Meeting Rooms I & II.
4. Minimum Number of Arrows to Burst Balloons.

## 15) System Design (SWE 3-lite)
1. Design a URL Shortener.
2. Design a Rate Limiter.
3. Design an Autocomplete System.
4. Design a News Feed.
5. Design a Distributed Queue (high level).

---

# Realistic Interview Simulations (Google SWE 3 Style)

These are structured like actual interviews: a short prompt, clarification questions,
and follow-up prompts you would likely hear if you solve the base problem quickly.
Tell me which simulation you want, and I will play the interviewer.

## Simulation A: Arrays + Hashing (45 min)
**Problem (base):** Given an array of integers `nums` and integer `k`, return the number
of subarrays whose sum equals `k`.
**Clarifications typically asked:**
- Can `nums` contain negative values? (Yes.)
- Expected time complexity? (Better than O(n^2).)
**Follow-ups if solved:**
1. What if you need to support multiple `k` queries efficiently?
2. Can you do it in O(n) time and O(n) space? Prove correctness.

## Simulation B: Sliding Window + String (45 min)
**Problem (base):** Given a string `s`, find the length of the longest substring
without repeating characters.
**Clarifications typically asked:**
- Input size? (Assume up to 10^5.)
- Character set? (ASCII.)
**Follow-ups if solved:**
1. Return the substring itself, not just the length.
2. How would you adapt this for Unicode?

## Simulation C: Trees (45 min)
**Problem (base):** Given a binary tree, return its diameter.
**Clarifications typically asked:**
- Does diameter mean number of edges or nodes? (Edges.)
**Follow-ups if solved:**
1. Return the actual path nodes forming the diameter.
2. Can you do it in one DFS pass?

## Simulation D: Graphs (45 min)
**Problem (base):** Given a 2D grid of `0`s and `1`s, return the number of islands.
**Clarifications typically asked:**
- Can we mutate the grid? (Yes.)
- Diagonal connections? (No.)
**Follow-ups if solved:**
1. Count distinct island shapes.
2. What is the memory footprint for a 10k x 10k grid?

## Simulation E: Dynamic Programming (45 min)
**Problem (base):** Given coins of different denominations and a total amount,
compute the fewest number of coins needed to make up that amount.
**Clarifications typically asked:**
- Can you use each coin unlimited times? (Yes.)
**Follow-ups if solved:**
1. Return the actual coin combination.
2. Optimize for very large amounts.

## Simulation F: System Design (60 min)
**Problem (base):** Design a rate limiter for an API.
**Clarifications typically asked:**
- Are there multiple clients? (Yes.)
- Is this distributed? (Assume yes.)
**Follow-ups if solved:**
1. Discuss token bucket vs leaky bucket trade-offs.
2. Storage choices and approximate counting at scale.
