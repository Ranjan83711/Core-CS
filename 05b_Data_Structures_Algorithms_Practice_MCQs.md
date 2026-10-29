# Data Structures & Algorithms: Practice MCQs (200 questions)

**Bihar STET Paper 2 (Computer Science)**

There are 10 topics with 20 questions each. The answer is shown right under each question, so you can revise in one read. Target: 17/20 or better.

DSA is the biggest chapter in recent papers (8–13 questions per shift), so give it the most practice time.

---

## A. Complexity & Asymptotic Notation

**1.** Big-O notation gives the:
(A) upper bound  (B) lower bound  (C) tight bound  (D) none of these

✅ **Ans: (A) upper bound**

**2.** Big-Omega (Ω) notation gives the:
(A) upper bound  (B) lower bound  (C) tight bound  (D) none of these

✅ **Ans: (B) lower bound**

**3.** Big-Theta (Θ) notation gives the:
(A) upper bound only  (B) lower bound only  (C) tight bound (both upper and lower)  (D) none of these

✅ **Ans: (C) tight bound (both upper and lower)**

**4.** What is the worst-case time complexity of linear search?
(A) O(1)  (B) O(log n)  (C) O(n)  (D) O(n²)

✅ **Ans: (C) O(n)**

**5.** What is the worst-case time complexity of binary search?
(A) O(n)  (B) O(log n)  (C) O(1)  (D) O(n log n)

✅ **Ans: (B) O(log n)**

**6.** What is the time to access an array element by its index?
(A) O(1)  (B) O(n)  (C) O(log n)  (D) O(n²)

✅ **Ans: (A) O(1)**

**7.** What is the complexity of two nested loops that each run n times?
(A) O(n)  (B) O(n²)  (C) O(log n)  (D) O(n³)

✅ **Ans: (B) O(n²)**

**8.** What is the complexity of `for (i = 1; i < n; i *= 2)`?
(A) O(n)  (B) O(n log n)  (C) O(1)  (D) O(log n)

✅ **Ans: (D) O(log n)** — i doubles each time

**9.** Which list is in increasing order of growth?
(A) 1 < log n < n < n log n < n² < 2ⁿ  (B) log n < 1 < n < n²  (C) n < log n < n²  (D) 2ⁿ < n² < n

✅ **Ans: (A) 1 < log n < n < n log n < n² < 2ⁿ**

**10.** Which data structure is a classic example of a time–space tradeoff?
(A) Linear search  (B) Bubble sort  (C) Hash table (extra memory for faster lookup)  (D) Stack

✅ **Ans: (C) Hash table (extra memory for faster lookup)** — (PYQ 2023)

**11.** Algorithm analysis is mainly concerned with:
(A) creating new algorithms  (B) measuring time and space efficiency  (C) writing code  (D) testing

✅ **Ans: (B) measuring time and space efficiency** — (PYQ 2025)

**12.** f(n) = o(g(n)) (little-o) means f grows:
(A) strictly slower than g (an upper bound that is not tight)  (B) at the same rate  (C) faster  (D) equal to g

✅ **Ans: (A) strictly slower than g (an upper bound that is not tight)**

**13.** What is the best-case complexity of insertion sort?
(A) O(n)  (B) O(n²)  (C) O(log n)  (D) O(1)

✅ **Ans: (A) O(n)** — When the array is already sorted

**14.** Asymptotic analysis looks at:
(A) small inputs  (B) hardware speed  (C) the compiler used  (D) behaviour as the input size grows large

✅ **Ans: (D) behaviour as the input size grows large**

**15.** Conditional asymptotic notation is useful when:
(A) the algorithm's behaviour changes with certain characteristics of the input  (B) the input size is fixed  (C) the time is constant  (D) the input is random

✅ **Ans: (A) the algorithm's behaviour changes with certain characteristics of the input** — (PYQ 2023)

**16.** What does T(n) = 2T(n/2) + n solve to?
(A) O(n)  (B) O(n log n)  (C) O(n²)  (D) O(log n)

✅ **Ans: (B) O(n log n)** — Merge sort

**17.** What does T(n) = T(n/2) + 1 solve to?
(A) O(n)  (B) O(n log n)  (C) O(log n)  (D) O(1)

✅ **Ans: (C) O(log n)** — Binary search

**18.** What does T(n) = T(n−1) + 1 solve to?
(A) O(log n)  (B) O(n²)  (C) O(1)  (D) O(n)

✅ **Ans: (D) O(n)**

**19.** Amortized analysis gives the:
(A) average cost per operation over a sequence of operations  (B) worst cost of a single operation  (C) best case  (D) none of these

✅ **Ans: (A) average cost per operation over a sequence of operations**

**20.** Which of these grows fastest?
(A) n²  (B) 2ⁿ  (C) n log n  (D) n³

✅ **Ans: (B) 2ⁿ**

---

## B. Arrays & Linked Lists

**1.** In row-major order, what is the index of element (i, j) in an array with n columns and base address B (element size 1)?
(A) B + (i·n + j)  (B) B + (j·n + i)  (C) B + (i + j)  (D) B + (i·m + j)

✅ **Ans: (A) B + (i·n + j)** — (PYQ 2024, 2025)

**2.** In column-major order, with m rows, the index of (i, j) is:
(A) B + (i·n + j)  (B) B + (i + j)  (C) B + (j·m + i)  (D) B + (i·m + j)

✅ **Ans: (C) B + (j·m + i)**

**3.** A[10][20] is stored in row-major order with base address 1000 and element size 2 (0-based indexing). What is the address of A[2][3]?
(A) 1086  (B) 1046  (C) 1043  (D) 1092

