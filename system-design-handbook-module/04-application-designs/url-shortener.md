# URL Shortener

> Original educational notes inspired by topics covered in *System Design Interview – An Insider’s Guide* Volumes 1 and 2 (Alex Xu; Volume 2 also credits Sahn Lam). These are independent explanations and exercises, **not copied book chapters or diagrams**.

## Core Idea

Map short codes to destinations; choose code generation, indexing, caching, redirect semantics and abuse prevention.

## Architecture and Trade-offs

Random codes require collision handling; sequential IDs may reveal usage. Analytics should be off the redirect critical path.

## Design Checklist

1. Clarify functional and non-functional requirements.
2. Identify critical data entities, APIs and data flow.
3. State scale estimates and assumptions.
4. Explain bottlenecks, failures, security and observability.
5. Compare alternatives and justify the selected design.

## Practice Exercise

Design create-link and redirect APIs with expiry and custom aliases.

## Senior-Level Interview Questions

- Which failure modes would break this design first?
- What would you measure to validate its scalability?
- Which consistency and latency guarantees can it actually provide?
- How would you migrate an existing production system safely?

## Further Study

Add an original architecture diagram, capacity estimate and runnable experiment.
