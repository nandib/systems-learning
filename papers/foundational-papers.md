# 📚 Foundational Papers in Distributed Systems

This repository is a curated list of foundational research papers in distributed systems. These works cover the fundamental theories, algorithms, architectures, and trade-offs that underpin modern distributed infrastructure.

---

## 🧠 Core Concepts & Theory

- **[Time, Clocks, and the Ordering of Events in a Distributed System](https://lamport.azurewebsites.net/pubs/time-clocks.pdf)**  
  *Leslie Lamport, 1978*  
  Introduces logical clocks and the "happens-before" relation.

- **[The Byzantine Generals Problem](https://lamport.azurewebsites.net/pubs/byz.pdf)**  
  *Lamport, Shostak, Pease, 1982*  
  Defines the Byzantine fault tolerance problem.

- **[Impossibility of Distributed Consensus with One Faulty Process (FLP)](https://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf)**  
  *Fischer, Lynch, Paterson, 1985*  
  Proves the impossibility of consensus in asynchronous systems with one faulty process.

- **[Viewstamped Replication](https://pmg.csail.mit.edu/papers/vr-revisited.pdf)**  
  *Oki & Liskov, 1988 (Revisited 2011)*  
  A leader-based replication protocol predating Paxos.

---

## ⚙️ Consensus Algorithms

- **[Paxos Made Simple](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf)**  
  *Lamport, 2001*  
  A human-readable explanation of the Paxos consensus protocol.

- **[In Search of an Understandable Consensus Algorithm (Raft)](https://raft.github.io/raft.pdf)**  
  *Ongaro & Ousterhout, 2014*  
  Raft is a consensus algorithm designed for understandability and practical use.

---

## 🔁 Transactions & Replication

- **[The Transaction Concept: Virtues and Limitations](https://research.microsoft.com/en-us/um/people/gray/papers/theTransactionConcept.pdf)**  
  *Jim Gray, 1981*  
  Discusses transactions and ACID semantics.

- **[Epidemic Algorithms for Replicated Database Maintenance](https://cs-www.cs.yale.edu/homes/yu-minlan/teach/cs425/papers/epidemic.pdf)**  
  *Demers et al., 1987*  
  Introduces gossip-based protocols.

- **[Dynamo: Amazon’s Highly Available Key-Value Store](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)**  
  *DeCandia et al., 2007*  
  A highly available, eventually consistent distributed store.

---

## 📜 CAP, Consistency, and Trade-offs

- **[CAP Theorem Formalization](https://people.csail.mit.edu/lynch/pubs/CAP.pdf)**  
  *Gilbert & Lynch, 2002*  
  The formal proof that you can't have Consistency, Availability, and Partition tolerance simultaneously.

- **[Eventually Consistent](https://www.allthingsdistributed.com/2008/12/eventually_consistent.html)**  
  *Werner Vogels, 2008*  
  A widely cited blog post explaining eventual consistency.

- **[Consistency, Availability, and Convergence](https://www.bailis.org/papers/hat2014.pdf)**  
  *Bailis & Ghodsi, 2013*  
  Clarifies CAP and introduces the idea of convergent consistency.

---

## 🏗️ Distributed Infrastructure & Storage

- **[The Google File System (GFS)](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf)**  
  *Ghemawat, Gobioff, Leung, 2003*  
  A distributed file system optimized for large data workloads.

- **[MapReduce: Simplified Data Processing on Large Clusters](https://research.google.com/archive/mapreduce.html)**  
  *Dean & Ghemawat, 2004*  
  Parallel computation framework for massive data.

- **[Bigtable: A Distributed Storage System for Structured Data](https://research.google.com/archive/bigtable-osdi06.pdf)**  
  *Chang et al., 2006*  
  Column-family store that inspired Cassandra and HBase.

---

## ⛓️ Coordination & Global Consistency

- **[ZooKeeper: Wait-free Coordination](https://www.usenix.org/legacy/event/atc10/tech/full_papers/Hunt.pdf)**  
  *Hunt et al., 2010*  
  A reliable coordination service used in many distributed systems.

- **[Spanner: Google’s Globally-Distributed Database](https://research.google.com/archive/spanner-osdi2012.pdf)**  
  *Corbett et al., 2012*  
  Uses TrueTime to provide external consistency across datacenters.

---

## 🧪 Modern Systems Thinking

- **[FaRM: Fast Remote Memory](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/farm-sosp14.pdf)**  
  *Dragojević et al., 2014*  
  Fast transactions using RDMA and distributed memory.

- **[CALM and its Implications](https://dsf.berkeley.edu/papers/calm-pods.pdf)**  
  *Hellerstein et al., 2011*  
  Describes what logic can be coordinated-free and still consistent.

- **[The Tail at Scale](https://research.google.com/pubs/archive/40801.pdf)**  
  *Dean & Barroso, 2013*  
  Discusses tail latency and system-level implications at Google scale.

---

## 🧪 Blog links of paper listing
- **[Fred Hebert- A Distributed Systems Reading List](https://ferd.ca/a-distributed-systems-reading-list.html)**
- **[Unknown Author - Reading list](https://dancres.github.io/Pages/)**
- **[Papers we love](https://github.com/papers-we-love/papers-we-love)**
- **[MIT -Dist System](https://www.youtube.com/playlist?list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB)**
- **[Awesome-Dist-Systms-github](https://github.com/theanalyst/awesome-distributed-systems#meta-lists)**
- **[Marc Brooker - How to read](https://brooker.co.za/blog/2020/05/25/reading.html)**
- **[Best Papers](https://jeffhuang.com/best_paper_awards/)**
- **[CRDT- Bartosz Sypytkowski](https://www.bartoszsypytkowski.com/)**