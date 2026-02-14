---
title: "Sharded Distributed Banking System"
excerpt: "A Go-based sharded transactional platform using Multi-Paxos and Two-Phase Commit, sustaining 1000-1200 TPS."
header:
  teaser: "500x300.png"
collection: portfolio
---

Built a distributed banking platform in Go with shard-aware transaction routing, consensus-backed replication, and fault-tolerant coordination.

Key points:
- Implemented Multi-Paxos for replica consistency.
- Added Two-Phase Commit for cross-shard transactions.
- Used BoltDB for persistent storage and recovery.
- Supported dynamic shard rebalancing under changing load.

[View project on GitHub](https://github.com/AshrayShetty4/CSE535-2PC-Banking-System)
