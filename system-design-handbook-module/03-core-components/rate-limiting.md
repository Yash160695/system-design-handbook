# Rate Limiting

> Original educational notes inspired by topics covered in *System Design Interview – An Insider’s Guide* Volumes 1 and 2 (Alex Xu; Volume 2 also credits Sahn Lam). These are independent explanations and exercises, **not copied book chapters or diagrams**.

## Core Idea

Compare fixed window, sliding window log, sliding window counter, token bucket and leaky bucket algorithms.

## Architecture and Trade-offs

Token bucket permits bursts; sliding logs are precise but memory-intensive; fixed windows can permit boundary bursts. Distributed enforcement needs atomic state and failure policy.

## Design Checklist

1. Clarify functional and non-functional requirements.
2. Identify critical data entities, APIs and data flow.
3. State scale estimates and assumptions.
4. Explain bottlenecks, failures, security and observability.
5. Compare alternatives and justify the selected design.

## Practice Exercise

Design a Redis-backed per-user rate limiter with an atomic update and fallback policy.

## Senior-Level Interview Questions

- Which failure modes would break this design first?
- What would you measure to validate its scalability?
- Which consistency and latency guarantees can it actually provide?
- How would you migrate an existing production system safely?

## Further Study

Add an original architecture diagram, capacity estimate and runnable experiment.
