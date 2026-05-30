# Sharding

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Estimated Time | 12-18 Hours |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | Partitioning |

---

## Learning Objectives

- Understand horizontal data scaling
- Learn how large systems distribute data
- Understand sharding tradeoffs

---

# Sharding Fundamentals

Subtopics:
- What is Sharding?
- Why Sharding Exists
- Horizontal Scaling

Resources:

Primary:
- DDIA

Interview Questions:
- What is sharding?
- Why do systems shard databases?

---

# Shard Keys

Subtopics:
- User ID
- Geographic Sharding
- Tenant ID
- Hash-Based Keys

Interview Questions:
- What makes a good shard key?

---

# Routing

Subtopics:
- Client Routing
- Proxy Routing
- Directory-Based Routing

Interview Questions:
- How does a request find the correct shard?

---

# Rebalancing

Subtopics:
- Adding New Shards
- Data Migration
- Repartitioning

Interview Questions:
- What happens when you add a new shard?

---

# Challenges

Subtopics:
- Cross-Shard Queries
- Cross-Shard Joins
- Cross-Shard Transactions

Interview Questions:
- Why are joins difficult in sharded systems?

---

# Most Important Topics

- Shard Keys
- Routing
- Rebalancing
- Cross-Shard Queries
