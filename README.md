# ccc_Network-Cable-Optimizer

A simple interactive website that simulates connecting computers with minimum cable cost using Minimum Spanning Tree (MST) algorithms.

Features:
Add computers as nodes by clicking on the canvas.
Move nodes by dragging to try different layouts.
Visualize all possible links between computers.
Run Prim’s Algorithm to generate MST.
Run Kruskal’s Algorithm to generate MST.
Highlight selected MST edges.
Show total cable cost, node count, and MST edge count.
🧠 Algorithms Used
1) Prim’s Algorithm (Greedy)

Builds the MST by starting from one node and repeatedly choosing the cheapest edge that connects a visited node to an unvisited node.

2) Kruskal’s Algorithm (Greedy + Union-Find)

Sorts all edges by weight and adds the smallest valid edges while avoiding cycles, using union-find.

🖥️ How to Run Locally

Because this project is a static website, you can run it directly:

Clone the repository:
git clone <your-repo-url>
cd ccc_Network-Cable-Optimizer
Open index.html in your browser.

Optional (recommended): use a local server:

python3 -m http.server 8000

Then visit http://localhost:8000.

📂 Project Structure
index.html — main app (UI + canvas rendering + MST logic).
README.md — project documentation.
💡 Why This Project Is Impressive
Combines algorithmic problem solving with interactive visualization.
Makes abstract graph theory concepts easy to understand.
Useful as a portfolio project for DSA + frontend fundamentals.
🔮 Possible Improvements
Let users manually add/remove edges.
Add animation for step-by-step MST construction.
Export/import graph layouts.
Support weighted input values instead of distance-only weights.
📜 License

Use freely for learning and personal portfolio projects.
