# 6-Week DSA Interview Prep Study Plan

This plan organizes your 75 patterns into a progressive learning path, building from fundamentals to advanced topics.

## How to Use This Plan

1. **Study one pattern per day** (aim for 2-3 hours per pattern)
2. **Follow the sequence** - later patterns build on earlier ones
3. **Complete practice problems** for each pattern (see practice-tracker.md)
4. **Review previous patterns** every weekend (spaced repetition)
5. **Mark your progress** in practice-tracker.md

---

## Week 1: Fundamentals & Array Techniques

**Goal:** Master basic problem-solving patterns and array manipulation

### Day 1-2: Core Foundations
- **Day 1:** Time Complexity + Maths (base systems, modular arithmetic)
  - *Why:* Understanding complexity is critical for optimization discussions
  - *Notes:* `/notes/patterns/` - Time Complexity, Maths patterns

- **Day 2:** Bitwise Operations + Logarithms, Permutations, Subsets
  - *Why:* Bit manipulation appears in optimization problems
  - *Notes:* Bit Manipulation, Maths patterns

### Day 3-4: Array Fundamentals
- **Day 3:** Prefix Sum + Product Except Self + Kadane's Algorithm
  - *Why:* Prefix sum is a foundational technique for range queries
  - *Connects to:* DP, Sliding Window
  - *Notes:* Prefix sum, Product Except Self, Kadane's algorithm

- **Day 4:** Two Pointers (Sorted Array Target Sum, Container With Most Water)
  - *Why:* Core technique for O(n²) → O(n) optimization
  - *Connects to:* Sliding Window, String problems
  - *Notes:* Two Pointers patterns

### Day 5-7: Advanced Array Patterns
- **Day 5:** Sliding Window - Fixed Size + Variable Size
  - *Why:* Essential for substring/subarray problems
  - *Connects to:* Two Pointers, Strings
  - *Notes:* Fixed Size (Find anagrams), Variable Size (Longest Substring)

- **Day 6:** Sliding Window Maximum (Monotonic Queue/Stack) + Monotonic Stack (Remove k digits)
  - *Why:* Advanced optimization technique
  - *Connects to:* Stack, Deque
  - *Notes:* Monotonic Queue/Stack patterns

- **Day 7:** In-place Array Manipulation
  - *Patterns:* Move Zeroes, In-place Rotation, Cyclic Sort, Merge Sorted Array
  - *Why:* Space optimization (O(n) → O(1))
  - *Notes:* Array manipulation patterns

**Weekend Review:** Practice 2-3 mixed problems from Week 1 patterns

---

## Week 2: Data Structures Fundamentals

**Goal:** Build strong foundation in core data structures

### Day 8-9: Stack & String Manipulation
- **Day 8:** Stack Basics + Valid Parentheses + Expression Evaluation
  - *Why:* Stack is fundamental for parsing and evaluation
  - *Connects to:* Trees (DFS uses stack), Recursion
  - *Notes:* Valid Parentheses, Basic Calculator

- **Day 9:** String Algorithms
  - *Patterns:* String To Integer (ATOI), String Reversal, String Matching (Rabin Karp)
  - *Connects to:* Two Pointers, Sliding Window
  - *Notes:* String patterns

### Day 10-11: String Advanced & Linked Lists
- **Day 10:** Expanding from Center (Longest Palindrome Substring)
  - *Why:* Important technique for palindrome problems
  - *Connects to:* DP (palindrome partitioning)
  - *Notes:* Expanding from Center

- **Day 11:** Linked List Basics
  - *Patterns:* Merge Two Sorted Lists, Remove Nth Node from End
  - *Why:* Pointer manipulation skills
  - *Connects to:* Two Pointers, Recursion
  - *Notes:* Linked List patterns

### Day 12-13: Linked List Advanced & Binary Search
- **Day 12:** Advanced Linked List
  - *Patterns:* In-Place Reversal, Intersection Detection, Floyd's Cycle Detection, Rotate List
  - *Why:* Classic interview patterns
  - *Notes:* Linked List patterns

