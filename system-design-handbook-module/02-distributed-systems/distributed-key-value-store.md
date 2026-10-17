# Distributed Key-Value Store

> Original educational notes inspired by topics covered in *System Design Interview – An Insider’s Guide* Volumes 1 and 2 (Alex Xu; Volume 2 also credits Sahn Lam). These are independent explanations and exercises, **not copied book chapters or diagrams**.

## Core Idea

Design partitioning, replication, read/write quorums, versioning, conflict handling, failure detection and anti-entropy.

## Architecture and Trade-offs

Quorum settings affect latency and availability; sloppy quorums and asynchronous replication may complicate guarantees. Decide whether last-write-wins is acceptable.

## Design Checklist

1. Clarify functional and non-functional requirements.
2. Identify critical data entities, APIs and data flow.
3. State scale estimates and assumptions.
4. Explain bottlenecks, failures, security and observability.
5. Compare alternatives and justify the selected design.

## Practice Exercise

Define GET/PUT semantics under a network partition and show how stale values are reconciled.

## Senior-Level Interview Questions

- Which failure modes would break this design first?
- What would you measure to validate its scalability?
- Which consistency and latency guarantees can it actually provide?
- How would you migrate an existing production system safely?

## Further Study

Add an original architecture diagram, capacity estimate and runnable experiment.
