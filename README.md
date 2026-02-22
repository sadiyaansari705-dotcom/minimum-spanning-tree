Prim’s Algorithm in C (Minimum Spanning Tree)

This project implements Prim’s Algorithm to find the Minimum Spanning Tree (MST) of a weighted undirected graph using:

✅ Adjacency Matrix

✅ Greedy Approach

✅ Key Array

✅ MST Set Array

🧾 Program Description

The program:

Represents a weighted undirected graph using a 4 × 4 adjacency matrix

Uses INF = 9999 to represent infinity

Selects the minimum weight edge at each step

Builds the Minimum Spanning Tree (MST)

Prints the edges included in the MST along with their weights

🧠 Concepts Used

Graph Data Structure

Weighted Undirected Graph

Minimum Spanning Tree (MST)

Greedy Algorithm

Adjacency Matrix

Arrays

🔄 How Prim’s Algorithm Works

Initialize all key values as infinite (INF).

Start from vertex 0 (key = 0).

Pick the vertex with the minimum key value that is not yet included in MST.

Update key values of adjacent vertices.

Repeat until all vertices are included in MST.

📊 Graph Representation (Adjacency Matrix)
     0  1  2  3
0  [ 0  2  0  6 ]
1  [ 2  0  3  8 ]
2  [ 0  3  0  0 ]
3  [ 6  8  0  0 ]

This is a weighted undirected graph.

📤 Sample Output
Edge   Weight
0 - 1    2
1 - 2    3
0 - 3    6

These edges form the Minimum Spanning Tree (MST).

🚀 How to Run
🔹 Compile the Program
gcc main.c -o prim
🔹 Run the Program
./prim

(For Windows)

prim.exe
📂 Project Structure
📁 prim-mst
 ├── main.c
 └── README.md
⚠️ Limitations

Number of vertices is fixed (#define V 4)

Uses adjacency matrix (less efficient for large graphs)

Does not calculate total MST weight separately

No dynamic input from user

🔧 Possible Improvements

Take number of vertices as user input

Print total weight of MST

Use adjacency list representation

Implement using Min Heap (Priority Queue) for better efficiency

Compare with Kruskal’s Algorithm

👨‍💻 Author


B.Tech Student

If you want, I can also provide:

⭐ Kruskal’s Algorithm version

⭐ Version with total MST cost

⭐ Lab viva explanation notes

⭐ Comparison: Prim vs Kruskal
