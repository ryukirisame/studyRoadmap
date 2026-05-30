# WhatsApp

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Difficulty | Hard |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | Chat Systems, Distributed Systems, Messaging |

---

## Functional Requirements

- One-to-One Messaging
- Group Messaging
- Read Receipts
- Online Presence
- Media Sharing

---

## Non-Functional Requirements

- Real-Time Delivery
- Global Availability
- Low Latency
- High Reliability

---

## Capacity Estimation

Subtopics:
- Concurrent Connections
- Messages Per Second
- Media Storage

---

## High Level Design

Subtopics:
- Gateway Layer
- WebSocket Layer
- Message Service
- Presence Service
- Media Service

---

## Core Components

Subtopics:
- Connection Manager
- Message Queue
- Delivery Service

---

## Data Model

Subtopics:
- Users
- Conversations
- Messages
- Groups

---

## Message Delivery Flow

Subtopics:
- Online Delivery
- Offline Delivery
- Acknowledgements

Interview Questions:
- How does WhatsApp deliver messages reliably?

---

## Scaling Strategy

Subtopics:
- Connection Sharding
- Regional Clusters
- Message Partitioning

---

## Reliability Considerations

Subtopics:
- Offline Users
- Message Retries
- Duplicate Prevention

---

## Security Considerations

Subtopics:
- End-to-End Encryption
- Key Exchange
- Identity Verification

Interview Questions:
- How does end-to-end encryption work?

---

## Tradeoffs

Subtopics:
- Consistency vs Availability
- Storage vs Performance

---

## Deep Dive Topics

- Presence Tracking
- Group Messaging
- Encryption
