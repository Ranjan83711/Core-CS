# Bihar STET Paper 2 (Computer Science): Data Structures & Algorithms PYQ Bank

**Papers covered:** the same 8 papers as the earlier chapters.

| Year | Paper | DSA questions found |
|---|---|---|
| 2019 | Second sitting | 4 |
| 2020 | Re-exam | 0 |
| 2023 | 12 Sep, Shift 1 | 13 |
| 2024 | 11 Jun (memory-based) | 7 |
| 2025 | 3 Nov Shift 1 | 9 |
| 2025 | 3 Nov Shift 2 | 8 |
| 2025 | 4 Nov Shift 2 | 9 |
| 2025 | 7 Nov Shift 1 | 13 |
| **Total** | | **≈63** |

> **This is the largest chapter in the exam.** Since 2023, each shift has had **8–13 DSA questions**.
> The style is **theory and one-step reasoning**: complexities, traversal facts, which paradigm fits which problem, and formulas (row-major address, spanning-tree edges, Tower of Hanoi moves).
> Many questions **repeat across years**: row-major formula, linked-list O(1) insert, BST delete, threaded tree, separate chaining, Tower of Hanoi, spanning tree n−1, merge sort, o(f(n)), divide & conquer.

**Notes on answers**
- The questions are paraphrased.
- The 2023 answers come from the official key.
- For 2025, the answers were worked out from the options.
- Ambiguous questions are flagged.

---

## 1. Topic frequency

