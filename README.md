# Data_structure-and-Algorithms
Learn Data Structure and Algorithms in C and C++

Here is a list of common **Data Structures** categorized by their types:

### 1. **Linear Data Structures**
   - **Array**: A collection of elements identified by index or key.
   - **Linked List**: A linear collection of elements, called nodes, where each node contains a reference (or link) to the next node in the sequence.
     - **Singly Linked List**
     - **Doubly Linked List**
     - **Circular Linked List**
   - **Stack**: Follows Last In First Out (LIFO) principle.
   - **Queue**: Follows First In First Out (FIFO) principle.
     - **Simple Queue**
     - **Circular Queue**
     - **Priority Queue**
     - **Deque (Double-ended Queue)**

### 2. **Non-Linear Data Structures**
   - **Tree**: A hierarchical structure where elements are organized into nodes, with a root node and children nodes.
     - **Binary Tree**
     - **Binary Search Tree (BST)**
     - **AVL Tree**
     - **Red-Black Tree**
     - **Heap (Max Heap, Min Heap)**
     - **Trie**
     - **Segment Tree**
     - **B-tree**
   - **Graph**: A set of nodes (vertices) connected by edges.
     - **Directed Graph**
     - **Undirected Graph**
     - **Weighted Graph**
     - **Unweighted Graph**
     - **Adjacency Matrix**
     - **Adjacency List**

### 3. **Hash-based Data Structures**
   - **Hash Table/Hash Map**: Stores key-value pairs and uses a hash function to compute an index into an array of buckets.
   - **Hash Set**: A collection that contains no duplicate elements.

### 4. **Advanced Data Structures**
   - **Fenwick Tree (Binary Indexed Tree)**: Used for efficiently calculating cumulative frequency tables.
   - **Disjoint Set (Union-Find)**: Keeps track of a partition of a set into disjoint subsets.
   - **Suffix Tree**: A compressed trie of all suffixes of a string.
   - **Trie (Prefix Tree)**: Used to store a dynamic set or associative array where the keys are usually strings.

### 5. **Specialized Data Structures**
   - **Bloom Filter**: A space-efficient probabilistic data structure used to test whether an element is in a set.
   - **Skip List**: A linked list with multiple levels used for fast search, insertion, and deletion.
   - **Sparse Matrix**: A matrix in which most of the elements are zero, stored efficiently.

### 6. **String Data Structures**
   - **Suffix Array**: An array of integers giving the starting positions of suffixes of a string.
   - **KMP Table (Knuth-Morris-Pratt Algorithm Table)**: Used for pattern matching in strings.

These data structures are fundamental in computer science and are crucial for developing efficient algorithms. Let me know if you'd like to explore any specific data structure in more detail!


Here is a comprehensive list of **Algorithms**, categorized by their purpose and type:

### 1. **Searching Algorithms**
   - **Linear Search**: Sequentially checks each element of the list until a match is found or the whole list has been searched.
   - **Binary Search**: Finds the position of a target value within a sorted array by repeatedly dividing the search interval in half.
   - **Exponential Search**: An algorithm that finds the range in which a target value lies and then applies binary search within that range.
   - **Jump Search**: Divides the list into blocks and jumps ahead by a fixed number of steps to find the target.
   - **Interpolation Search**: Similar to binary search but suitable for uniformly distributed values by using interpolation formulas.

### 2. **Sorting Algorithms**
   - **Bubble Sort**: Repeatedly swaps adjacent elements if they are in the wrong order.
   - **Selection Sort**: Finds the minimum element and places it at the beginning, then repeats with the remaining elements.
   - **Insertion Sort**: Builds the final sorted array one item at a time by inserting unsorted elements at their correct position.
   - **Merge Sort**: Divides the array into halves, recursively sorts them, and merges the sorted halves.
   - **Quick Sort**: Uses a pivot element to partition the array into two parts, then sorts them recursively.
   - **Heap Sort**: Converts the array into a binary heap and repeatedly extracts the maximum/minimum element.
   - **Radix Sort**: Sorts numbers by processing individual digits from least to most significant.
   - **Counting Sort**: Counts the occurrences of each unique element and uses this information to sort the array.
   - **Shell Sort**: Generalization of insertion sort that allows the exchange of far-apart elements.
   - **Bucket Sort**: Divides the elements into several buckets, sorts them individually, and then merges them.

