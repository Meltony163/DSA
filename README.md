# Data Structures and Algorithms (DSA) Course – Labs & Implementations

## 📌 Overview

During my Data Structures and Algorithms (DSA) course, I implemented a wide range of fundamental data structures and algorithms from scratch using Python.  
The course focused on understanding internal logic, implementation details, and algorithmic complexity analysis.

---

# 🧪 Lab 1 – Core Data Structures Implementation

## 🔹 Task 1 — Doubly Linked List of Students

### 1️⃣ Student Class

Created a `Student` class with the following attributes:

- `id: int`
- `name: str`
- `grades: list[float]` (exactly 5 grades)

### Implemented Getters:
- `get_id()`
- `get_name()`
- `get_grades()`
- `get_average()` → Returns the average of the 5 grades

### Implemented Setters:
- `set_id(new_id)`
- `set_name(new_name)`
- `set_grades(new_grades)`
  - Validates that exactly 5 numeric grades are provided.

---

### 2️⃣ Node Class

Each node contains:
- `data: Student`
- `prev`
- `next`

---

### 3️⃣ DoublyLinkedList Class

Implemented the following methods:

- `append(student)` → Add student at the end  
- `prepend(student)` → Add student at the beginning  
- `delete_by_id(student_id)` → Remove student by id  
- `search_by_name(name)` → Return matching student(s)  
- `search_by_id(student_id)` → Return the student  
- `count_nodes()` → Return number of nodes  
- `display_forward()` → Print from head to tail  
- `display_backward()` → Print from tail to head  

---

## 🔹 Task 2 — Stack Using Linked List

Implemented a `Stack` class using a linked list structure.

### Operations:
- `push(item)`
- `pop()`
- `peek()`
- `is_empty()`
- `size()`

Used `Student` objects with stack operations.

---

## 🔹 Task 3 — Queue Using Array

Implemented a `Queue` class using a Python list (array-based implementation).

### Operations:
- `enqueue(item)`
- `dequeue()`
- `front()`
- `is_empty()`
- `is_full()` (for fixed-size implementation)
- `size()`

Used `Student` objects with queue operations.

---

# 🧪 Lab 2 – Algorithm Complexity Analysis

In this lab, I analyzed the time and space complexity of implemented algorithms.

Topics included:
- Big-O Notation
- Best, Average, and Worst-case analysis
- Comparing iterative vs recursive approaches
- Complexity comparison between different data structures

---

# 🧪 Lab 3 – Divide and Conquer & Classic Algorithms

Implemented the following algorithms:

- Merge Sort
- Max–Min using Divide and Conquer
- Strassen Matrix Multiplication
- Karatsuba Multiplication
- Knapsack Problem
- Matrix Chain Multiplication

This lab strengthened my understanding of recursion, divide-and-conquer strategies, and dynamic programming concepts.

---

# 🧪 Lab 4 – Trees and Graphs

## 🔹 Task 1 — Binary Tree Implementation

Created:

### Node Class
- `value`
- `left`
- `right`

### BinaryTree Class
- `root`
- Optional `insert()` (BST insertion) or manual linking for testing

---

## 🔹 Task 2 — Binary Tree Traversals

Implemented recursive (and optional iterative) versions of:

- Inorder (Left, Root, Right)
- Preorder (Root, Left, Right)
- Postorder (Left, Right, Root)

Each traversal function returns a list of visited values.

---

## 🔹 Task 3 — Build Tree from Traversals

### A) Build from Inorder + Preorder

Rules:
- `preorder[0]` is the root
- Find root in inorder → split into left/right
- Split preorder accordingly and recurse

### B) Build from Inorder + Postorder

Rules:
- `postorder[-1]` is the root
- Find root in inorder → split into left/right
- Split postorder accordingly and recurse

After reconstruction, the tree was printed in readable form (sideways or level-order).

Note:
Preorder + Postorder alone is not sufficient to uniquely reconstruct a general binary tree without additional constraints.

---

## 🔹 Task 4 — Graph Implementation (Adjacency List)

Built a `Graph` class using dictionary/list representation:

- `add_vertex(v)`
- `add_edge(u, v)` (directed or undirected)

---

## 🔹 Task 5 — Graph Traversals

### Depth First Search (DFS)
- Recursive DFS
- Iterative DFS using a stack

### Breadth First Search (BFS)
- BFS using a queue

Each traversal returns the visitation order.

---

# 🎯 Key Learning Outcomes

- Strong understanding of linked structures
- Implementing stacks and queues from scratch
- Complexity analysis using Big-O notation
- Applying divide and conquer strategies
- Implementing advanced multiplication algorithms
- Understanding dynamic programming problems
- Building and traversing trees
- Reconstructing trees from traversals
- Implementing graphs and graph traversal algorithms

---

# 🛠️ Tools Used

- Python
- Object-Oriented Programming (OOP)
- Recursion
- Algorithm Analysis Techniques

---

# 🚀 Conclusion

This course significantly strengthened my problem-solving skills and deepened my understanding of fundamental data structures and algorithms, preparing me for technical interviews and competitive programming.