✅ **Ans: (A) 1086** — 1000 + 2 × (2 × 20 + 3) = 1000 + 86

**4.** Which array type suits storing the pixel values of a grayscale image?
(A) 1-D  (B) 2-D  (C) 3-D  (D) 4-D

✅ **Ans: (B) 2-D** — Rows × columns (PYQ 2025)

**5.** Which of these is a linear data structure?
(A) Tree  (B) Graph  (C) Linked list  (D) Heap

✅ **Ans: (C) Linked list**

**6.** Which of these is a non-linear data structure?
(A) Stack  (B) Queue  (C) Array  (D) Tree

✅ **Ans: (D) Tree** — (PYQ 2019)

**7.** What is the time to insert at the beginning of a singly linked list?
(A) O(1)  (B) O(n)  (C) O(log n)  (D) O(n²)

✅ **Ans: (A) O(1)** — (PYQ 2024, 2025)

**8.** What is the time to insert at the end of a singly linked list that has no tail pointer?
(A) O(1)  (B) O(n)  (C) O(log n)  (D) O(n²)

✅ **Ans: (B) O(n)** — You have to walk to the end

**9.** A singly linked list node contains:
(A) only data  (B) only an address  (C) data plus a link to the next node  (D) an index

✅ **Ans: (C) data plus a link to the next node**

**10.** What is the time to access the k-th element of a linked list?
(A) O(1)  (B) O(k), i.e. O(n) in the worst case  (C) O(log n)  (D) O(n²)

✅ **Ans: (B) O(k), i.e. O(n) in the worst case**

**11.** A doubly linked list node has:
(A) two pointers (previous and next)  (B) one pointer  (C) three pointers  (D) no pointers

✅ **Ans: (A) two pointers (previous and next)**

**12.** In a circular linked list, the last node points to:
(A) NULL  (B) itself  (C) the middle node  (D) the first node

✅ **Ans: (D) the first node**

**13.** What is the main advantage of a linked list over an array?
(A) dynamic size and easy insertion/deletion  (B) random access  (C) less memory per element  (D) better cache use

✅ **Ans: (A) dynamic size and easy insertion/deletion**

**14.** What is a disadvantage of a linked list?
(A) fixed size  (B) no random access, plus extra memory for pointers  (C) slow insertion at the head  (D) none of these

✅ **Ans: (B) no random access, plus extra memory for pointers**

**15.** Visiting every node of a linked list exactly once is called:
(A) inorder traversal  (B) preorder traversal  (C) linear traversal  (D) postorder traversal

✅ **Ans: (C) linear traversal** — (PYQ 2025)

**16.** Which stack implementation uses a fixed amount of memory for a fixed number of elements?
(A) Array (static) implementation  (B) Linked implementation  (C) Dynamic implementation  (D) Tree implementation

✅ **Ans: (A) Array (static) implementation** — (PYQ 2025)

**17.** A sparse matrix is one in which:
(A) most elements are zero  (B) all elements are non-zero  (C) it is square  (D) it is diagonal

✅ **Ans: (A) most elements are zero**

**18.** Array indexing in C and Python starts at:
(A) 0  (B) 1  (C) −1  (D) any number

✅ **Ans: (A) 0**

**19.** How many elements are in the array A[2..8]?
(A) 6  (B) 7  (C) 8  (D) 9

✅ **Ans: (B) 7** — 8 − 2 + 1

**20.** Data structures are broadly classified as:
(A) arrays only  (B) trees only  (C) files only  (D) primitive and non-primitive (linear and non-linear)

✅ **Ans: (D) primitive and non-primitive (linear and non-linear)**

---

## C. Stacks, Queues & Recursion

**1.** A stack works on the principle of:
(A) FIFO  (B) LIFO  (C) Middle Element First  (D) LILO

✅ **Ans: (B) LIFO** — (PYQ 2025)

**2.** Evaluate the postfix expression `3 5 * 6 + 2 3 * -`.
(A) 39  (B) −9  (C) 15  (D) −17

✅ **Ans: (C) 15** — 15 + 6 = 21, 2 × 3 = 6, 21 − 6 = 15 (PYQ 2025)

**3.** What is the postfix form of `(A + B) * C`?
(A) `AB+C*`  (B) `ABC*+`  (C) `+AB*C`  (D) `A+BC*`

✅ **Ans: (A) `AB+C*`**

**4.** What is the prefix form of `A + B * C`?
(A) `ABC*+`  (B) `+A*BC`  (C) `*+ABC`  (D) `AB+C*`

✅ **Ans: (B) `+A*BC`**

**5.** Postfix expressions are evaluated using a:
(A) stack  (B) queue  (C) tree  (D) graph

✅ **Ans: (A) stack**

**6.** In recursion, the stack is used to store:
(A) loop counters  (B) variables only  (C) function calls only  (D) the local variables and return addresses of each call

✅ **Ans: (D) the local variables and return addresses of each call** — (PYQ 2025)

**7.** To remove recursion, recursive calls are replaced with:
(A) loops (plus an explicit stack if needed)  (B) more recursive calls  (C) extra memory allocation  (D) non-recursive function calls

✅ **Ans: (A) loops (plus an explicit stack if needed)** — (PYQ 2023)

**8.** What is the usual base case of a recursive factorial function?
(A) n == 0  (B) n < 0  (C) n > 0  (D) n == 2

✅ **Ans: (A) n == 0** — (PYQ 2025)

**9.** What is the minimum number of moves for Tower of Hanoi with n disks?
(A) 2ⁿ  (B) n²  (C) 2ⁿ − 1  (D) n!