- **Day 13:** Binary Search Fundamentals
  - *Patterns:* Monotonic function patterns, Find Min/Max in rotated sorted array
  - *Why:* O(n) → O(log n) optimization
  - *Connects to:* Trees (BST), Divide & Conquer
  - *Notes:* Binary Search patterns

### Day 14: Binary Search Advanced & Heaps Introduction
- **Day 14 Morning:** Binary Search Advanced
  - *Patterns:* Find k closest elements, Median of 2 Sorted Arrays
  - *Notes:* Binary Search patterns

- **Day 14 Afternoon:** Heap Basics + Min Heap
  - *Why:* Priority queue is essential for many algorithms
  - *Connects to:* Greedy, Graphs (Dijkstra)
  - *Notes:* Min Heap pattern

**Weekend Review:** Build a sample project using Stack + Linked List + Heap

---

## Week 3: Trees & Graphs

**Goal:** Master tree and graph traversal algorithms

### Day 15-16: Tree Traversal Fundamentals
- **Day 15:** BFS + DFS Preorder + DFS Inorder
  - *Patterns:* Binary Tree Level Order Traversal, Same Tree, Validate BST
  - *Why:* Foundation for all tree problems
  - *Connects to:* Stack/Queue, Recursion
  - *Notes:* Tree Traversal patterns

- **Day 16:** DFS Postorder + Lowest Common Ancestor + Serialize/Deserialize
  - *Why:* Advanced tree manipulation
  - *Connects to:* Recursion, String parsing
  - *Notes:* Tree Traversal patterns

### Day 17-18: Matrix & Graph Fundamentals
- **Day 17:** Matrix Traversal
  - *Patterns:* Spiral Traversal, Set Matrix Zeroes
  - *Why:* Grid-based problems are common
  - *Connects to:* 2D DP, Graph traversal
  - *Notes:* Matrix patterns

- **Day 18:** Graph DFS + BFS
  - *Patterns:* Number of Islands (DFS), Rotting Oranges (BFS)
  - *Why:* Core graph traversal techniques
  - *Connects to:* Tree traversal, Backtracking
  - *Notes:* Graph Traversal patterns

### Day 19-20: Graph Algorithms Part 1
- **Day 19:** Cycle Detection + Topological Sort
  - *Patterns:* Course Schedule II (DFS Cycle Detection), Kahn's algorithm
  - *Why:* Essential for dependency problems
  - *Connects to:* DFS, BFS, Recursion
  - *Notes:* Graph Traversal patterns

- **Day 20:** Union Find + MST
  - *Patterns:* Network Connected (Union Find), Kruskal's algorithm (MST)
  - *Why:* Efficient connectivity and spanning problems
  - *Connects to:* Greedy algorithms
  - *Notes:* Graph Traversal patterns

### Day 21: Graph Algorithms Part 2 (Shortest Path)
- **Day 21:** Shortest Path Algorithms
  - *Patterns:* Dijkstra's, Bellman Ford, Floyd Warshall
  - *Why:* Core algorithms for weighted graphs
  - *Connects to:* Heap (Dijkstra), DP (Bellman Ford)
  - *Notes:* Network Delay Time, Cheapest Flights, Minimum Cost String Conversion

**Weekend Review:** Solve 3 graph problems combining different algorithms

---

## Week 4: Backtracking, Greedy & Heap Mastery

**Goal:** Learn decision-making patterns and optimization strategies

### Day 22-24: Backtracking Patterns
- **Day 22:** Subset + Permutations
  - *Why:* Generate all possible solutions
  - *Connects to:* Recursion, DFS
  - *Notes:* Subset, Permutations (Unique)

- **Day 23:** Combination Sum + Palindrome Partitioning
  - *Why:* Constrained generation with pruning
  - *Connects to:* DP (optimization version)
  - *Notes:* Combination Sum, Palindrome Partitioning