### 3. **Graph Algorithms**
   - **Breadth-First Search (BFS)**: Explores the vertices of a graph level by level (wide exploration).
   - **Depth-First Search (DFS)**: Explores as far as possible along a branch before backtracking (deep exploration).
   - **Dijkstra’s Algorithm**: Finds the shortest path from a starting vertex to all other vertices in a weighted graph.
   - **Bellman-Ford Algorithm**: Calculates the shortest path in a graph, allowing negative weight edges.
   - **Floyd-Warshall Algorithm**: Finds all pairs shortest paths in a graph.
   - **A* Search Algorithm**: An informed search algorithm that uses heuristics to find the shortest path efficiently.
   - **Prim’s Algorithm**: Finds the Minimum Spanning Tree (MST) of a graph using a greedy approach.
   - **Kruskal’s Algorithm**: Finds the Minimum Spanning Tree by sorting edges and adding them to the MST.
   - **Topological Sort**: Linear ordering of vertices in a Directed Acyclic Graph (DAG).
   - **Tarjan's Algorithm**: Finds strongly connected components in a directed graph.
   - **Kahn's Algorithm**: Another algorithm for topological sorting of a DAG.
   - **Johnson’s Algorithm**: Finds shortest paths between all pairs of vertices in a sparse graph.

### 4. **Dynamic Programming Algorithms**
   - **Fibonacci Sequence (Memoization/Tabulation)**
   - **Knapsack Problem (0/1 and Fractional)**: Maximizes the value in a knapsack of limited capacity.
   - **Longest Common Subsequence (LCS)**
   - **Longest Increasing Subsequence (LIS)**
   - **Matrix Chain Multiplication**
   - **Edit Distance** (Levenshtein distance)
   - **Coin Change Problem**: Minimum number of coins that sum up to a given amount.
   - **Rod Cutting Problem**
   - **Subset Sum Problem**
   - **Optimal Binary Search Tree (OBST)**

### 5. **Greedy Algorithms**
   - **Activity Selection Problem**: Selects the maximum number of activities that don't overlap.
   - **Huffman Coding**: A greedy algorithm for lossless data compression.
   - **Greedy Coloring**: Assigns colors to vertices of a graph using the fewest colors possible.
   - **Fractional Knapsack Problem**
   - **Job Sequencing Problem**
   - **Kruskal’s and Prim’s Algorithms** (Minimum Spanning Tree)
   - **Dijkstra’s Algorithm** (Shortest Path in a graph)

### 6. **Divide and Conquer Algorithms**
   - **Merge Sort**
   - **Quick Sort**
   - **Binary Search**
   - **Strassen’s Matrix Multiplication**: More efficient matrix multiplication than standard algorithms.
   - **Closest Pair of Points**
   - **Karatsuba Algorithm**: Efficient algorithm for multiplying large numbers.

### 7. **Backtracking Algorithms**
   - **N-Queens Problem**
   - **Sudoku Solver**
   - **Hamiltonian Path Problem**
   - **Knight’s Tour Problem**
   - **Subset Sum Problem**
   - **Graph Coloring**
   - **Crossword Puzzle Solver**

### 8. **String Algorithms**
   - **Knuth-Morris-Pratt (KMP) Algorithm**: Efficient pattern matching algorithm.
   - **Rabin-Karp Algorithm**: Uses hashing to find patterns in a string.
   - **Z Algorithm**: Finds occurrences of a pattern in a string.
   - **Boyer-Moore Algorithm**: Another pattern matching algorithm using character mismatches to skip sections.
   - **Trie (Prefix Tree)**: Efficient data structure for string searching and sorting.
   - **Aho-Corasick Algorithm**: Multi-pattern string searching.
   - **Levenshtein Distance (Edit Distance)**: Measures how different two strings are.
   - **Suffix Tree/Array**: Used for efficient pattern matching and other string manipulations.