✅ **Ans: (C) 2ⁿ − 1** — (PYQ 2023)

**10.** What is the minimum number of moves for Tower of Hanoi with 3 disks?
(A) 3  (B) 7  (C) 15  (D) 63

✅ **Ans: (B) 7** — 2³ − 1 (PYQ 2025)

**11.** What is the minimum number of moves for Tower of Hanoi with 5 disks?
(A) 31  (B) 32  (C) 25  (D) 63

✅ **Ans: (A) 31** — 2⁵ − 1

**12.** In a queue, insertion happens at the:
(A) rear  (B) front  (C) middle  (D) either end

✅ **Ans: (A) rear** — Deletion happens at the front

**13.** A circular queue solves the problem of:
(A) sorting  (B) unused space at the front of a linear (array) queue  (C) recursion  (D) none of these

✅ **Ans: (B) unused space at the front of a linear (array) queue**

**14.** A circular queue of size N is full when:
(A) (rear + 1) % N == front  (B) rear == front  (C) rear == N  (D) front == 0

✅ **Ans: (A) (rear + 1) % N == front**

**15.** A deque allows insertion and deletion at:
(A) both ends  (B) the rear only  (C) the front only  (D) the middle

✅ **Ans: (A) both ends** — (PYQ 2025)

**16.** A priority queue is most efficiently implemented using a:
(A) stack  (B) queue  (C) unsorted linked list  (D) binary heap

✅ **Ans: (D) binary heap**

**17.** How many stacks are needed to implement a queue?
(A) 1  (B) 2  (C) 3  (D) 4

✅ **Ans: (B) 2**

**18.** In tail recursion, the recursive call is:
(A) the last operation in the function  (B) the first statement  (C) inside a loop  (D) never made

✅ **Ans: (A) the last operation in the function**

**19.** With fib(0) = 0 and fib(1) = 1, what is fib(5)?
(A) 3  (B) 5  (C) 8  (D) 13

✅ **Ans: (B) 5** — 0, 1, 1, 2, 3, 5

**20.** Stack overflow during recursion happens when:
(A) a base case is present  (B) a queue is full  (C) the recursion goes too deep or the base case is missing  (D) none of these

✅ **Ans: (C) the recursion goes too deep or the base case is missing**

---

## D. Trees & Binary Search Trees

**1.** A tree is a:
(A) non-linear, hierarchical data structure  (B) linear data structure  (C) type of array  (D) type of queue

✅ **Ans: (A) non-linear, hierarchical data structure** — (PYQ 2019)

**2.** What is the maximum number of nodes in a binary tree of height h (root at height 0)?
(A) 2ʰ  (B) 2^(h+1) − 1  (C) 2h  (D) h²

✅ **Ans: (B) 2^(h+1) − 1**

**3.** What is the maximum number of nodes at level l of a binary tree (root at level 0)?
(A) 2^l  (B) l²  (C) 2l  (D) l

✅ **Ans: (A) 2^l**

**4.** How many edges does a tree with n nodes have?
(A) n  (B) n + 1  (C) n − 1  (D) 2n

✅ **Ans: (C) n − 1**

**5.** What is the order of inorder traversal?
(A) Left, Root, Right  (B) Root, Left, Right  (C) Left, Right, Root  (D) Right, Left, Root

✅ **Ans: (A) Left, Root, Right**

**6.** What is the order of preorder traversal?
(A) Left, Right, Root  (B) Root, Left, Right  (C) Left, Root, Right  (D) Right, Left, Root

✅ **Ans: (B) Root, Left, Right**

**7.** What is the order of postorder traversal?
(A) Root, Left, Right  (B) Left, Root, Right  (C) Root, Right, Left  (D) Left, Right, Root

✅ **Ans: (D) Left, Right, Root**

**8.** Inorder traversal of a BST gives the keys in:
(A) ascending (sorted) order  (B) random order  (C) descending order  (D) level order

✅ **Ans: (A) ascending (sorted) order**

*For Q9–11 use this tree: root A; A's left child is B and its right child is C; B's left child is D and its right child is E.*

**9.** What is the preorder traversal?
(A) ABDEC  (B) DBEAC  (C) DEBCA  (D) ABCDE

✅ **Ans: (A) ABDEC**

**10.** What is the inorder traversal?
(A) ABDEC  (B) DBEAC  (C) DEBCA  (D) ABCDE

✅ **Ans: (B) DBEAC**

**11.** What is the postorder traversal?
(A) ABDEC  (B) DBEAC  (C) DEBCA  (D) ABCDE

✅ **Ans: (C) DEBCA**

**12.** To delete a BST node that has one child:
(A) replace it with its parent  (B) delete it and leave the subtree unattached  (C) delete the whole subtree  (D) replace the node with its only child

✅ **Ans: (D) replace the node with its only child** — (PYQ 2024, 2025)

**13.** To delete a BST node that has two children, replace it with its:
(A) inorder successor (or inorder predecessor)  (B) parent  (C) root  (D) left child always

✅ **Ans: (A) inorder successor (or inorder predecessor)**

**14.** What is the worst-case search time in an unbalanced (skewed) BST?
(A) O(log n)  (B) O(n)  (C) O(1)  (D) O(n log n)

✅ **Ans: (B) O(n)**

**15.** In a threaded binary tree:
(A) NULL pointers are replaced by threads to the inorder predecessor/successor  (B) there are no pointers  (C) every node has three children  (D) nodes are stored in an array

✅ **Ans: (A) NULL pointers are replaced by threads to the inorder predecessor/successor** — (PYQ 2023, 2025)

