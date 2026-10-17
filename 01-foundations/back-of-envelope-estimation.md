# Back-of-the-Envelope Estimation

> Original educational notes inspired by topics covered in *System Design Interview – An Insider’s Guide* Volumes 1 and 2 (Alex Xu; Volume 2 also credits Sahn Lam). These are independent explanations and exercises, **not copied book chapters or diagrams**.

## Core Idea

Estimate average and peak RPS, storage growth, network bandwidth, memory and cache size from stated assumptions.

## Architecture and Trade-offs

Average RPS = requests per day / 86,400. Storage = events/day × bytes/event × retention days × replication factor. Peak traffic requires an explicit peak multiplier.

## Design Checklist

1. Clarify functional and non-functional requirements.
2. Identify critical data entities, APIs and data flow.
3. State scale estimates and assumptions.
4. Explain bottlenecks, failures, security and observability.
5. Compare alternatives and justify the selected design.

## Practice Exercise

Assume 5 million daily active users, 10 requests/user/day and 5× peak. Estimate peak RPS and document assumptions.

## Senior-Level Interview Questions

- Which failure modes would break this design first?
- What would you measure to validate its scalability?
- Which consistency and latency guarantees can it actually provide?
- How would you migrate an existing production system safely?

## Further Study

Add an original architecture diagram, capacity estimate and runnable experiment.
