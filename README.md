# 📡 Link‑State Routing Lab

A multi‑threaded C program that simulates link‑state routing over N nodes. It uses UDP sockets to exchange dynamic link‑cost updates, pthreads for concurrent receive/update and Dijkstra’s shortest‑path computation, and a mutex‑protected cost matrix.

---

## 🚀 Features

- 📨 UDP-based link-cost broadcasts  
- 🧵 Concurrent threads for receive and compute  
- 🔒 Mutex-protected shared cost matrix  
- 🛣 Dijkstra’s algorithm to compute shortest paths  
- 🔄 Runtime link-cost changes & convergence visualization  

---

## 🛠 Build

```bash
make