**16.** The threads in a threaded binary tree use:
(A) extra nodes  (B) extra arrays  (C) link fields that would otherwise be NULL (no extra pointer space)  (D) a stack

✅ **Ans: (C) link fields that would otherwise be NULL (no extra pointer space)** — Less space than extra pointers would need (PYQ 2025)

**17.** How many NULL links does a binary tree with n nodes have?
(A) n  (B) n − 1  (C) n + 1  (D) 2n

✅ **Ans: (C) n + 1** — 2n links − (n − 1) edges

**18.** A complete binary tree is stored in an array (0-based). The children of index i are at:
(A) 2i + 1 and 2i + 2  (B) 2i and 2i + 1  (C) i + 1 and i + 2  (D) i/2

✅ **Ans: (A) 2i + 1 and 2i + 2**

**19.** In a full binary tree, every node has:
(A) 0 or 2 children  (B) exactly 1 child  (C) 2 children always  (D) any number of children

✅ **Ans: (A) 0 or 2 children**

**20.** In an expression tree, the leaves are:
(A) operators  (B) operands  (C) both  (D) neither

✅ **Ans: (B) operands**

---

## E. Balanced Trees & Heaps

**1.** The balance factor of an AVL node is:
(A) height(left subtree) − height(right subtree)  (B) height(left subtree) − height(parent)  (C) number of left children − number of right children  (D) depth − height

✅ **Ans: (A) height(left subtree) − height(right subtree)** — (PYQ 2025)

**2.** Which balance factors are allowed in an AVL tree?
(A) {0, 1}  (B) {−1, 0, 1}  (C) {−2, …, 2}  (D) any value

✅ **Ans: (B) {−1, 0, 1}**

**3.** The AVL tree is named after:
(A) Adelson-Velsky and Landis  (B) Aho, Volkov and Lee  (C) Allen, Vogel and Lamport  (D) none of these

✅ **Ans: (A) Adelson-Velsky and Landis**

**4.** What is the worst-case search time in an AVL tree?
(A) O(n)  (B) O(log n)  (C) O(1)  (D) O(n log n)

✅ **Ans: (B) O(log n)**

**5.** Which rotation fixes the Left-Left (LL) case?
(A) a single right rotation  (B) a single left rotation  (C) left-right double rotation  (D) right-left double rotation

✅ **Ans: (A) a single right rotation**

**6.** In a B-tree of order m, what is the maximum number of children per node?
(A) m − 1  (B) m  (C) 2m − 1  (D) 2m

✅ **Ans: (B) m** — (PYQ 2025)

**7.** In a B-tree of order m, what is the maximum number of keys per node?
(A) m − 1  (B) m  (C) 2m  (D) m + 1

✅ **Ans: (A) m − 1**

**8.** B-trees are mainly used in:
(A) compilers  (B) networking  (C) database and file-system indexing  (D) sorting

✅ **Ans: (C) database and file-system indexing**

**9.** In a B+ tree, the actual data records are kept in the:
(A) leaf nodes, which are linked together  (B) internal nodes only  (C) root only  (D) a separate stack

✅ **Ans: (A) leaf nodes, which are linked together**

**10.** In a red-black tree, the root is always:
(A) red  (B) either colour  (C) alternating  (D) black

✅ **Ans: (D) black**

**11.** A heap is a:
(A) complete binary tree that satisfies the heap property  (B) BST  (C) linked list  (D) graph

✅ **Ans: (A) complete binary tree that satisfies the heap property**

**12.** In a max-heap:
(A) each parent ≤ its children  (B) each parent ≥ its children  (C) all nodes are sorted  (D) none of these

✅ **Ans: (B) each parent ≥ its children**

**13.** The root of a min-heap holds the:
(A) minimum element  (B) maximum element  (C) median  (D) last inserted element

✅ **Ans: (A) minimum element**

**14.** What is the time to insert into a binary heap?
(A) O(1)  (B) O(log n)  (C) O(n)  (D) O(n log n)

✅ **Ans: (B) O(log n)**

**15.** What is the time to build a heap from n elements (bottom-up)?
(A) O(n)  (B) O(n log n)  (C) O(log n)  (D) O(n²)

✅ **Ans: (A) O(n)**

**16.** What is the time complexity of heap sort?
(A) O(n)  (B) O(n²)  (C) O(n log n)  (D) O(log n)

✅ **Ans: (C) O(n log n)**

**17.** In an array-based heap (0-based), the parent of node i is at:
(A) ⌊(i − 1)/2⌋  (B) 2i  (C) i − 1  (D) i/3

✅ **Ans: (A) ⌊(i − 1)/2⌋**

**18.** What is the height of a complete binary tree with n nodes?
(A) ⌊log₂ n⌋  (B) n  (C) n/2  (D) √n

✅ **Ans: (A) ⌊log₂ n⌋**

**19.** A trie is used for:
(A) sorting numbers  (B) graphs  (C) hashing  (D) prefix searches on strings (e.g. dictionaries)

✅ **Ans: (D) prefix searches on strings (e.g. dictionaries)**

**20.** A splay tree moves each accessed node to the:
(A) root  (B) leaf level  (C) left subtree  (D) right subtree

✅ **Ans: (A) root**

---

## F. Graphs & Graph Algorithms

**1.** BFS uses a:
(A) queue  (B) stack  (C) heap  (D) tree

✅ **Ans: (A) queue**

**2.** DFS uses a:
(A) queue  (B) stack (or recursion)  (C) heap  (D) tree

✅ **Ans: (B) stack (or recursion)** — (PYQ 2023)