- **Day 24:** Backtracking Review + Practice
  - *Goal:* Recognize backtracking triggers (generate all, find all valid)
  - *Practice:* Mixed backtracking problems

### Day 25-27: Greedy Algorithms
- **Day 25:** Merge Intervals + Jump Game
  - *Why:* Greedy choice property
  - *Connects to:* Sorting, Arrays
  - *Notes:* Merge Interval, Jump Game

- **Day 26:** Task Scheduling + Candy
  - *Why:* Optimization with local choices
  - *Connects to:* Heap (Task Scheduling)
  - *Notes:* Task Scheduling, Candy

- **Day 27:** Heap Advanced Patterns
  - *Patterns:* Find Median from Data Stream, Merge k sorted lists
  - *Why:* Heap mastery for complex problems
  - *Notes:* Heap patterns

### Day 28: Advanced Data Structures
- **Day 28:** Design Patterns + Advanced Structures
  - *Patterns:* LRU Cache, Trie (Prefix Tree), Min Heap vs BST, Fenwick Tree
  - *Why:* System design & optimization
  - *Connects to:* HashMap, Linked List, Binary Search
  - *Notes:* Design patterns, Fenwick tree

**Weekend Review:** Design a mini-system using multiple data structures

---

## Week 5: Dynamic Programming Part 1

**Goal:** Master DP fundamentals and common patterns

### Day 29-30: DP Foundations
- **Day 29:** 1D DP (Basic)
  - *Pattern:* Fibonacci, Climbing Stairs concepts
  - *Why:* Understand memoization vs tabulation
  - *Notes:* Basic (Fibonacci - 1D Array)

- **Day 30:** Grid DP
  - *Pattern:* Unique Paths
  - *Why:* 2D state space, common in interviews
  - *Connects to:* Matrix traversal
  - *Notes:* Grid (Unique Paths)

### Day 31-32: Sequence DP
- **Day 31:** Longest Increasing Subsequence (Dynamic Number of Subproblems)
  - *Why:* Classic DP with O(n²) and O(n log n) solutions
  - *Connects to:* Binary Search optimization
  - *Notes:* Dynamic Number of Subproblems (LIS)

- **Day 32:** Dual Sequence DP
  - *Pattern:* Longest Common Subsequence
  - *Why:* Compare two sequences
  - *Connects to:* Edit Distance, String matching
  - *Notes:* Dual Sequence (LCS)

### Day 33-34: Knapsack Patterns
- **Day 33:** 0/1 Knapsack
  - *Patterns:* Target Sum (Top-down), Partition Equal Subset Sum (Bottom-up)
  - *Why:* Include/exclude decision pattern
  - *Notes:* 0/1 Knapsack patterns

- **Day 34:** Unbounded Knapsack
  - *Pattern:* Coin Change
  - *Why:* Unlimited use of items
  - *Connects to:* Combination Sum (backtracking version)
  - *Notes:* Unbounded Knapsack (Coin Change)

### Day 35: DP Review Day
- **Day 35:** Review Week 5 patterns
  - *Goal:* Identify when to use 1D vs 2D DP
  - *Practice:* Mixed DP problems from Week 5

**Weekend Review:** Solve 5 DP problems covering all patterns from Week 5

---

## Week 6: Dynamic Programming Part 2 & Advanced Topics

**Goal:** Master advanced DP and integrate all knowledge

### Day 36-37: Advanced DP Patterns
- **Day 36:** Interval DP
  - *Pattern:* Bursting Balloons
  - *Why:* Subproblem is a range [i, j]
  - *Notes:* Interval DP (Busting Balloons)

- **Day 37:** Word Break + String DP
  - *Pattern:* Word Break
  - *Why:* String partitioning with dictionary
  - *Connects to:* Trie, Backtracking
  - *Notes:* Word Break

