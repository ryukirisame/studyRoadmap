# URL Shortener

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Difficulty | Easy |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | Databases, Caching, Distributed Systems |

---

## Functional Requirements

- Generate short URLs
- Redirect short URLs
- Support custom aliases
- URL expiration (optional)
- Analytics (optional)

---

## Non-Functional Requirements

- High Availability
- Low Latency Redirects
- Massive Read Traffic
- Horizontal Scalability

---

## Capacity Estimation

Subtopics:
- Write QPS
- Redirect QPS
- Storage Estimation
- Cache Size Estimation

Interview Questions:
- How would you estimate storage requirements?

---

## High Level Design

Subtopics:
- API Layer
- URL Service
- Database
- Cache

Interview Questions:
- What components are required?

---

## Core Components

Subtopics:
- URL Generation Service
- Redirect Service
- Analytics Service

Interview Questions:
- How are short URLs generated?

---

## Data Model

Subtopics:
- URL Mapping
- Metadata
- Expiration

Interview Questions:
- What database schema would you use?

---

## Scaling Strategy

Subtopics:
- Read Scaling
- Database Sharding
- Cache Layer

Interview Questions:
- How do you scale redirects?

---

## Reliability Considerations

Subtopics:
- Replication
- Backups
- Failover

Interview Questions:
- How would you prevent data loss?

---

## Security Considerations

Subtopics:
- Malicious URLs
- Abuse Prevention
- Rate Limiting

Interview Questions:
- How would you prevent abuse?

---

## Tradeoffs

Subtopics:
- Hashing vs Counter IDs
- SQL vs NoSQL

Interview Questions:
- Counter-based IDs vs Hashing?

---

## Deep Dive Topics

- Base62 Encoding
- Cache Design
- Sharding Strategy
