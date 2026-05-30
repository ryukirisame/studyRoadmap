# Uber

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Difficulty | Hard |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | Distributed Systems, Geospatial Systems, Messaging |

---

## Functional Requirements

- Rider Requests Ride
- Driver Accepts Ride
- Real-Time Driver Tracking
- Fare Estimation
- Trip History
- Payments

---

## Non-Functional Requirements

- Real-Time Updates
- Low Latency Matching
- High Availability
- Global Scalability

---

## Capacity Estimation

Subtopics:
- Active Riders
- Active Drivers
- Location Updates Per Second
- Trip Volume

---

## High Level Design

Subtopics:
- Rider Service
- Driver Service
- Matching Service
- Trip Service
- Payment Service

---

## Core Components

Subtopics:
- Location Service
- Matching Engine
- Pricing Engine

---

## Data Model

Subtopics:
- Driver
- Rider
- Trip
- Location

---

## Driver Matching

Subtopics:
- Nearby Driver Discovery
- Driver Ranking
- Assignment Logic

Interview Questions:
- How do you find nearby drivers efficiently?

---

## Geospatial Indexing

Subtopics:
- Geohash
- QuadTree
- Spatial Partitioning

Interview Questions:
- Why use Geohashes?

---

## Scaling Strategy

Subtopics:
- Regional Clusters
- Location Sharding
- Event Streaming

---

## Reliability Considerations

Subtopics:
- Driver Disconnects
- Retry Mechanisms
- Regional Failover

---

## Tradeoffs

Subtopics:
- Matching Accuracy vs Latency
- Freshness vs Scalability

---

## Deep Dive Topics

- Geohash
- Matching Algorithms
- Dynamic Pricing
