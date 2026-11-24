# DAA.PRACTICAL_1: Implementation and Time analysis of sorting algorithms. Bubble sort, Selection sort,Insertion sort, Merge sort and Quicksort.

# Summary:-
This practical implements and compares five fundamental sorting algorithms: Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort. Each algorithm sorts the input array, measures the execution time, and demonstrates its working along with its time complexity. The program helps in understanding the efficiency, performance, and practical applications of different sorting techniques.

# Conclusion:-
The experiment shows that different sorting algorithms have different performance characteristics. Bubble Sort, Selection Sort, and Insertion Sort are simple to implement but are less efficient for large datasets due to their O(n²) time complexity. Merge Sort and Quick Sort are more efficient, with an average time complexity of O(n log n), making them suitable for larger inputs. The choice of a sorting algorithm depends on factors such as input size, data characteristics, memory requirements, and application needs.


# DAA.PRACTICAL_2: Implementation and Time analysis of linear and binary search algorithm.

# Summary:-
This program demonstrates the implementation of Linear Search and Binary Search algorithms in Python. It accepts user input, searches for a given element, measures the execution time, and displays the result along with the time complexity. Linear Search checks each element one by one, whereas Binary Search works on a sorted array by repeatedly dividing the search space into two halves, making it more efficient.

# Conclusion:-
The experiment shows that Binary Search is significantly faster than Linear Search for large sorted datasets, with a time complexity of O(log n) compared to O(n) for Linear Search. However, Binary Search requires the array to be sorted, while Linear Search can be applied to both sorted and unsorted data. Therefore, the choice of algorithm depends on the nature of the input data and the application's requirements.


# DAA.PRACTICAL_3: Implementation of max-heap sort algorithm.

# Summary:-
This program implements the Heap Sort algorithm in Python. It builds a Max Heap from the input array and repeatedly extracts the largest element to produce the sorted array in ascending order. The program also measures the execution time in microseconds and displays the best, average, and worst-case time complexities.

# Conclusion:-
The experiment demonstrates that Heap Sort is an efficient comparison-based sorting algorithm with a consistent time complexity of O(n log n) in the best, average, and worst cases. It provides reliable performance regardless of the input order and is suitable for sorting large datasets. Although it is not a stable sorting algorithm, Heap Sort is preferred when guaranteed O(n log n) performance and constant auxiliary space (O(1)) are required.


# DAA.PRACTICAL_4: Implementation and Time analysis of factorial program using iterative and recursive method.

# summary:-
The factorial program was implemented using both iterative and recursive methods. The iterative method uses a loop, while the recursive method calls itself until it reaches the base condition. The execution time, time complexity, and space complexity of both methods were compared.

# Conclusion:-
both methods take O(n) time. The recursive method uses O(n) space because it stores function calls. The iterative method uses O(1) space, so it uses less memory. Therefore, the iterative method is more memory-efficient, while the recursive method is simpler to understand.


# DAA.PRACTICAL_5: Implementation of a knapsack problem using dynamic programming.

# Summary:-
This program solves the 0/1 Knapsack Problem using Dynamic Programming. It finds the maximum value of items that can fit within the given capacity.

# Conclusion:-
Dynamic Programming avoids repeated calculations and helps find the maximum possible value efficiently.


# DAA.PRACTICAL_6: Implementation of chain matrix multiplication using dynamic programming.

# Summary:-
This program finds the best way to multiply matrices with the minimum number of operations using Dynamic Programming.

# Conclusion:-
Dynamic Programming helps reduce repeated calculations and gives the minimum multiplication cost efficiently.


# DAA.PRACTICAL_7: Implementation of making a change problem using dynamic programming.

# Summary:-
The Making Change Problem was solved using Dynamic Programming. The program finds the minimum number of coins needed to make a given amount.

# Conclusion:-
Dynamic Programming helps solve the problem efficiently by storing previous results. The program has O(n × amount) time complexity and O(amount) space complexity.


# DAA.PRACTICAL_8: Implementation of Graph and Searching(DFS and BFS).

# Summary:-
In this program, we implemented a graph using an adjacency list and performed two searching methods: DFS and BFS. DFS searches by going deep into one path before coming back, while BFS searches the graph level by level using a queue.

# Conclusion:-
We successfully implemented Graph, DFS, and BFS in Python. DFS is useful for exploring paths deeply, while BFS is useful for searching nodes level by level. Both methods help in efficiently exploring and searching graphs.


# DAA.PRACTICAL_9: Implement prim’s algorithm.

# Summary:
In this practical, I implemented Prim's Algorithm to find the Minimum Spanning Tree of a graph. It selects the smallest edge one by one and connects all vertices without forming a cycle.

# Conclusion:
From this practical, I learned how Prim's Algorithm works and how to find the minimum cost to connect all vertices in a graph.


# DAA.PRACTICAL_10: Implement Kruskal’s algorithm.

# Summary:
In this practical, we implemented Kruskal's Algorithm to find the Minimum Spanning Tree of a graph. The algorithm selects the edges with the smallest weights without forming a cycle. It continues until all vertices are connected.

# Conclusion:
From this practical, I learned how Kruskal's Algorithm works and how to find the minimum cost of connecting all vertices in a graph.


# DAA.PRACTICAL_11: Write a program for Floyd-Warshal algorithm.

# Summary:
In this practical, we implemented the Floyd-Warshall Algorithm to find the shortest distances between all pairs of vertices in a graph. It checks different possible paths and selects the shortest distance.

# Conclusion:
From this practical, I learned how to find the shortest paths between all pairs of vertices using the Floyd-Warshall Algorithm.


# DAA.PRACTICAL_12:Write a program for travelling salesman problem.

# Summary:
In this practical, I implemented the Travelling Salesman Problem using Python. The program checks different possible routes, calculates their total costs, and finds the shortest route to visit all cities and return to the starting city.

# Conclusion:
From this practical, I learned how to find the shortest possible route between cities with minimum travel cost using the Travelling Salesman Problem.
