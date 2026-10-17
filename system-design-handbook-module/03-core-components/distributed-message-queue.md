# Distributed Message Queue

> Original educational notes inspired by topics covered in *System Design Interview – An Insider’s Guide* Volumes 1 and 2 (Alex Xu; Volume 2 also credits Sahn Lam). These are independent explanations and exercises, **not copied book chapters or diagrams**.

## Core Idea

Explore producers, brokers, partitions/queues, consumers, acknowledgments, offsets, retries, dead-letter queues and replay.

## Architecture and Trade-offs

At-least-once delivery means duplicates are possible. Ordering often holds only within a partition or queue under specified conditions. Broker durability does not replace idempotent business processing.

## Design Checklist

1. Clarify functional and non-functional requirements.
2. Identify critical data entities, APIs and data flow.
3. State scale estimates and assumptions.
4. Explain bottlenecks, failures, security and observability.
5. Compare alternatives and justify the selected design.

## Practice Exercise

Compare Kafka and RabbitMQ for an async document job pipeline and specify retry and deduplication.

## Senior-Level Interview Questions

- Which failure modes would break this design first?
- What would you measure to validate its scalability?
- Which consistency and latency guarantees can it actually provide?
- How would you migrate an existing production system safely?

## Further Study

Add an original architecture diagram, capacity estimate and runnable experiment.
