# NeetCode-250 Explanations

This repository contains explanations for most of the problems listed in the **[NeetCode-250](https://neetcode.io/roadmap)** and hand-picked problems by myself. Each problem is explained in detail, including the approach, diagrams, code snippets, time complexity, and space complexity. 

I keep this repository updated with new explanations as I work through the problems. This is used as a personal reference and also to help others who are preparing for coding interviews.

## [Arrays](Arrays/)

`Arrays` are a fundamental data structure that store a fixed number of values of the same type. They allow for efficient access to elements using an index.

| Problem | Explanation |
|---------|-------------|
| [48. Rotate Image](./Arrays/48.%20Rotate%20Image.md) | We have to rotate a given n x n 2D matrix by 90 degrees clockwise. |
| [118. Pascal's Triangle](./Arrays/118.%20Pascal's%20Triangle.md) | We have to generate the first numRows of Pascal's triangle. |
| [128. Longest Consecutive Sequence](./Arrays/128.%20Longest%20Consecutive%20Sequence.md) | We have to find the length of the longest consecutive elements sequence in an unsorted array. |
| [229. Majority Element II](./Arrays/229.%20Majority%20Element%20II.md) | We have to find all elements that appear more than n/3 times in an array. |

---

## [Two Pointers](Two%20Pointers/)

`Two Pointers` is a technique used to solve problems that involve finding pairs or triplets of elements in an array that satisfy certain conditions. It involves using two pointers to traverse the array from both ends towards the center.

| Problem | Explanation |
|---------|-------------|
| [15. 3Sum](./Two%20Pointers/15.%203Sum.md) | Find all unique triplets in the array which gives the sum of zero. |
| [18. 4Sum](./Two%20Pointers/18.%204Sum.md) | Find all unique quadruplets in the array which gives the sum of a target. |
| [31. Next Permutation](./Two%20Pointers/31.%20Next%20Permutation.md) | Rearrange numbers into the lexicographically next greater permutation of numbers. |
| [881. Boats to Save People](./Two%20Pointers/881.%20Boats%20to%20Save%20People.md) | Find the minimum number of boats required to save all people given their weights and the boat's limit. |
| [2149. Rearrange Array Elements by Sign](./Two%20Pointers/2149.%20Rearrange%20Array%20Elements%20by%20Sign.md) | Rearrange the elements of an array such that positive and negative numbers are placed alternately. |
---

## [Sliding Window](Sliding%20Window/)

`Sliding Window` is a technique used to solve problems that involve finding a contiguous subarray or substring that satisfies certain conditions. It involves maintaining a window of elements and sliding it across the data structure to find the desired result.

| Problem | Explanation |
|---------|-------------|
| [3. Longest Substring Without Repeating Characters](./Sliding%20Window/3.%20Longest%20Substring%20Without%20Repeating%20Characters.md) | Find the length of the longest substring without repeating characters in a given string. |
| [76. Minimum Window Substring](./Sliding%20Window/76.%20Minimum%20Window%20Substring.md) | Find the minimum window in a string that contains all the characters of another string. |
| [209. Minimum Size Subarray Sum](./Sliding%20Window/209.%20Minimum%20Size%20Subarray%20Sum.md) | Find the minimum length of a contiguous subarray of which the sum is greater than or equal to a given target. |
| [424. Longest Repeating Character Replacement](./Sliding%20Window/424.%20Longest%20Repeating%20Character%20Replacement.md) | Find the length of the longest substring that can be obtained by replacing `at most k` characters in a given string. |
| [992. Subarrays with K Different Integers](./Sliding%20Window/992.%20Subarrays%20with%20K%20Different%20Integers.md) | Find the number of subarrays with `exactly k` different integers in a given array. |
| [1838. Frequency of the Most Frequent Element](./Sliding%20Window/1838.%20Frequency%20of%20the%20Most%20Frequent%20Element.md) | Find the maximum frequency of an element in an array after performing `at most k` increment operations. |
| [2134. Minimum Swaps to Group All 1's Together](./Sliding%20Window/2134.%20Minimum%20Swaps%20to%20Group%20All%201's%20Together.md) | Find the minimum number of swaps required to group all 1's together in a binary `circular` array. |

---

## [Binary Search](Binary%20Search/)

`Binary Search` is a search algorithm that finds the position of a target value within a sorted array. It works by repeatedly dividing the search interval in half until the target value is found or the interval is empty.

| Problem | Explanation |
|---------|-------------|
| [33. Search in Rotated Sorted Array](./Binary%20Search/33.%20Search%20in%20Rotated%20Sorted%20Array.md) | Find the index of a target value in a rotated sorted array. |
| [410. Split Array Largest Sum](./Binary%20Search/410.%20Split%20Array%20Largest%20Sum.md) | Split an array into `m` non-empty continuous subarrays and minimize the largest sum among these subarrays. |
| [540. Single Element in a Sorted Array](./Binary%20Search/540.%20Single%20Element%20in%20a%20Sorted%20Array.md) | Find the single element in a sorted array where every other element appears twice. |
| [981. Time Based Key-Value Store](./Binary%20Search/981.%20Time%20Based%20Key-Value%20Store.md) | Implement a time-based key-value store that can retrieve the value of a key at a specific timestamp. |

---

## [Heaps](Heaps/)

`Heaps` are a specialized tree-based data structure that satisfies the heap property. In a max heap, for any given node C, if P is a parent node of C, then the key (the value) of P is greater than or equal to the key of C. In a min heap, the key of P is less than or equal to the key of C.

| Problem | Explanation |
|---------|-------------|
| [973. K Closest Points to Origin](./Heaps/995.%20K%20Closest%20Points%20to%20Origin.md) | Find the k closest points to the origin in a 2D plane. |

---

## [Backtracking](Backtracking/)

`Backtracking` is a general algorithm for finding all (or some) solutions to computational problems, notably constraint satisfaction problems.

| Problem | Explanation |
|---------|-------------|
| [52. N-Queens II](./Backtracking/52.%20N-Queens%20II.md) | We have to find the number of Queens arrangements on the chessboard.| 
| [77. Combinations](./Backtracking/77.%20Combinations.md) | We have to find all the combinations of k numbers from 1 to n.|
| [79. Word Search](./Backtracking/79.%20Word%20Search.md) | We have to find if a given word exists in a 2D grid of characters. |
| [140. Word Break II](./Backtracking/140.%20Word%20Break%20II.md) | We have to find all possible sentences that can be formed by concatenating words from a given dictionary. |
| [698. Partition to K Equal Sum Subsets](./Backtracking/698.%20Partition%20to%20K%20Equal%20Sum%20Subsets.md) | We have to determine if we can partition an array into k subsets with equal sums. |

---

## [BFS and DFS](Graphs/)

`Breadth-First Search (BFS)` is an algorithm for traversing or searching tree or graph data structures. It starts at the tree root (or an arbitrary node of a graph) and explores the neighbor nodes at the present depth prior to moving on to the nodes at the next depth level.

`Depth-First Search (DFS)` is an algorithm for traversing or searching tree or graph data structures. It starts at the root node and explores as far as possible along each branch before backtracking.

| Problem | Explanation |
|---------|-------------|
| [127. Word Ladder](./Graphs/127.%20Word%20Ladder.md) | Find the length of the shortest transformation sequence from a start word to an end word, changing only one letter at a time and using only words from a given dictionary. |
| [130. Surrounded Regions](./Graphs/130.%20Surrounded%20Regions.md) | We have to capture all regions that are surrounded by 'X' in a 2D grid. |
| [133. Clone Graph](./Graphs/133.%20Clone%20Graph.md) | Create a deep copy of an undirected graph and return the reference to the cloned graph. |
| [200. Number of Islands](./Graphs/200.%20Number%20of%20Islands.md) | We have to find the number of islands in a 2D grid. |
| [417. Pacific Atlantic Water Flow](./Graphs/417.%20Pacific%20Atlantic%20Water%20Flow.md) | We have to find the cells in a grid where water can flow to both the Pacific and Atlantic oceans. |
| [785. Is Graph Bipartite?](./Graphs/785.%20Is%20Graph%20Bipartite.md) | We have to determine if a graph can be colored using two colors without adjacent nodes sharing the same color. |
| [994. Rotting Oranges](./Graphs/994.%20Rotting%20Oranges.md) | We have to find the minimum time required for all oranges to rot in a grid. |

---

## [Topological Sort](Graphs/)

`Topological Sort` is a linear ordering of vertices in a directed graph such that for every directed edge uv from vertex u to vertex v, u comes before v in the ordering.

| Problem | Explanation |
|---------|-------------|
| [207. Course Schedule](./Graphs/207.%20Course%20Schedule.md) | We have to determine if it is possible to finish all courses given the prerequisites. |
| [210. Course Schedule II](./Graphs/210.%20Course%20Schedule%20II.md) | We have to find the order of courses to finish all courses given the prerequisites. |
| [310. Minimum Height Trees](./Graphs/310.%20Minimum%20Height%20Trees.md) | Task is to find the minimum height trees in a graph. |
| [1462. Course Schedule IV](./Graphs/1462.%20Course%20Schedule%20IV.md) | We have to determine if one course is a prerequisite of another course given the prerequisites. |

---

## [Shortest Path Algorithms](Graphs/)

`Shortest Path Algorithms` are algorithms used to find the shortest path between two vertices in a graph. Common algorithms include Dijkstra's algorithm, Bellman-Ford algorithm, and Floyd-Warshall algorithm.

| Problem | Explanation |
|---------|-------------|
| [743. Network Delay Time](./Graphs/743.%20Network%20Delay%20Time.md) | We have to find the time it takes for all nodes to receive a signal sent from a starting node in a directed graph. |
| [778. Swim in Rising Water](./Graphs/778.%20Swim%20in%20Rising%20Water.md) | We have to find the minimum time required to swim from the top-left corner to the bottom-right corner of a grid, where the water level rises over time. |
| [787. Cheapest Flights Within K Stops](./Graphs/787.%20Cheapest%20Flights%20Within%20K%20Stops.md) | We have to find the cheapest price for a flight from a source city to a destination city with at most K stops. |
| [1631. Path With Minimum Effort](./Graphs/1631.%20Path%20With%20Minimum%20Effort.md) | We have to find the path with the minimum effort in a grid of heights. |


---

## [1-D Dynamic Programming](Dynamic%20Programming/)

`Dynamic Programming` is a method for solving complex problems by breaking them down into simpler subproblems, storing the results of those subproblems to avoid redundant work.

| Problem | Explanation |
|---------|-------------|
| [213. House Robber II](./Dynamic%20Programming/213.%20House%20Robber%20II.md) | We have to find the maximum amount of money that can be robbed from a circular street of houses.  |
| [300. Longest Increasing Subsequence](./Dynamic%20Programming/300.%20Longest%20Increasing%20Subsequence.md) | We have to find the length of the longest increasing subsequence in an array. |
| [416. Partition Equal Subset Sum](./Dynamic%20Programming/416.%20Partition%20Equal%20Subset%20Sum.md) | We have to determine if we can partition an array into two subsets with equal sums.  |
| [494. Target Sum](Dynamic%20Programming/494.%20Target%20Sum.md) | We have to find the number of ways to assign symbols to make a target sum. |

---


## [2-D Dynamic Programming](Dynamic%20Programming/)

`Dynamic Programming` is a method for solving complex problems by breaking them down into simpler subproblems, storing the results of those subproblems to avoid redundant work.

| Problem | Explanation |
|---------|-------------|
| [5. Longest Palindromic Substring](./Dynamic%20Programming/5.%20Longest%20Palindromic%20Substring.md) | We have to find the longest palindromic substring in a given string. |
| [63. Unique Paths II](./Dynamic%20Programming/63.%20Unique%20Paths%20II.md) | We have to find the number of unique paths from the top-left corner to the bottom-right corner of a grid, considering obstacles. |
| [64. Minimum Path Sum](./Dynamic%20Programming/64.%20Minimum%20Path%20Sum.md) | We have to find the minimum path sum from the top-left corner to the bottom-right corner of a grid. |
| [72. Edit Distance](./Dynamic%20Programming/72.%20Edit%20Distance.md) | We have to find the minimum number of operations required to convert one string into another. |
| [97. Interleaving String](./Dynamic%20Programming/97.%20Interleaving%20String.md) | We have to determine if a string is an interleaving of two other strings. |
| [115. Distinct Subsequences](./Dynamic%20Programming/115.%20Distinct%20Subsequences.md) | We have to find the number of distinct subsequences of a string that equals another string. |
| [309. Best Time to Buy and Sell Stock with Cooldown](./Dynamic%20Programming/309.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock%20with%20Cooldown.md) | We have to find the maximum profit from stock trading with a cooldown period after selling. |
| [518. Coin Change 2](./Dynamic%20Programming/518.%20Coin%20Change%202.md) | We have to find the number of combinations that make up a given amount using a set of coins. |
| [1049. Last Stone Weight II](./Dynamic%20Programming/1049.%20Last%20Stone%20Weight%20II.md) | We have to find the smallest possible weight of the last remaining stone after smashing stones together. |
| [1143. Longest Common Subsequence](Dynamic%20Programming/1143.%20Longest%20Common%20Subsequence.md) | We have to find the length of the longest common subsequence between two strings. | 

---