**3.** BFS explores level by level, starting from the:
(A) shallowest level (the source)  (B) deepest level  (C) middle level  (D) vertex with the highest degree

✅ **Ans: (A) shallowest level (the source)** — (PYQ 2025)

**4.** Which search usually needs the least memory?
(A) BFS  (B) Optimal search  (C) DFS  (D) Bidirectional search

✅ **Ans: (C) DFS** — (PYQ 2025)

**5.** Connected components of a graph can be found using:
(A) DFS only  (B) BFS only  (C) both DFS and BFS  (D) neither

✅ **Ans: (C) both DFS and BFS** — (PYQ 2025)

**6.** How many edges does a spanning tree of a connected graph with n vertices have?
(A) n  (B) n − 1  (C) n + 1  (D) n(n−1)/2

✅ **Ans: (B) n − 1** — (PYQ 2024, 2025)

**7.** What is the maximum number of edges in a simple undirected graph with n vertices?
(A) n  (B) n − 1  (C) n²  (D) n(n−1)/2

✅ **Ans: (D) n(n−1)/2**

**8.** The sum of the degrees of all vertices equals:
(A) 2 × the number of edges  (B) the number of edges  (C) the number of vertices  (D) V + E

✅ **Ans: (A) 2 × the number of edges** — Handshake lemma

**9.** How much space does an adjacency matrix need?
(A) O(V)  (B) O(V²)  (C) O(E)  (D) O(V + E)

✅ **Ans: (B) O(V²)**

**10.** How much space does an adjacency list need?
(A) O(V²)  (B) O(V)  (C) O(E²)  (D) O(V + E)

✅ **Ans: (D) O(V + E)**

**11.** Dijkstra's algorithm finds:
(A) single-source shortest paths when edge weights are non-negative  (B) all-pairs shortest paths  (C) an MST  (D) a topological order

✅ **Ans: (A) single-source shortest paths when edge weights are non-negative** — It is greedy

**12.** Bellman-Ford can handle:
(A) only positive weights  (B) negative edge weights, and detects negative cycles  (C) only unweighted graphs  (D) none of these

✅ **Ans: (B) negative edge weights, and detects negative cycles**

**13.** What is the time complexity of Floyd-Warshall on n vertices?
(A) O(n)  (B) O(n²)  (C) O(n³)  (D) O(n log n)

✅ **Ans: (C) O(n³)** — (PYQ 2025)

**14.** Floyd-Warshall solves the:
(A) all-pairs shortest path problem  (B) single-source shortest path problem  (C) MST problem  (D) topological sort problem

✅ **Ans: (A) all-pairs shortest path problem** — It uses DP and transitive reachability (PYQ 2024)

**15.** By the cut property, Prim's algorithm always adds:
(A) the minimum-weight edge crossing the cut  (B) the maximum-weight edge  (C) a random edge  (D) the edge to the farthest vertex

✅ **Ans: (A) the minimum-weight edge crossing the cut** — (PYQ 2025)

**16.** Kruskal's algorithm first sorts the:
(A) edges by weight  (B) vertices by degree  (C) vertices alphabetically  (D) adjacency list

✅ **Ans: (A) edges by weight**

**17.** Kruskal's algorithm detects cycles using:
(A) a stack  (B) a queue  (C) a disjoint-set (union-find) structure  (D) a heap only

✅ **Ans: (C) a disjoint-set (union-find) structure**

**18.** Topological sorting applies to:
(A) a DAG (directed acyclic graph)  (B) any graph  (C) undirected graphs  (D) cyclic graphs

✅ **Ans: (A) a DAG (directed acyclic graph)**

**19.** A directed edge from vertex A to vertex B is written:
(A) (A, B)  (B) {A, B}  (C) [B, A]  (D) A–B

✅ **Ans: (A) (A, B)** — (PYQ 2023)

**20.** How many edges does the complete graph K₅ have?
(A) 5  (B) 10  (C) 20  (D) 25

✅ **Ans: (B) 10** — 5 × 4 / 2

---

## G. Sorting

**1.** What is the time complexity of merge sort?
(A) O(n)  (B) O(log n)  (C) O(n log n) in all cases  (D) O(n²)

✅ **Ans: (C) O(n log n) in all cases** — (PYQ 2024, 2025)

**2.** Which sort compares neighbouring elements and swaps them when needed?
(A) Selection sort  (B) Bubble sort  (C) Insertion sort  (D) Quick sort

✅ **Ans: (B) Bubble sort** — (PYQ 2025)

**3.** What is the worst-case complexity of quick sort?
(A) O(n²)  (B) O(n log n)  (C) O(n)  (D) O(log n)

✅ **Ans: (A) O(n²)** — Happens with a bad pivot on sorted data

**4.** What is the average-case complexity of quick sort?
(A) O(n²)  (B) O(n log n)  (C) O(n)  (D) O(log n)

✅ **Ans: (B) O(n log n)**

**5.** What is the worst-case complexity of insertion sort?
(A) O(n²)  (B) O(n log n)  (C) O(n)  (D) O(log n)

✅ **Ans: (A) O(n²)** — (PYQ 2025)

**6.** Which of these sorts is stable?
(A) Merge sort  (B) Quick sort  (C) Heap sort  (D) Selection sort

✅ **Ans: (A) Merge sort** — Insertion and bubble sort are stable too

**7.** Which of these sorts is in-place?
(A) Merge sort  (B) Quick sort  (C) Counting sort  (D) Radix sort

✅ **Ans: (B) Quick sort**

**8.** Which sort makes the fewest swaps (at most n − 1)?
(A) Bubble sort  (B) Insertion sort  (C) Selection sort  (D) Merge sort

