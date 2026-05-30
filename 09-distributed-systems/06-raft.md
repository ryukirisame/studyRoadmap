# Raft

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Estimated Time | 12-18 Hours |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | Consensus |

---

## Learning Objectives

- Understand a practical consensus algorithm
- Understand leader election
- Understand replicated logs

---

# Raft Fundamentals

Subtopics:
- Why Raft Exists
- Consensus Simplification
- Fault Tolerance

Resources:

Primary:
- In Search of an Understandable Consensus Algorithm (Raft Paper)
- DDIA

Interview Questions:
- What is Raft?

---

# Node Roles

Subtopics:
- Leader
- Follower
- Candidate

Interview Questions:
- What roles exist in Raft?

---

# Leader Election

Subtopics:
- Election Timeout
- Voting
- Majority Quorum

Interview Questions:
- How is a leader elected?

---

# Log Replication

Subtopics:
- Log Entries
- Commit Index
- Replicated State Machine

Interview Questions:
- How does Raft replicate data?

---

# Safety Guarantees

Subtopics:
- Log Matching
- Leader Completeness

Interview Questions:
- How does Raft prevent split brain?

---

# Real-World Usage

Subtopics:
- etcd
- Consul
- Kubernetes

Interview Questions:
- Why does Kubernetes use etcd?

---

# Most Important Topics

- Leader Election
- Quorum
- Log Replication
- Safety Guarantees