### 9. **Mathematical Algorithms**
   - **Euclidean Algorithm**: Finds the greatest common divisor (GCD) of two numbers.
   - **Sieve of Eratosthenes**: Finds all prime numbers up to a given limit.
   - **Fast Exponentiation**: Efficiently computes large powers of a number.
   - **Modular Exponentiation**: Computes powers modulo a number.
   - **Karatsuba Multiplication**: Fast multiplication algorithm for large numbers.
   - **Chinese Remainder Theorem**: Solves systems of simultaneous congruences.
   - **Matrix Exponentiation**: Used to compute nth Fibonacci number in logarithmic time.
   - **Gaussian Elimination**: Solves systems of linear equations.
   - **Greatest Common Divisor (GCD)**

### 10. **Miscellaneous Algorithms**
   - **Reservoir Sampling**: A random sampling algorithm for large or unknown datasets.
   - **Fisher-Yates Shuffle**: Randomly shuffles an array.
   - **Union-Find (Disjoint Set Union)**: Efficient data structure for tracking disjoint sets.
   - **Flood Fill Algorithm**: Fills a connected region with a color (used in graphics, games).
   - **Bit Manipulation Algorithms**: Includes XOR swaps, counting set bits, and bit masking.

### 11. **Approximation Algorithms**
   - **Traveling Salesman Problem (TSP) Approximation**
   - **Vertex Cover Approximation**
   - **Set Cover Problem Approximation**
   - **Max-Cut Problem Approximation**

### 12. **Machine Learning Algorithms**
   - **Linear Regression**
   - **Logistic Regression**
   - **Decision Trees**
   - **K-Nearest Neighbors (KNN)**
   - **K-Means Clustering**
   - **Support Vector Machines (SVM)**
   - **Random Forests**
   - **Neural Networks (NN)**
   - **Gradient Descent**: Optimization algorithm for machine learning.
   - **Backpropagation**: Algorithm used to train neural networks.

This list encompasses a wide variety of algorithms used in computer science, data structures, mathematics, and machine learning. Let me know if you'd like details or code examples for any specific algorithm!

Here’s an overview of key **Data Structures** and **Algorithms** in **C++**, along with simple implementations.

## 1. **Basic Data Structures**

#### a. **Array**

```cpp
#include <iostream>
using namespace std;

int main() {
    // Declaring an array
    int arr[] = {1, 2, 3, 4, 5};

    // Accessing elements
    cout << "Element at index 0: " << arr[0] << endl;

    // Modifying an element
    arr[2] = 10;

    // Appending an element (using vector for dynamic array)
    vector<int> vec = {1, 2, 3, 4, 5};
    vec.push_back(6);

    // Deleting an element
    vec.erase(vec.begin() + 1);  // Erasing element at index 1

    return 0;
}
```

#### b. **Linked List**

```cpp
#include <iostream>
using namespace std;

// Create a Class with contains node (data and link)
class Node {                
public:
    int data;
    Node* next;

    Node(int val) {
        data = val;
        next = nullptr;
    }
};

class LinkedList {
public:
    Node* head;

    LinkedList() {
        head = nullptr;
    }

    void insertAtEnd(int val) {
        Node* newNode = new Node(val);
        if (!head) {
            head = newNode;
            return;
        }
        Node* temp = head;
        while (temp->next) {
            temp = temp->next;
        }
        temp->next = newNode;
    }

    void display() {
        Node* temp = head;
        while (temp) {
            cout << temp->data << " -> ";
            temp = temp->next;
        }
        cout << "NULL" << endl;
    }
};

int main() {
    LinkedList list;
    list.insertAtEnd(1);
    list.insertAtEnd(2);
    list.insertAtEnd(3);
    list.display();
    return 0;
}
```

#### c. **Stack**
A stack is a data structure that follows the **Last In First Out (LIFO)** principle.

```cpp
#include <iostream>
#include <stack>
using namespace std;

int main() {
    stack<int> s;

    // Push elements
    s.push(10);
    s.push(20);
    s.push(30);

    // Access the top element
    cout << "Top element: " << s.top() << endl;

    // Pop elements
    s.pop();
    cout << "After pop, top element: " << s.top() << endl;

    return 0;
}
```

#### d. **Queue**
A queue follows the **First In First Out (FIFO)** principle.

```cpp
#include <iostream>
#include <queue>
using namespace std;

int main() {
    queue<int> q;

    // Enqueue elements
    q.push(10);
    q.push(20);
    q.push(30);

    // Access front element
    cout << "Front element: " << q.front() << endl;

    // Dequeue element
    q.pop();
    cout << "After pop, front element: " << q.front() << endl;

    return 0;
}
```