✅ **Ans: (C) Selection sort**

**9.** Counting sort is efficient when the range of key values is:
(A) small  (B) very large  (C) negative  (D) made of floats

✅ **Ans: (A) small** — (PYQ 2024)

**10.** What is the time complexity of counting sort (k = range of keys)?
(A) O(n²)  (B) O(n log n)  (C) O(log n)  (D) O(n + k)

✅ **Ans: (D) O(n + k)**

**11.** How much extra space does merge sort need?
(A) O(n)  (B) O(1)  (C) O(log n)  (D) O(n²)

✅ **Ans: (A) O(n)**

**12.** Which sort works best on nearly sorted data?
(A) Insertion sort  (B) Selection sort  (C) Heap sort  (D) Quick sort with the first element as pivot

✅ **Ans: (A) Insertion sort**

**13.** Which pair of sorts uses divide and conquer?
(A) Bubble and insertion  (B) Merge and quick  (C) Selection and bubble  (D) Counting and radix

✅ **Ans: (B) Merge and quick**

**14.** What is the worst-case complexity of heap sort?
(A) O(n)  (B) O(n²)  (C) O(n log n)  (D) O(log n)

✅ **Ans: (C) O(n log n)**

**15.** What is the lower bound for any comparison-based sort?
(A) Ω(n log n)  (B) Ω(n)  (C) Ω(n²)  (D) Ω(log n)

✅ **Ans: (A) Ω(n log n)**

**16.** After the first pass of bubble sort (ascending), the largest element is:
(A) in the last position  (B) in the first position  (C) in the middle  (D) anywhere

✅ **Ans: (A) in the last position**

**17.** How many comparisons does selection sort make?
(A) n  (B) n(n−1)/2  (C) n log n  (D) 2n

✅ **Ans: (B) n(n−1)/2**

**18.** LSD radix sort processes the digits starting from the:
(A) least significant digit  (B) most significant digit  (C) middle digit  (D) random digit

✅ **Ans: (A) least significant digit**

**19.** In quick sort partitioning, the elements smaller than the pivot go to the:
(A) left  (B) right  (C) end  (D) nowhere

✅ **Ans: (A) left**

**20.** What is [5, 1, 4, 2] after the first pass of bubble sort (ascending)?
(A) [1, 2, 4, 5]  (B) [1, 5, 4, 2]  (C) [4, 1, 2, 5]  (D) [1, 4, 2, 5]

✅ **Ans: (D) [1, 4, 2, 5]** — 5↔1 → [1,5,4,2], 5↔4 → [1,4,5,2], 5↔2 → [1,4,2,5]

---

## H. Searching & Hashing

**1.** Binary search requires the data to be:
(A) sorted, in an array  (B) in a linked list  (C) unsorted  (D) in a hash table

✅ **Ans: (A) sorted, in an array**

**2.** What is the time complexity of binary search?
(A) O(n)  (B) O(log n)  (C) O(1)  (D) O(n log n)

✅ **Ans: (B) O(log n)**

**3.** On average, how many comparisons does a successful linear search make over n elements?
(A) (n + 1)/2  (B) n²  (C) log n  (D) 1

✅ **Ans: (A) (n + 1)/2**

**4.** What is the average search time in a hash table?
(A) O(1)  (B) O(n)  (C) O(log n)  (D) O(n²)

✅ **Ans: (A) O(1)**

**5.** A collision in hashing means:
(A) two keys map to the same index  (B) the table is full  (C) a key is lost  (D) the hash function fails

✅ **Ans: (A) two keys map to the same index**

**6.** Separate chaining stores collided elements in:
(A) arrays  (B) linked lists  (C) stacks  (D) queues

✅ **Ans: (B) linked lists** — (PYQ 2023, 2025)

**7.** Linear probing places a collided element in:
(A) a linked list  (B) a slot given by a second hash  (C) the next empty slot, checked one by one  (D) a new table

✅ **Ans: (C) the next empty slot, checked one by one** — (PYQ 2023)

**8.** The main problem with linear probing is:
(A) primary clustering  (B) secondary clustering  (C) no collisions  (D) wasted pointers

✅ **Ans: (A) primary clustering**

**9.** Quadratic probing reduces:
(A) secondary clustering  (B) nothing  (C) all collisions  (D) primary clustering

✅ **Ans: (D) primary clustering**

**10.** Double hashing uses:
(A) a second hash function to decide the step size  (B) two tables  (C) linked lists  (D) sorting

✅ **Ans: (A) a second hash function to decide the step size**

**11.** The load factor α of a hash table is:
(A) n/m (keys ÷ slots)  (B) m/n  (C) n × m  (D) n − m

✅ **Ans: (A) n/m (keys ÷ slots)**

**12.** With h(k) = k mod 10, where does 47 go?
(A) 4  (B) 7  (C) 47  (D) 0

✅ **Ans: (B) 7**

**13.** With h(k) = k mod 10, inserting 15 and then 25 causes:
(A) no collision  (B) a collision at index 0  (C) a collision at index 5  (D) overflow

✅ **Ans: (C) a collision at index 5**

**14.** A good hash function should:
(A) spread keys uniformly across the table  (B) map every key to index 0  (C) be slow  (D) need sorted keys

✅ **Ans: (A) spread keys uniformly across the table**

**15.** Binary search for 23 in [2, 5, 8, 12, 16, 23, 38, 56, 72, 91]. How many comparisons does it take?
(A) 1  (B) 2  (C) 3  (D) 4

