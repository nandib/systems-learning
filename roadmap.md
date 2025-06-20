# Expanded Roadmap: Distributed Systems + Rust + C

## 📅 Phase 1: Foundations

### Week 1–2: Rust & C - Language Basics
- 📘 Rust Book Ch. 1–6
- 📘 C Pointers, memory, structs
- 🛠️ Project: Ownership visualizer + malloc simulator

### Week 3: Tooling + Setup
- Install: Rust, C, valgrind, perf, tokio-console
- Explore: `gdb`, `strace`, `lsof`, cargo tools
- Setup GitHub repo for tracking

### Week 4–5: OS Concepts + Processes
- 📘 OSTEP Ch. 1–9, 28–34
- 🛠️ Rust: `/proc` parser, file monitor
- 🛠️ C: `fork()`, `wait()`, signal handler

### Week 6: BUFFER WEEK (Catch-up, review, try rustlings)

---

## 🌐 Phase 2: Networking & Protocols

### Week 7–8: Networking Basics
- 📘 Kurose & Ross Ch. 2–4, CS144 lab ref
- 🛠️ Rust: Build async HTTP server using `tokio`
- 🛠️ C: TCP socket echo server with `select()`

### Week 9: BUFFER WEEK

---

## 📡 Phase 3: Distributed Systems Core

### Week 10–11: Replication & Quorum Systems
- 📄 Dynamo Paper (2007)
- 📘 DDIA Ch. 5, Petrov Ch. 8
- 🔗 PingCAP replication section
- 🛠️ Implement majority quorum reader

### Week 12–13: Consensus - Raft
- 📄 Raft Paper + MIT 6.824 Lecture
- 📘 DDIA Ch. 9
- 🛠️ Project: Raft log replicator in Rust

### Week 14: BUFFER WEEK

---

## 🔄 Phase 4: Transactions & Concurrency

### Week 15–16: Concurrency Control
- 📄 Calvin, Spanner papers
- 📘 DDIA Ch. 7–8, Petrov Ch. 6–7
- 🛠️ Simulate serializability + optimistic tx

### Week 17: BUFFER WEEK

---

## 🧱 Phase 5: Database Internals

### Week 18–19: Storage Engines (B-Tree, LSM)
- 📘 Petrov Ch. 3–4
- 📄 RocksDB blog + TiKV docs
- 🛠️ Project: LSM tree compactor

### Week 20–21: SQL Layer + Planning
- 📘 Petrov Ch. 10, DDIA Ch. 4
- 🧠 EatonPhil: SQL parser blog
- 🔗 PingCAP SQL Execution

### Week 22: BUFFER WEEK

---

## 🚀 Phase 6: Real Systems

### Week 23–24: Aurora, DynamoDB Deep Dive
- 📄 Aurora Paper (SIGMOD), DynamoDB paper
- 📄 FoundationDB + Amazon S2N blog
- 🔬 Explore failover, fencing, replication model

### Week 25–26: Project Wrap-up + Capstone Idea
- Build a distributed KV or LSM-based system
- Write a postmortem, add profiling