#### e. **Binary Tree**
A tree is a hierarchical data structure with nodes, and each node has zero or more children.

```cpp
#include <iostream>
using namespace std;

class Node {
public:
    int data;
    Node* left;
    Node* right;

    Node(int val) {
        data = val;
        left = nullptr;
        right = nullptr;
    }
};

void inOrder(Node* root) {
    if (root == nullptr) {
        return;
    }
    inOrder(root->left);
    cout << root->data << " ";
    inOrder(root->right);
}

int main() {
    Node* root = new Node(1);
    root->left = new Node(2);
    root->right = new Node(3);
    root->left->left = new Node(4);
    root->left->right = new Node(5);

    cout << "InOrder Traversal: ";
    inOrder(root);

    return 0;
}
```

## 2. **Common Algorithms**

#### a. **Binary Search**

```cpp
#include <iostream>
using namespace std;

int binarySearch(int arr[], int n, int key) {
    int low = 0, high = n - 1;

    while (low <= high) {
        int mid = (low + high) / 2;
        if (arr[mid] == key) {
            return mid;
        } else if (arr[mid] < key) {
            low = mid + 1;
        } else {
            high = mid - 1;
        }
    }
    return -1;
}

int main() {
    int arr[] = {1, 2, 3, 4, 5};
    int n = sizeof(arr) / sizeof(arr[0]);
    int key = 3;
    int result = binarySearch(arr, n, key);

    if (result != -1) {
        cout << "Element found at index " << result << endl;
    } else {
        cout << "Element not found" << endl;
    }

    return 0;
}
```

#### b. **Bubble Sort**

```cpp
#include <iostream>
using namespace std;

void bubbleSort(int arr[], int n) {
    for (int i = 0; i < n - 1; i++) {
        for (int j = 0; j < n - i - 1; j++) {
            if (arr[j] > arr[j + 1]) {
                swap(arr[j], arr[j + 1]);
            }
        }
    }
}

int main() {
    int arr[] = {5, 1, 4, 2, 8};
    int n = sizeof(arr) / sizeof(arr[0]);

    bubbleSort(arr, n);

    cout << "Sorted array: ";
    for (int i = 0; i < n; i++) {
        cout << arr[i] << " ";
    }

    return 0;
}
```

#### c. **Depth-First Search (DFS)** (for Graph)

```cpp
#include <iostream>
#include <vector>
using namespace std;

void DFSUtil(int v, vector<bool>& visited, vector<int> adj[]) {
    visited[v] = true;
    cout << v << " ";

    for (auto i : adj[v]) {
        if (!visited[i]) {
            DFSUtil(i, visited, adj);
        }
    }
}

void DFS(int V, vector<int> adj[]) {
    vector<bool> visited(V, false);

    for (int i = 0; i < V; i++) {
        if (!visited[i]) {
            DFSUtil(i, visited, adj);
        }
    }
}

int main() {
    int V = 5;
    vector<int> adj[V];

    adj[0].push_back(1);
    adj[0].push_back(2);
    adj[1].push_back(2);
    adj[2].push_back(0);
    adj[2].push_back(3);
    adj[3].push_back(3);

    cout << "Depth First Traversal: ";
    DFS(V, adj);

    return 0;
}
```

#### d. **Breadth-First Search (BFS)** (for Graph)

```cpp
#include <iostream>
#include <vector>
#include <queue>
using namespace std;

void BFS(int V, vector<int> adj[], int start) {
    vector<bool> visited(V, false);
    queue<int> q;

    visited[start] = true;
    q.push(start);

    while (!q.empty()) {
        int v = q.front();
        cout << v << " ";
        q.pop();

        for (auto i : adj[v]) {
            if (!visited[i]) {
                visited[i] = true;
                q.push(i);
            }
        }
    }
}

int main() {
    int V = 5;
    vector<int> adj[V];

    adj[0].push_back(1);
    adj[0].push_back(2);
    adj[1].push_back(2);
    adj[2].push_back(0);
    adj[2].push_back(3);
    adj[3].push_back(3);

    cout << "Breadth First Traversal: ";
    BFS(V, adj, 2);

    return 0;
}
```

These implementations cover basic data structures and algorithms in C++. Let me know if you need more advanced topics!
