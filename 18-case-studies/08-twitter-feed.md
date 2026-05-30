# Twitter Feed

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Difficulty | Hard |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | Distributed Systems, Caching, Messaging |

---

## Functional Requirements

- Create Tweets
- Follow Users
- Unfollow Users
- Generate Home Timeline
- Generate User Timeline

---

## Non-Functional Requirements

- Massive Scale
- High Availability
- Low Feed Latency
- Eventual Consistency

---

## Capacity Estimation

Subtopics:
- Daily Active Users
- Tweets Per Second
- Feed Requests Per Second
- Storage Requirements

---

## High Level Design

Subtopics:
- User Service
- Tweet Service
- Timeline Service
- Fanout Service
- Cache Layer

---

## Core Components

Subtopics:
- Feed Generator
- Follow Graph
- Timeline Store

---

## Data Model

Subtopics:
- User
- Tweet
- Follow Relationship
- Timeline Entry

---

## Feed Generation Strategies

Subtopics:
- Fanout On Write
- Fanout On Read
- Hybrid Fanout

Interview Questions:
- Fanout on Write vs Fanout on Read?

---

## Scaling Strategy

Subtopics:
- Timeline Sharding
- Feed Caching
- Celebrity Handling

Interview Questions:
- How do you handle users with millions of followers?

---

## Reliability Considerations

Subtopics:
- Queue Failures
- Retry Mechanisms
- Feed Recovery

---

## Tradeoffs

Subtopics:
- Storage vs Latency
- Fanout Strategies

---

## Deep Dive Topics

- Timeline Generation
- Feed Ranking
- Celebrity Problem