✅ **Ans: (C) 3** — mid=4 (16) → go right; mid=7 (56) → go left; mid=5 (23) → found

**16.** Interpolation search works best on:
(A) sorted, uniformly distributed data  (B) unsorted data  (C) linked lists  (D) trees

✅ **Ans: (A) sorted, uniformly distributed data**

**17.** With open addressing, the load factor must be:
(A) ≤ 1  (B) > 1  (C) exactly 2  (D) anything

✅ **Ans: (A) ≤ 1**

**18.** Rehashing means:
(A) deleting keys  (B) resizing the table and re-inserting all the keys  (C) sorting the table  (D) none of these

✅ **Ans: (B) resizing the table and re-inserting all the keys**

**19.** Which data structure is a classic time–space tradeoff?
(A) Hash table  (B) Linear array search  (C) Stack  (D) Queue

✅ **Ans: (A) Hash table** — (PYQ 2023)

**20.** A sentinel in linear search:
(A) sorts the array  (B) hashes the keys  (C) always doubles the speed  (D) removes the end-of-array check from each loop step

✅ **Ans: (D) removes the end-of-array check from each loop step**

---

## I. Divide & Conquer and Greedy

**1.** Divide and conquer solves a problem by:
(A) solving subproblems iteratively  (B) solving subproblems recursively and combining the results  (C) using heuristics  (D) making greedy choices

✅ **Ans: (B) solving subproblems recursively and combining the results** — (PYQ 2023, 2025)

**2.** What are the three steps of divide and conquer?
(A) Divide, conquer, combine  (B) Sort, search, merge  (C) Push, pop, peek  (D) Select, project, join

✅ **Ans: (A) Divide, conquer, combine**

**3.** What is the time complexity of finding the maximum and minimum by divide and conquer?
(A) O(n)  (B) O(log n)  (C) O(n log n)  (D) O(n²)

✅ **Ans: (A) O(n)** — (PYQ 2025)

**4.** In max-min by divide and conquer, how are the two halves combined?
(A) Compare the two maxima, and compare the two minima  (B) Average them  (C) Add them  (D) Multiply them

✅ **Ans: (A) Compare the two maxima, and compare the two minima** — (PYQ 2025)

**5.** How many comparisons does max-min by divide and conquer make (n a power of 2)?
(A) 2n − 2  (B) n  (C) 3n/2 − 2  (D) n²

✅ **Ans: (C) 3n/2 − 2**

**6.** T(n) = T(n/2) + T(n/3) + n describes which paradigm?
(A) Divide and conquer  (B) Dynamic programming  (C) Greedy  (D) Backtracking

✅ **Ans: (A) Divide and conquer** — (PYQ 2025)

**7.** What is the recurrence for binary search?
(A) T(n) = 2T(n/2) + n  (B) T(n) = T(n/2) + 1  (C) T(n) = T(n−1) + n  (D) T(n) = 2T(n−1)

✅ **Ans: (B) T(n) = T(n/2) + 1** — (PYQ 2023)

**8.** What is the recurrence for merge sort?
(A) T(n) = 2T(n/2) + n  (B) T(n) = T(n/2) + 1  (C) T(n) = T(n−1) + 1  (D) T(n) = 2T(n−1) + 1

✅ **Ans: (A) T(n) = 2T(n/2) + n**

**9.** What is the complexity of Strassen's matrix multiplication?
(A) O(n³)  (B) O(n^2.81)  (C) O(n²)  (D) O(n log n)

✅ **Ans: (B) O(n^2.81)**

**10.** A greedy algorithm:
(A) makes the locally optimal choice at each step  (B) tries every possibility  (C) always backtracks  (D) uses memoization

✅ **Ans: (A) makes the locally optimal choice at each step**

**11.** In Huffman coding, which characters get shorter codes?
(A) those with higher frequency  (B) those with lower frequency  (C) those with larger ASCII values  (D) all characters equally

✅ **Ans: (A) those with higher frequency** — (PYQ 2025)

**12.** Huffman coding is a:
(A) DP algorithm  (B) D&C algorithm  (C) greedy algorithm  (D) backtracking algorithm

✅ **Ans: (C) greedy algorithm**

**13.** The fractional knapsack problem is solved optimally by:
(A) greedy, using the value/weight ratio  (B) backtracking only  (C) BFS  (D) sorting by weight only

✅ **Ans: (A) greedy, using the value/weight ratio**

**14.** The 0/1 knapsack problem is solved optimally by:
(A) greedy  (B) divide and conquer  (C) BFS  (D) dynamic programming

✅ **Ans: (D) dynamic programming**

**15.** Activity selection (greedy) picks the activity that:
(A) finishes earliest  (B) starts earliest  (C) lasts longest  (D) is chosen at random

✅ **Ans: (A) finishes earliest**

**16.** Prim's algorithm is correct because of the:
(A) cut property (minimum edge crossing a cut)  (B) cycle property only  (C) optimal BST property  (D) transitive property

✅ **Ans: (A) cut property (minimum edge crossing a cut)** — (PYQ 2025)

**17.** Dijkstra's algorithm is a:
(A) greedy algorithm  (B) DP algorithm  (C) backtracking algorithm  (D) brute-force algorithm

✅ **Ans: (A) greedy algorithm**

**18.** Job sequencing with deadlines is usually solved with:
(A) DP  (B) greedy  (C) backtracking  (D) branch and bound

✅ **Ans: (B) greedy**

**19.** For which problem does greedy fail to give the optimum?
(A) 0/1 knapsack  (B) fractional knapsack  (C) activity selection  (D) Huffman coding

✅ **Ans: (A) 0/1 knapsack**