| Rank | Topic | Times asked | Years |
|---|---|---|---|
| 1 | **Algorithm design paradigms** (divide & conquer ×3, recurrences ×2, max-min ×2, DP ×2, greedy/Huffman, backtracking ×2, tradeoff) | 14 | 2023, 2025 ×4 |
| 2 | **Trees** (threaded ×3, BST delete ×2, AVL, B-tree, tree = non-linear) | 9 | 2019, 2023, 2024, 2025 ×4 |
| 3 | **Graphs** (BFS, DFS stack, DFS memory, connected components, directed edge, spanning tree ×2, Floyd-Warshall, transitive property, Prim's cut) | 10 | 2023, 2024, 2025 ×4 |
| 4 | **Complexity & asymptotics** (analysis, conditional asymptotic ×2, o-notation ×2, NP ×2) | 8 | 2023, 2025 ×3 |
| 5 | **Arrays & linked lists** (row-major ×2, 2-D array, linked list O(1) ×2, linear traversal, array-based stack, data organisation, arrays implement stacks and queues) | 10 | 2019, 2024, 2025 ×4 |
| 6 | **Stack & recursion** (LIFO, postfix evaluation, recursion stack, removing recursion, factorial base case, Tower of Hanoi ×2) | 7 | 2023, 2025 ×3 |
| 7 | **Sorting** (merge sort ×2, O(n²) sort, bubble, counting sort) | 5 | 2024, 2025 ×3 |
| 8 | **Hashing** (separate chaining ×2, linear probing, hash-table tradeoff) | 4 | 2023, 2025 |

---

## 2. Questions by topic (with answers)

### A. Complexity, asymptotic notation & NP
| # | Asked (paraphrased) | Answer | Year |
|---|---|---|---|
| 1 | Algorithm analysis is mainly about | **Measuring the time and space efficiency** | 2025 (7 Nov) |
| 2 | Optimising resources by sacrificing one aspect for another | **Tradeoff** | 2023 |
| 3 | Data structure that trades extra memory for speed | **Hash table** | 2023 |
| 4 | Conditional asymptotic notation is useful when | **Behaviour varies with certain input characteristics** | 2023 |
| 5 | "Θ(f(n)) if g(n)": bounded above and below by f(n) when | **g(n) is true** | 2025 (4 Nov) |
| 6 | "o(f(n)) if g(n)" with the condition removed becomes | **o(f(n))** | 2023, 2025 (7 Nov) |
| 7 | A problem is in NP if | **Its solution can be verified in polynomial time** | 2025 (3 Nov S1) |
| 8 | Who introduced NP-completeness? | **Stephen Cook** (1971) | 2025 (7 Nov) |

### B. Arrays & linked lists
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Row-major index of element (i, j), base B, n columns | **B + (i × n + j)** | 2024, 2025 (3 Nov S1) |
| 2 | Array type suited to pixel values | **2-D array** | 2025 (3 Nov S2) |
| 3 | O(1) operation in a pointer-based linked list | **Inserting at the beginning** | 2024, 2025 (7 Nov) |
| 4 | Visiting each node of a linked list once | **Linear traversal** | 2025 (4 Nov) |
| 5 | Stack using fixed memory for a fixed number of elements | **Array (static) implementation** | 2025 (3 Nov S1) |
| 6 | "Data structure" refers to ___ and the relationships between data | **Organisation of data** | 2019 |
| 7 | Stacks, queues and linked lists can be implemented using | **Arrays** | 2019 |
| 8 | In data structures, data may be of ___ types | **2** (primitive/non-primitive). The candidate's marked answer was 4. | 2019 |

### C. Stack, recursion & Tower of Hanoi
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Stack principle | **LIFO** | 2025 (3 Nov S2) |
| 2 | Evaluate the postfix `3 5 * 6 + 2 3 * -` | **15** (15 + 6 = 21, 21 − 6 = 15) | 2025 (3 Nov S2) |
| 3 | Role of the stack in recursion | **Stores variables and function calls for backtracking/returning** | 2025 (7 Nov) |
| 4 | Removing recursion means replacing recursive calls with | **Loops** | 2023 |
| 5 | Base case of a recursive factorial | **n == 0** | 2025 (3 Nov S1) |
| 6 | Tower of Hanoi moves for n disks | **2ⁿ − 1** | 2023 |
| 7 | Tower of Hanoi moves for 3 disks | **7** | 2025 (7 Nov) |

### D. Trees
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Which is a non-linear data structure? | **Tree** | 2019 |
| 2 | A threaded binary tree is one in which | **Each node has threads to its (inorder) predecessor/successor** | 2023, 2025 (3 Nov S2) |
| 3 | Space needed for threads, compared with regular pointers | **Less**. Threads reuse the NULL link fields, adding only a flag bit. *Debatable; this is the usual answer.* | 2025 (4 Nov) |
| 4 | Deleting a BST node that has one child | **Replace the node with its only child**. The paper's options said "left child" / "right child", so pick whichever child the question means. | 2024, 2025 (7 Nov) |
| 5 | AVL balance factor | **Height(left subtree) − height(right subtree)** | 2025 (7 Nov) |
| 6 | B-tree of order m: maximum children per node | **m** | 2025 (4 Nov) |

### E. Graphs
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | BFS explores level by level, starting from | **The shallowest level (source)** | 2025 (3 Nov S2) |
| 2 | Traversal implemented with a stack | **DFS** | 2023 |
| 3 | Search that needs the least memory (Optimal, Linear, DFS, BFS) | **DFS** | 2025 (3 Nov S1) |
| 4 | Connected components are found with | **Both DFS and BFS** | 2025 (4 Nov) |
| 5 | Directed edge from A to B is written | **(A, B)** | 2023 |
| 6 | Minimum edges in a spanning tree of n vertices | **n − 1** | 2024, 2025 (7 Nov) |
| 7 | Time complexity of Floyd-Warshall | **O(n³)** | 2025 (4 Nov) |
| 8 | All-pairs shortest path: the "transitive property" means | **One vertex can be reached from another (through intermediate vertices)** | 2024 |
| 9 | Cut property (Prim's algorithm) | **The minimum-weight edge crossing a cut belongs to the MST** | 2025 (7 Nov) |

### F. Sorting
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Time complexity of merge sort | **O(n log n)** | 2024, 2025 (4 Nov) |
| 2 | Sort whose basic form is O(n²) in the worst case (Quick, Merge, Insertion, Counting) | **Insertion sort** (intended). *Quick sort is also O(n²) in the worst case, so the question is ambiguous.* | 2025 (3 Nov S2) |
| 3 | Sort that compares neighbouring elements and swaps them | **Bubble sort** | 2025 (7 Nov) |
| 4 | Counting sort is efficient when the range of values is | **Small** | 2024 |

### G. Hashing
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Separate chaining stores collided elements in | **Linked lists** | 2023, 2025 (4 Nov) |
| 2 | Putting a collided element in the next empty slot is | **Linear probing** | 2023 |

### H. Algorithm design paradigms
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Divide and conquer solves problems by | **Recursively solving subproblems** | 2023, 2025 (7 Nov) |
| 2 | T(n) = T(n/2) + 1 is the recurrence of | **Divide and conquer** (binary search) | 2023 |
| 3 | T(n) = T(n/2) + T(n/3) + n is the recurrence of | **Divide and conquer** | 2025 (4 Nov) |
| 4 | Time complexity of finding max-min by D&C | **O(n)** (3n/2 − 2 comparisons) | 2025 (3 Nov S1) |
| 5 | How the max-min halves are combined | **Compare the two maxima and the two minima** | 2025 (3 Nov S1) |
| 6 | DP property used for Optimal BST | **Optimal substructure** | 2025 (3 Nov S1) |
| 7 | Memoization in a multistage graph is used for | **Storing solutions to overlapping subproblems** | 2025 (3 Nov S1) |
| 8 | Huffman coding gives shorter codes to | **Characters with higher frequency** | 2025 (7 Nov) |
| 9 | 8-Queens backtracking: once a feasible solution is found, the algorithm | **Stops and returns it** (when one solution is needed) | 2025 (3 Nov S2) |
| 10 | Goal of backtracking for the Hamiltonian cycle | **A cycle visiting every vertex exactly once** | 2025 (3 Nov S2) |

---

## 3. Must-revise checklist

1. **Complexity:** O / Ω / Θ / o / ω meanings, growth order 1 < log n < n < n log n < n² < n³ < 2ⁿ < n!, loop analysis, best/average/worst case, amortized cost, time–space tradeoff.
2. **Recurrences:** binary search T(n/2)+1 → log n, merge sort 2T(n/2)+n → n log n, T(n−1)+1 → n, Master theorem basics.
3. **Arrays:** row-major B + w(i·n + j), column-major B + w(j·m + i), sparse matrix.
4. **Linked lists:** singly/doubly/circular; insert at head O(1), access O(n); NULL links in a binary tree = n + 1.
5. **Stack/queue:** LIFO/FIFO, infix → postfix/prefix, postfix evaluation, circular queue full condition (rear+1)%N == front, deque, priority queue (heap), a queue built from 2 stacks.
6. **Recursion:** base case, recursion stack, tail recursion, Tower of Hanoi 2ⁿ − 1, removing recursion (loops + explicit stack).
7. **Trees:** binary tree properties (max nodes 2^(h+1) − 1, edges n − 1), traversals (pre/in/post), BST insert/delete (0, 1 or 2 children → inorder successor), threaded tree, AVL (BF ∈ {−1, 0, 1}, rotations), B-tree (order m: m children, m − 1 keys), heaps.
8. **Graphs:** representation (matrix O(V²) / list O(V+E)), BFS (queue) / DFS (stack), spanning tree n − 1 edges, Prim/Kruskal (cut property, union-find), Dijkstra (greedy, non-negative weights), Bellman-Ford (negative weights), Floyd-Warshall (DP, O(n³)), topological sort (DAG).
9. **Sorting:** bubble/selection/insertion O(n²), merge O(n log n) (stable, extra space), quick (average n log n, worst n²), heap O(n log n), counting O(n + k), radix; stability and in-place.
10. **Searching & hashing:** linear O(n), binary O(log n) (sorted data), chaining, linear/quadratic probing, double hashing, load factor, clustering.
11. **Paradigms:** D&C (merge, quick, binary search, max-min, Strassen), greedy (Huffman, Prim, Kruskal, Dijkstra, fractional knapsack, activity selection), DP (0/1 knapsack, LCS, OBST, multistage graph, Floyd-Warshall), backtracking (N-Queens, Hamiltonian cycle, sum of subsets, graph colouring), branch & bound.
12. **P vs NP:** P ⊆ NP, NP = verifiable in polynomial time, NP-complete (Cook 1971, SAT), NP-hard.

Practice set: `05b_Data_Structures_Algorithms_Practice_MCQs.md`
