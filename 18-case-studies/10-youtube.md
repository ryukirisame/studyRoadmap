# YouTube

## Metadata

| Field | Value |
|---------|---------|
| Priority | P0 |
| Difficulty | Hard |
| Interview Frequency | ⭐⭐⭐⭐⭐ |
| Prerequisites | CDN, Distributed Storage, Caching |

---

## Functional Requirements

- Upload Videos
- Stream Videos
- Search Videos
- Recommendations
- Likes and Comments

---

## Non-Functional Requirements

- Massive Storage
- Global Availability
- Low Playback Latency
- High Throughput

---

## Capacity Estimation

Subtopics:
- Upload Volume
- Video Storage
- Streaming Bandwidth
- CDN Traffic

---

## High Level Design

Subtopics:
- Upload Service
- Video Processing Service
- Metadata Service
- Recommendation Service
- CDN

---

## Core Components

Subtopics:
- Video Encoder
- Storage Service
- Streaming Service

---

## Data Model

Subtopics:
- Videos
- Channels
- Comments
- Watch History

---

## Video Upload Pipeline

Subtopics:
- Upload
- Validation
- Encoding
- Storage

Interview Questions:
- What happens after a video upload?

---

## Video Streaming Architecture

Subtopics:
- Chunked Streaming
- Adaptive Bitrate Streaming
- CDN Distribution

Interview Questions:
- Why use CDNs for video delivery?

---

## Scaling Strategy

Subtopics:
- Distributed Storage
- CDN Caching
- Regional Replication

---

## Reliability Considerations

Subtopics:
- Storage Replication
- Processing Failures
- Retry Pipelines

---

## Tradeoffs

Subtopics:
- Storage Cost vs Availability
- Preprocessing vs On-Demand Processing

---

## Deep Dive Topics

- Video Encoding
- Adaptive Streaming
- CDN Architecture
- Recommendation Systems
