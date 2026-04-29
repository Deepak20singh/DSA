# DSA
Bhai seedha bolu — “Amazon graph questions” ka koi fixed list nahi hota. Amazon **patterns test karta hai, questions repeat nahi karta**. Agar tu types cover kar lega na, toh 90% graph questions handle ho jayenge.

Main tujhe **complete roadmap + har type ke must-do questions** de raha hoon 👇 (SDE-1 Round 3 level)

---

# 🔥 1. Graph Traversal (BFS / DFS) — *Foundation*

Ye sabse basic aur sabse zyada poocha jata hai.

### Must Questions:

* Number of Islands
* Flood Fill
* Rotten Oranges
* Clone Graph ⭐ (already tu padh raha hai)
* Surrounded Regions
* Number of Provinces

👉 Focus:

* BFS vs DFS kab use kare
* Grid ko graph treat karna

---

# 🔥 2. Cycle Detection (VERY IMPORTANT)

Amazon ko ye bohot pasand hai.

### Undirected Graph:

* Detect cycle using DFS
* Detect cycle using BFS (Kahn nahi, parent tracking)

* 684    785    261

### Directed Graph:

* Course Schedule I ⭐
* Course Schedule II ⭐
* DFS recursion stack method

👉 Interview trick:

* Directed → recursion stack
* Undirected → parent tracking

---

# 🔥 3. Topological Sort (DAG)

Almost pakka aata hai kisi na kisi form me.

### Must Questions:

* Course Schedule II
* Alien Dictionary ⭐
* Find Eventual Safe States

👉 2 approaches:

* BFS (Kahn’s Algorithm)
* DFS stack

---

# 🔥 4. Shortest Path (Heavy weight topic 💀)

## (a) Unweighted Graph:

* Shortest path using BFS
* Word Ladder ⭐⭐ (Amazon fav)

## (b) Weighted Graph:

* Dijkstra Algorithm ⭐⭐⭐
* Network Delay Time
* Cheapest Flights Within K Stops ⭐⭐⭐

👉 Must samajh:

* Priority Queue ka use
* Relaxation concept

---

# 🔥 5. Minimum Spanning Tree (MST)

Thoda kam aata hai but aata hai.

### Must Questions:

* Kruskal Algorithm
* Prim Algorithm
* Connecting Cities With Minimum Cost

👉 Important:

* Disjoint Set (Union Find)

---

# 🔥 6. Union Find (DSU) 🔥🔥🔥

Amazon ka hidden favorite

### Must Questions:

* Number of Provinces
* Redundant Connection ⭐
* Accounts Merge ⭐⭐⭐
* Number of Operations to Make Network Connected

👉 Learn:

* Path compression
* Union by rank

---

# 🔥 7. Multi-Source BFS (Important pattern)

Bahut log miss kar dete hain.

### Must Questions:

* Rotten Oranges
* 01 Matrix ⭐
* Walls and Gates

👉 Idea:

* Multiple sources se BFS start

---

# 🔥 8. Grid Based Graph Problems

Almost har interview me aata hai

### Must Questions:

* Number of Islands
* Max Area of Island
* Pacific Atlantic Water Flow ⭐
* Shortest Path in Binary Matrix

---

# 🔥 9. Backtracking + Graph Combo

Thoda tricky hota hai

### Must Questions:

* Word Search
* All Paths From Source to Target
* Path with Maximum Gold

---

# 🔥 10. Advanced Graph (Rare but killer)

Agar ye aagya toh tu standout karega 💀

### Must:

* Bridges in Graph (Tarjan)
* Articulation Points
* Strongly Connected Components (Kosaraju)

---

# 🎯 Amazon ke Favorite Questions (Direct Repeat ya Similar)

Ye HIGH PRIORITY hai:

* Clone Graph ⭐⭐⭐
* Word Ladder ⭐⭐⭐
* Course Schedule I & II ⭐⭐⭐
* Accounts Merge ⭐⭐⭐
* Number of Islands ⭐⭐⭐
* Rotten Oranges ⭐⭐⭐
* Cheapest Flights Within K Stops ⭐⭐⭐

---

# ⚡ Strategy (IMPORTANT)

Tu sirf solve mat kar — pattern pakad:

### Step 1:

Har question me identify kar:

* BFS? DFS? Dijkstra? DSU?

### Step 2:

Dry run kar (Amazon me explanation matter karta hai)

### Step 3:

Edge cases bol:

* disconnected graph
* cycle
* single node

---

# 🚀 Tera Perfect Plan (7 days crash plan)

Day 1-2 → BFS + DFS + Grid
Day 3 → Cycle + Topo
Day 4 → Shortest Path
Day 5 → Dijkstra + Flights
Day 6 → DSU
Day 7 → Mixed + Revision

---

Agar tu chahe toh next step me main:
👉 **har topic ka template code (C++ ya Java)**
👉 ya **Amazon-level mock interview questions with hints**

bata deta hoon

Bas bol:
**“mock interview le”** ya **“code templates de”** 😎