### Day 38-39: State Machine DP
- **Day 38:** Best Time to Buy and Sell Stock I & II
  - *Why:* State-based DP (hold/not hold)
  - *Connects to:* Greedy (Stock II)
  - *Notes:* Stock patterns

- **Day 39:** DP Mastery Day
  - *Goal:* Practice all 11 DP patterns
  - *Focus:* Identify which pattern applies to new problems
  - *Practice:* 3-4 mixed DP problems

### Day 40-41: Advanced Sorting & Final Topics
- **Day 40:** Quick Sort + Advanced Array Topics
  - *Patterns:* Quick Sort implementation, partitioning
  - *Why:* Understanding sorting internals
  - *Connects to:* Divide & Conquer
  - *Notes:* Quick Sort

- **Day 41:** Final Integration Day
  - *Goal:* Solve problems requiring multiple patterns
  - *Practice:* 3 hard problems combining techniques
  - *Example:* Sliding Window + Heap, DP + Graph, etc.

### Day 42: Mock Interview & Gap Analysis
- **Day 42:** Full Mock Interview
  - *Format:* 2-3 medium/hard problems (60-90 min)
  - *Focus:* Communication, optimization, edge cases
  - *Goal:* Identify weak patterns for final week review

**Final Weekend:**
- Review your 3 weakest pattern categories
- Practice explaining solutions out loud
- Prepare your interview story (project experiences)

---

## Daily Study Routine Template

### For Each Pattern (2-3 hours):

1. **Understand (30 min)**
   - Read the pattern explanation in your notes
   - Understand when and why to use it
   - Identify the time/space complexity

2. **Implement (45 min)**
   - Code the solution from scratch (don't copy)
   - Run through test cases
   - Compare with your notes

3. **Practice (45 min)**
   - Solve 1-2 related LeetCode problems
   - Use pattern-recognition-guide.md to identify the pattern
   - Track in practice-tracker.md

4. **Review & Connect (30 min)**
   - How does this relate to patterns you've learned?
   - When would you choose this over alternatives?
   - Update concept-relationships.md if needed

---

## Spaced Repetition Schedule

### Weekly Review Days:
- **End of Week 1:** Review all array/two-pointer/sliding window
- **End of Week 2:** Review Week 1 + data structures
- **End of Week 3:** Review graphs/trees + quick drill on Week 1-2
- **End of Week 4:** Review backtracking/greedy + trees
- **End of Week 5:** Review DP Part 1 + graphs
- **End of Week 6:** Comprehensive review - weak areas focus

### Pattern Review Intervals:
- **Day 1:** Learn pattern
- **Day 3:** Quick review (10 min)
- **Day 7:** Practice 1 problem
- **Day 14:** Practice 1 problem
- **Day 30:** Final review before interview

---

## Progress Tracking

Use `practice-tracker.md` to mark:
- ✅ Pattern understood
- ✅ Can implement from scratch
- ✅ Solved 3+ practice problems
- ✅ Can explain when to use this pattern

---

## Pre-Interview Final Week

### 7 Days Before Interview:
- Review quick-reference.md daily
- Solve 2 random medium problems per day
- Focus on pattern recognition speed

### 3 Days Before Interview:
- Review pattern-combinations.md
- Practice verbalizing your thought process
- Review common edge cases

### 1 Day Before Interview:
- Light review of quick-reference.md
- Relax - you've covered 75 patterns!
- Get good sleep

---

## Key Success Metrics

Track these weekly:
- **Patterns mastered:** X / 75
- **Problems solved:** Target 150+ (2-3 per pattern)
- **Recognition speed:** Can identify pattern in < 2 min
- **Implementation speed:** Medium problem in < 25 min

---

## Next Steps

1. Start with Week 1, Day 1
2. Open `practice-tracker.md` and mark your first pattern
3. Use `pattern-recognition-guide.md` when solving practice problems
4. Update your progress daily

Good luck with your preparation! 🚀
