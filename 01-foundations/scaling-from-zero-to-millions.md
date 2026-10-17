# Scaling from Zero to Millions

> Original educational notes inspired by topics covered in *System Design Interview – An Insider’s Guide* Volumes 1 and 2 (Alex Xu; Volume 2 also credits Sahn Lam). These are independent explanations and exercises, **not copied book chapters or diagrams**.

## Core Idea

Start with a single service and database; add load balancing, stateless replicas, caching, database read replicas, CDN and partitioning only as bottlenecks emerge.

## Architecture and Trade-offs

A single server is simple but a single failure domain. Horizontal scale improves capacity but requires externalized state. Read replicas improve reads but can lag. CDN helps static content, not personalized writes.

## Design Checklist

1. Clarify functional and non-functional requirements.
2. Identify critical data entities, APIs and data flow.
3. State scale estimates and assumptions.
4. Explain bottlenecks, failures, security and observability.
5. Compare alternatives and justify the selected design.

## Practice Exercise

Sketch a migration from 100 daily users to 1 million daily users. Identify the metric that triggers each change.

## Senior-Level Interview Questions

- Which failure modes would break this design first?
- What would you measure to validate its scalability?
- Which consistency and latency guarantees can it actually provide?
- How would you migrate an existing production system safely?

## Further Study

Add an original architecture diagram, capacity estimate and runnable experiment.
