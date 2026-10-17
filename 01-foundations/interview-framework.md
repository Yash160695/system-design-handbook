# Four-Step Design Interview Framework

> Original educational notes inspired by topics covered in *System Design Interview – An Insider’s Guide* Volumes 1 and 2 (Alex Xu; Volume 2 also credits Sahn Lam). These are independent explanations and exercises, **not copied book chapters or diagrams**.

## Core Idea

Clarify requirements, propose high-level design, deep dive into bottlenecks, and wrap up with trade-offs and validation.

## Architecture and Trade-offs

Ask for latency, availability, consistency, data retention and security constraints before choosing technology. Avoid inventing scale figures.

## Design Checklist

1. Clarify functional and non-functional requirements.
2. Identify critical data entities, APIs and data flow.
3. State scale estimates and assumptions.
4. Explain bottlenecks, failures, security and observability.
5. Compare alternatives and justify the selected design.

## Practice Exercise

Practice a 40-minute interview: 8 minutes requirements, 12 minutes HLD, 15 minutes deep dive, 5 minutes trade-offs.

## Senior-Level Interview Questions

- Which failure modes would break this design first?
- What would you measure to validate its scalability?
- Which consistency and latency guarantees can it actually provide?
- How would you migrate an existing production system safely?

## Further Study

Add an original architecture diagram, capacity estimate and runnable experiment.