**20.** For coin change with arbitrary denominations, greedy:
(A) is always optimal  (B) never terminates  (C) takes exponential time  (D) may not give the optimal answer

✅ **Ans: (D) may not give the optimal answer** — e.g. coins {1, 3, 4} for 6

---

## J. Dynamic Programming, Backtracking & P/NP

**1.** What are the two key properties needed for dynamic programming?
(A) Optimal substructure and overlapping subproblems  (B) Greedy choice and sorting  (C) Recursion and loops  (D) Hashing and indexing

✅ **Ans: (A) Optimal substructure and overlapping subproblems**

**2.** Memoization is used to:
(A) divide a graph into stages  (B) sort vertices  (C) store the solutions of overlapping subproblems  (D) find the shortest path directly

✅ **Ans: (C) store the solutions of overlapping subproblems** — (PYQ 2025)

**3.** Which DP property is used to solve the Optimal BST problem?
(A) Optimal substructure  (B) Greedy choice property  (C) Divide and conquer  (D) Linear programming

✅ **Ans: (A) Optimal substructure** — (PYQ 2025)

**4.** The multistage graph problem is solved using:
(A) dynamic programming  (B) BFS only  (C) sorting  (D) hashing

✅ **Ans: (A) dynamic programming**

**5.** What is the time complexity of computing Fibonacci with DP?
(A) O(n)  (B) O(2ⁿ)  (C) O(log n)  (D) O(n²)

✅ **Ans: (A) O(n)**

**6.** What is the time complexity of naive recursive Fibonacci?
(A) O(n)  (B) O(2ⁿ)  (C) O(log n)  (D) O(n²)

✅ **Ans: (B) O(2ⁿ)**

**7.** Longest Common Subsequence (LCS) is solved with:
(A) dynamic programming  (B) greedy  (C) BFS  (D) hashing

✅ **Ans: (A) dynamic programming**

**8.** Floyd-Warshall belongs to which paradigm?
(A) Greedy  (B) Dynamic programming  (C) Divide and conquer  (D) Backtracking

✅ **Ans: (B) Dynamic programming**

**9.** Backtracking:
(A) builds a solution step by step and abandons a partial solution as soon as it breaks a constraint  (B) always uses a greedy choice  (C) never uses recursion  (D) sorts the input first

✅ **Ans: (A) builds a solution step by step and abandons a partial solution as soon as it breaks a constraint**

**10.** When only one solution is needed, 8-Queens backtracking, on finding a feasible solution:
(A) stops and returns it  (B) keeps searching for more  (C) tries every possibility anyway  (D) rearranges the queens to optimise

✅ **Ans: (A) stops and returns it** — (PYQ 2025)

**11.** The goal of the Hamiltonian cycle problem is to find a cycle that:
(A) has the fewest edges  (B) has the lowest weight  (C) visits every vertex exactly once  (D) has the most edges

✅ **Ans: (C) visits every vertex exactly once** — (PYQ 2025)

**12.** In N-Queens, no two queens may share a:
(A) row, column or diagonal  (B) row only  (C) column only  (D) colour

✅ **Ans: (A) row, column or diagonal**

**13.** The sum-of-subsets problem is usually solved with:
(A) greedy  (B) DP only  (C) divide and conquer  (D) backtracking

✅ **Ans: (D) backtracking**

**14.** Graph colouring (m-colouring) is solved with:
(A) backtracking  (B) greedy only  (C) hashing  (D) sorting

✅ **Ans: (A) backtracking**

**15.** Branch and bound is used for:
(A) optimisation problems such as TSP and 0/1 knapsack  (B) sorting  (C) hashing  (D) string matching

✅ **Ans: (A) optimisation problems such as TSP and 0/1 knapsack**

**16.** A problem is in NP if:
(A) a proposed solution can be verified in polynomial time  (B) it cannot be solved  (C) it has exponential complexity  (D) it is solved by a deterministic linear algorithm

✅ **Ans: (A) a proposed solution can be verified in polynomial time** — (PYQ 2025)

**17.** Who introduced the concept of NP-completeness?
(A) Richard Karp  (B) Stephen Cook  (C) Donald Knuth  (D) John Nash

✅ **Ans: (B) Stephen Cook** — 1971; Karp extended it in 1972 (PYQ 2025)

**18.** Which of these is NP-complete?
(A) SAT (Boolean satisfiability)  (B) Sorting  (C) Binary search  (D) Single-source shortest path

✅ **Ans: (A) SAT (Boolean satisfiability)**

**19.** Which relation between P and NP is known to be true?
(A) P ⊆ NP  (B) NP ⊆ P has been proved  (C) P ∩ NP = ∅  (D) none of these

✅ **Ans: (A) P ⊆ NP** — Whether P = NP is still unsolved

**20.** The decision version of the Travelling Salesman Problem is:
(A) in P  (B) undecidable  (C) NP-complete  (D) solvable in linear time

✅ **Ans: (C) NP-complete**

---

### Score tracker

| Topic | Attempt 1 | Attempt 2 |
|---|---|---|
| A. Complexity | /20 | /20 |
| B. Arrays & linked lists | /20 | /20 |
| C. Stacks, queues & recursion | /20 | /20 |
| D. Trees & BST | /20 | /20 |
| E. Balanced trees & heaps | /20 | /20 |
| F. Graphs | /20 | /20 |
| G. Sorting | /20 | /20 |
| H. Searching & hashing | /20 | /20 |
| I. D&C & greedy | /20 | /20 |
| J. DP, backtracking & P/NP | /20 | /20 |
| **Total** | **/200** | **/200** |
