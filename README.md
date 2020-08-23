# Interview-Preparation
Collections of Resources I collected during my Internship Interview Prepration.
I had spent significant amount of time for choosing resources while styding and have mentioned them with topics for easy reading.
Will add  Questions soon!.
## Table of Contents
- [Resources](#resources)
- [Data Structures](#data-structures)
  - [Linked List](#linked-list)
  - [Stack](#stack)
  - [Queue](#queue)
  - [Tree](#tree)
  - [Binary Tree](#binary-tree)
  - [Binary Search Tree](#binary-search-tree)
  - [Heap](#heap)
  - [Hash Map](#hashing)
  - [Graph](#graph)
- [Algorithms](#algorithms)
- [How to Approach](#how-to-approach)

# Resources
Free Resources to study/ revise each of the topics which I felt were concise and good enough.

Topic | Resource 
--- | --- 
**Graph** (Basics/Theory)| [Basics and Representing Graph](https://medium.com/basecs/deep-dive-through-a-graph-dfs-traversal-8177df5d0f13) , [Depth First Search](https://medium.com/basecs/deep-dive-through-a-graph-dfs-traversal-8177df5d0f13) and [Breath First Search](https://medium.com/basecs/going-broad-in-a-graph-bfs-traversal-959bd1a09255).
**Graph** (Programming)| [Topcoder Tutorial](https://www.topcoder.com/community/competitive-programming/tutorials/introduction-to-graphs-and-their-data-structures-section-1/)
**Graph Traversals** (Programming and Applications)| [DFS](https://cp-algorithms.com/graph/depth-first-search.html) and [BFS](https://cp-algorithms.com/graph/breadth-first-search.html)
**Dynamic Programming**    | [Dynamic Programming-Topcoder](https://www.topcoder.com/community/competitive-programming/tutorials/dynamic-programming-from-novice-to-advanced/)
**Dynamic Programming** (How to Approach)| [7 Steps to Solve DP Problems](https://www.freecodecamp.org/news/follow-these-steps-to-solve-any-dynamic-programming-interview-problem-cc98e508cd0e/)
 


# Data Structures
## Linked List
 * A *Linked List* is a linear collection of data elements, called nodes, each
   pointing to the next node by means of a pointer. It is a data structure
   consisting of a group of nodes which together represent a sequence.
 * **Singly-linked list**: linked list in which each node points to the next node and the last node points to null
 * **Doubly-linked list**: linked list in which each node has two pointers, p and n, such that p points to the previous node and n points to the next node; the last node's n pointer points to null
 * **Circular-linked list**: linked list in which each node points to the next node and the last node points back to the first node
 * Time Complexity:
   * Access: `O(n)`
   * Search: `O(n)`
   * Insert: `O(1)`
   * Remove: `O(1)`
 
 ### Questions:
 > Try to know optimal/various solutions(even in no. of passes/traversals and space) because other than that their are not much in Linked Lists. Also for Linked List **search various solutions** even if you got optimal, you will learn many tricks on how to traverse etc in each case.
   1. [Reverse the Linked List](https://leetcode.com/problems/reverse-linked-list/) (Recursive and Iterative)
   1. [Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/)
   1. [Remove Nth Node From End](https://leetcode.com/problems/remove-nth-node-from-end-of-list/solution/) (try it in one pass).
   1. [Reorder List](https://leetcode.com/problems/reorder-list/).
   1. [Separate Even/Odd nodes in LL](https://leetcode.com/problems/odd-even-linked-list/)
   1. [Clone LinkedList with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/)
   1. [LinkList Cycle Detection](https://leetcode.com/problems/linked-list-cycle/)
   1. [LinkList Cycle Removal](https://leetcode.com/problems/linked-list-cycle-ii/) and also [the gfg one](https://practice.geeksforgeeks.org/problems/remove-loop-in-linked-list/1)
   1. [Pairwise Swap linkedList Nodes](https://leetcode.com/problems/swap-nodes-in-pairs/)
   1. [Reverse LL in Group of K](https://leetcode.com/problems/reverse-nodes-in-k-group/)
   1. [LRU cache](https://leetcode.com/problems/lru-cache/) (optional)
   
**Special**(Applications in non-trivial form)
   1. [Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) 
   
### Corner Cases :
`Even Nodes/Odd Nodes` (also `Single or Two Nodes`) and `list has cycle` 

## Stack
 * A *Stack* is a collection of elements, with two principle operations: *push*, which adds to the collection, and
   *pop*, which removes the most recently added element
 * **Last in, first out data structure (LIFO)**: the most recently added object is the first to be removed
 * Time Complexity:
   * Access: `O(n)`
   * Search: `O(n)`
   * Insert: `O(1)`
   * Remove: `O(1)`

 ### Questions:
 > Questions directly on stack are very limited, the real applications of stack are in Graph/Tree Traversals. Also understand both List and Array implementation of stack.
   1. [Min/Max Stack](https://leetcode.com/problems/min-stack/)  (Remembe O(1) )
   1. [Implement Queue using Stack](https://leetcode.com/problems/implement-queue-using-stacks/) 
   1. [Backspace String Compare](https://leetcode.com/problems/backspace-string-compare/)
   1. [Valid Stack Sequence](https://leetcode.com/problems/validate-stack-sequences/) 
   1. [Valid Parenthesis ](https://leetcode.com/problems/valid-parentheses/) 
   1. [Minimum Deletion to make valid Paranthesis](https://leetcode.com/problems/minimum-remove-to-make-valid-parentheses).
   1. [Minimum add to make parenthesis valid](https://leetcode.com/problems/minimum-add-to-make-parentheses-valid/)
      1. [Minimum Insertion to make valid Paranthesis](https://leetcode.com/problems/minimum-insertions-to-balance-a-parentheses-string/)
   1. [Score of Parenthesis](https://leetcode.com/problems/score-of-parentheses/)
   1. [Decode String](https://leetcode.com/problems/decode-string/) (Something New!)
   1. [Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/) (optional)
   1. [Trapping Rainwater](https://leetcode.com/problems/trapping-rain-water/) (optional)
   

### Queue
 * A *Queue* is a collection of elements, supporting two principle operations: *enqueue*, which inserts an element
   into the queue, and *dequeue*, which removes an element from the queue
 * **First in, first out data structure (FIFO)**: the oldest added object is the first to be removed
 * Time Complexity:
   * Access: `O(n)`
   * Search: `O(n)`
   * Insert: `O(1)`
   * Remove: `O(1)`

### Tree
 * A *Tree* is an undirected, connected, acyclic graph

### Binary Tree
 * A *Binary Tree* is a tree data structure in which each node has at most two children, which are referred to as
   the *left child* and *right child*
 * **Full Tree**: a tree in which every node has either 0 or 2 children
 * **Perfect Binary Tree**: a binary tree in which all interior nodes have two children and all leave have the same depth
 * **Complete Tree**: a binary tree in which every level *except possibly the last* is full and all nodes in the last
   level are as far left as possible

### Binary Search Tree
 * A binary search tree, sometimes called BST, is a type of binary tree which maintains the property that the value in each
   node must be greater than or equal to any value stored in the left sub-tree, and less than or equal to any value stored
   in the right sub-tree
 * Time Complexity:
   * Access: `O(log(n))`
   * Search: `O(log(n))`
   * Insert: `O(log(n))`
   * Remove: `O(log(n))`

### Heap
* A *Heap* is a specialized tree based structure data structure that satisfies the *heap* property: if A is a parent node of
B, then the key (the value) of node A is ordered with respect to the key of node B with the same ordering applying across the entire heap.
A heap can be classified further as either a "max heap" or a "min heap". In a max heap, the keys of parent nodes are always greater
than or equal to those of the children and the highest key is in the root node. In a min heap, the keys of parent nodes are less than
or equal to those of the children and the lowest key is in the root node
* Time Complexity:
  * Access Max / Min: `O(1)`
  * Insert: `O(log(n))`
  * Remove Max / Min: `O(log(n))`

### Hashing
* *Hashing* is used to map data of an arbitrary size to data of a fixed size. The values returned by a hash
  function are called hash values, hash codes, or simply hashes. If two keys map to the same value, a collision occurs
* **Hash Map**: a *hash map* is a structure that can map keys to values. A hash map uses a hash function to compute
  an index into an array of buckets or slots, from which the desired value can be found.
* Collision Resolution
 * **Separate Chaining**: in *separate chaining*, each bucket is independent, and contains a list of entries for each index. The
 time for hash map operations is the time to find the bucket (constant time), plus the time to iterate through the list
 * **Open Addressing**: in *open addressing*, when a new entry is inserted, the buckets are examined, starting with the
 hashed-to-slot and proceeding in some sequence, until an unoccupied slot is found. The name open addressing refers to
 the fact that the location of an item is not always determined by its hash value



### Graph
* A *Graph* is an ordered pair of G = (V, E) comprising a set V of vertices or nodes together with a set E of edges or arcs,
  which are 2-element subsets of V (i.e. an edge is associated with two vertices, and that association takes the form of the
  unordered pair comprising those two vertices)
 * **Undirected Graph**: a graph in which the adjacency relation is symmetric. So if there exists an edge from node u to node
 v (u -> v), then it is also the case that there exists an edge from node v to node u (v -> u)
 * **Directed Graph**: a graph in which the adjacency relation is not symmetric. So if there exists an edge from node u to node v
 (u -> v), this does *not* imply that there exists an edge from node v to node u (v -> u)


## Algorithms

### Sorting

#### Quicksort
* Stable: `No`
* Time Complexity:
  * Best Case: `O(nlog(n))`
  * Worst Case: `O(n^2)`
  * Average Case: `O(nlog(n))`


#### Mergesort
* *Mergesort* is also a divide and conquer algorithm. It continuously divides an array into two halves, recurses on both the
  left subarray and right subarray and then merges the two sorted halves
* Stable: `Yes`
* Time Complexity:
  * Best Case: `O(nlog(n))`
  * Worst Case: `O(nlog(n))`
  * Average Case: `O(nlog(n))`

### Graph Algorithms

#### Depth First Search
* *Depth First Search* is a graph traversal algorithm which explores as far as possible along each branch before backtracking
* Time Complexity: `O(|V| + |E|)`


#### Breadth First Search
* *Breadth First Search* is a graph traversal algorithm which explores the neighbor nodes first, before moving to the next
  level neighbors
* Time Complexity: `O(|V| + |E|)`


#### Topological Sort
* *Topological Sort* is the linear ordering of a directed graph's nodes such that for every edge from node u to node v, u
  comes before v in the ordering
* Time Complexity: `O(|V| + |E|)`

#### Dijkstra's Algorithm
* *Dijkstra's Algorithm* is an algorithm for finding the shortest path between nodes in a graph
* Time Complexity: `O(|V|^2)`


#### Bellman-Ford Algorithm
* *Bellman-Ford Algorithm* is an algorithm that computes the shortest paths from a single source node to all other nodes in a weighted graph
* Although it is slower than Dijkstra's, it is more versatile, as it is capable of handling graphs in which some of the edge weights are
  negative numbers
* Time Complexity:
  * Best Case: `O(|E|)`
  * Worst Case: `O(|V||E|)`


#### Floyd-Warshall Algorithm
* *Floyd-Warshall Algorithm* is an algorithm for finding the shortest paths in a weighted graph with positive or negative edge weights, but
  no negative cycles
* A single execution of the algorithm will find the lengths (summed weights) of the shortest paths between *all* pairs of nodes
* Time Complexity:
  * Best Case: `O(|V|^3)`
  * Worst Case: `O(|V|^3)`
  * Average Case: `O(|V|^3)`

#### Prim's Algorithm
* *Prim's Algorithm* is a greedy algorithm that finds a minimum spanning tree for a weighted undirected graph. In other words, Prim's find a
  subset of edges that forms a tree that includes every node in the graph
* Time Complexity: `O(|V|^2)`


#### Kruskal's Algorithm
* *Kruskal's Algorithm* is also a greedy algorithm that finds a minimum spanning tree in a graph. However, in Kruskal's, the graph does not
  have to be connected
* Time Complexity: `O(|E|log|V|)`



## How to Approach
 (Go to Approaches)
```
If input array is sorted then
- Binary search
- Two pointers
- Upper_bound lower_bound 

If given a Tree/Graph then
- DFS
- BFS

If asked/generate all permutations/subsets then 
- Backtracking

If asked to generate any/all solutions 
- Backtracking

If very complex counting kind problem ( N < 50 )
- Backtracking

If feel like multiple nested for loops whose numbers depend upon conditional input
- backtracking

If given a linked list then
- Two pointers

If linklist backtraversing pointer needed then
- Recursion (Head Recursion)

If recursion is banned/TLE then
- Stack

If asked for maximum/minumum subarray/subset/options then
- Dynamic programming

If asked for counting then
- Dynamic programming (Optimising Backtracking)

If most subproblems are needed/Tighter Constraints in DP then
- Tabulation in DP 

If BruteForce Recursion fails then :
- Recursion + store solved sub-problems (Memoization).

If asked for top/least K items then
- Heap

If asked for common strings then
- Map
- Trie

If O(1) operations needed then 
- map or unordered_map 

If O(logn) time operations needed then 
- set , multi_set

If find first/Number of elements greater than/equal to then 
- lower_bound, upper_bound (in sorted )
```

