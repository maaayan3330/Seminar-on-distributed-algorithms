# 📘 Seminar on Distributed Algorithms
### Port-Numbered (PN) Network Models

## 📄 Overview

This repository contains the seminar presentation **"Distributed Algorithms in the PN Model"**, prepared as part of an academic seminar on distributed computing.

The seminar focuses on **port-numbered networks (PN model)** and presents formal definitions, execution models, and distributed algorithms operating under this framework.


## 🧠 Topics Covered

### 🔹 Distributed Systems – Refresher
- Definition of distributed networks
- Nodes, communication links, and synchronous rounds
- Message passing with local knowledge

### 🔹 The PN (Port-Numbered) Model
- Formal definition of a port-numbered network  
- Ports, involution function, and degree constraints
- Underlying graph representation

### 🔹 Distributed Algorithms in the PN Model
- Distributed graph problems
- Local outputs and node labeling
- State-machine based algorithm definition
- Synchronous execution model

---

## 🎨 Algorithm: 3-Coloring Path Graphs

- Problem definition:
  - Graph family: **Path graphs**
  - Target: **3-coloring**
- Assumes an initial (possibly large) coloring
- Nodes iteratively reduce colors using local neighborhood information
- Uses a minimal missing color function
- **Correctness:** Proper coloring, stabilization, and color bound
- **Runtime:** 𝑂(n) communication rounds

---

## 🔗 Algorithm: Maximal Matching in Bipartite Graphs

- Operates on **2-colored (bipartite) graphs**
- White & Black node roles
- Proposal / Accept message protocol
- Local states: UR, MR, US, MS
- Guarantees:
  - Correct matching encoding
  - Maximality of the matching
- **Runtime:** 𝑂(Δ), where Δ is the maximum degree

---

## ⏱️ Complexity Results

| Problem | Runtime |
|------|------|
| 3-Coloring Paths | O(n) |
| Bipartite Maximal Matching | O(Δ) |

---

## 🎓 Academic Context

- Course / Seminar: **Distributed Algorithms**
- Model: **Port-Numbered Networks**
- Focus: Local computation, symmetry breaking, and round complexity

---

## 📌 Notes

This repository contains **presentation material only**.  
No implementation code is included.

---

<p align="center">
  Prepared for academic use • Distributed Computing Seminar
</p>
