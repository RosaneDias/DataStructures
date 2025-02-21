📚 Study Roadmap: Simplest → Hardest (With Python)
We will cover CtCI (Cracking the Code Interview) questions progressively:

🟢 **Phase 1: Fundamentals (Simple Problems, Big O Basics)**
📌 **Topics:**
- Big O notation (Time Complexity)
- Arrays & Strings
- Hash Tables (Dictionaries in Python)

📌 **Example Questions:**
- **Big O Practice:** Analyze time complexity of simple loops.
- **Arrays & Strings:**
  - Check Permutation (`is_permutation(s1, s2)`) 
  - URLify (`replace_spaces(s)`) 
- **Hashing:**
  - Two Sum (`find_pair(arr, target)`) 

1️⃣ **Arrays & Strings in Python**
📌 **Arrays (Lists)**
- Python lists work like dynamic arrays.
- Indexing starts at 0.
- Common operations: append, insert, remove, pop, slicing.
```python
# Creating a list
arr = [1, 2, 3, 4, 5]

# Accessing elements
print(arr[0])  # Output: 1

# Adding elements
arr.append(6)  # [1, 2, 3, 4, 5, 6]
arr.insert(2, 99)  # [1, 2, 99, 3, 4, 5, 6]

# Removing elements
arr.remove(99)  # [1, 2, 3, 4, 5, 6]
arr.pop()  # Removes last element
```
📌 **Strings (Immutable)**
- Strings cannot be modified directly (must create a new one).
- Slicing is important.
```python
s = "hello"
print(s[1:4])  # "ell"
print(s[::-1])  # "olleh" (reversed)
```
✅ **Practice Task:** Write a Python function that reverses a string without using `[::-1]`.

2️⃣ **Loops (for, while)**
📌 **For Loops**
```python
# Looping through an array
arr = [1, 2, 3, 4]
for num in arr:
    print(num)  # Prints 1, 2, 3, 4

# Looping with index
for i in range(len(arr)):
    print(f"Index {i}: {arr[i]}")
```
📌 **While Loops**
```python
x = 5
while x > 0:
    print(x)
    x -= 1  # Decrement
```
✅ **Practice Task:** Write a function to find the sum of all even numbers in a given list.

3️⃣ **Dictionaries (Hash Tables)**
📌 **Dictionaries in Python (O(1) Lookups)**
```python
# Creating a dictionary
person = {"name": "Alice", "age": 25, "city": "Sao Paulo"}

# Accessing values
print(person["name"])  # Alice

# Adding & Updating
person["job"] = "Engineer"
person["age"] = 26

# Looping through dictionary
for key, value in person.items():
    print(f"{key}: {value}")
```
✅ **Practice Task:** Write a function that counts character frequency in a string using a dictionary.

4️⃣ **Functions & Recursion**
📌 **Defining Functions**
```python
def add(a, b):
    return a + b

print(add(3, 5))  # Output: 8
```
📌 **Recursion (Base + Recursive Case)**
```python
def factorial(n):
    if n == 0:
        return 1
    return n * factorial(n - 1)

print(factorial(5))  # Output: 120
```
✅ **Practice Task:** Write a recursive function to compute the Fibonacci sequence.

🟡 **Phase 2: Intermediate Problems (Linked Lists, Recursion, Sorting)**
📌 **Topics:**
- Linked Lists (Singly & Doubly)
- Stacks & Queues
- Recursion & Backtracking
- Sorting Algorithms (Merge Sort, Quick Sort, etc.)

📌 **Example Questions:**
- **Linked Lists:**
  - Remove Duplicates (`remove_dupes(head)`) 
  - Detect Loop in Linked List (`detect_cycle(head)`) 
- **Stacks & Queues:**
  - Min Stack (`getMin()` in O(1) time) 
- **Recursion:**
  - Power Set (`subsets(nums)`) 
- **Sorting:**
  - Implement Merge Sort (`merge_sort(arr)`) 

🟠 **Phase 3: Advanced Problems (Trees, Graphs, Dynamic Programming)**
📌 **Topics:**
- Binary Trees & BSTs
- Graphs (BFS, DFS, Dijkstra’s Algorithm)
- Dynamic Programming (Tabulation vs. Memoization)

📌 **Example Questions:**
- **Trees:**
  - Lowest Common Ancestor (LCA) (`findLCA(root, n1, n2)`) 
  - Balanced Binary Tree (`isBalanced(root)`) 
- **Graphs:**
  - Course Schedule (Topological Sort) (`canFinish(numCourses, prerequisites)`) 
  - Word Ladder (BFS) (`ladderLength(beginWord, endWord, wordList)`) 
- **Dynamic Programming:**
  - Fibonacci with Memoization (`fib(n)`) 
  - Longest Common Subsequence (LCS) (`lcs(str1, str2)`) 

🔴 **Phase 4: Expert-Level Problems (Hard Google-Level Questions)**
📌 **Topics:**
- Tries (Prefix Trees)
- Advanced Graphs (Union-Find, A* Algorithm)
- Bit Manipulation & Hard DP Problems

📌 **Example Questions:**
- **Tries:**
  - Autocomplete System (`insert(), searchPrefix()`) 
- **Graphs:**
  - Connected Components in a Graph (`numComponents(graph)`) 
- **Bit Manipulation:**
  - Single Number (Using XOR) (`findUnique(nums)`) 
- **Hard DP:**
  - Word Break Problem (`canSegment(s, wordDict)`)
