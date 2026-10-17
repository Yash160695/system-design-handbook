# System Design Handbook

**Original system design notes and interview exercises** covering core topics found in Alex Xu's *System Design Interview – An Insider’s Guide* (Volumes 1 & 2). Volume 2 is co-authored with Sahn Lam.

Maintained by [Yash Rai Khanna](https://github.com/Yash160695) — Java Backend / Distributed Systems Engineer.

> This is an independent study guide, not an official companion to the books. No copyrighted chapter text or diagrams are reproduced. All designs are illustrative and not representations of employer systems.

## How to Use

1. Study foundations and estimate traffic/storage with explicit assumptions.
2. Learn distributed primitives and their failure modes.
3. Practice application designs and advanced case studies.
4. For every design, explain requirements, API/data model, architecture, trade-offs, observability and security.
5. Add original diagrams, Java implementations and tests as you build them.

## Topic Index

## 01 Foundations

- [Scaling from Zero to Millions](01-foundations/scaling-from-zero-to-millions.md)
- [Back-of-the-Envelope Estimation](01-foundations/back-of-envelope-estimation.md)
- [Four-Step Design Interview Framework](01-foundations/interview-framework.md)

## 02 Distributed Systems

- [Consistent Hashing](02-distributed-systems/consistent-hashing.md)
- [Distributed Key-Value Store](02-distributed-systems/distributed-key-value-store.md)
- [Distributed Unique ID Generation](02-distributed-systems/distributed-id-generation.md)
- [Replication and Consistency](02-distributed-systems/replication-consistency.md)

## 03 Core Components

- [Rate Limiting](03-core-components/rate-limiting.md)
- [Caching and Cache Invalidation](03-core-components/caching.md)
- [Distributed Message Queue](03-core-components/distributed-message-queue.md)
- [Metrics Monitoring and Alerting](03-core-components/metrics-monitoring.md)
- [S3-like Object Storage](03-core-components/object-storage.md)

## 04 Application Designs

- [URL Shortener](04-application-designs/url-shortener.md)
- [Web Crawler](04-application-designs/web-crawler.md)
- [Notification Service](04-application-designs/notification-service.md)
- [News Feed](04-application-designs/news-feed.md)
- [Chat System](04-application-designs/chat-system.md)
- [Search Autocomplete](04-application-designs/search-autocomplete.md)
- [Video Streaming Platform](04-application-designs/video-streaming.md)
- [Cloud File Drive](04-application-designs/cloud-drive.md)

## 05 Advanced Designs

- [Proximity Service](05-advanced-designs/proximity-service.md)
- [Nearby Friends](05-advanced-designs/nearby-friends.md)
- [Maps and Route Planning](05-advanced-designs/maps-routing.md)
- [Ad Click Event Aggregation](05-advanced-designs/ad-click-aggregation.md)
- [Hotel Reservation System](05-advanced-designs/hotel-reservations.md)
- [Distributed Email Service](05-advanced-designs/distributed-email.md)
- [Real-Time Leaderboard](05-advanced-designs/leaderboard.md)
- [Payment System](05-advanced-designs/payment-system.md)
- [Digital Wallet](05-advanced-designs/digital-wallet.md)
- [Stock Exchange](05-advanced-designs/stock-exchange.md)

## Recommended Interview Order

1. Scaling, estimation, framework
2. Caching, rate limiting, consistent hashing, distributed IDs
3. Message queues, consistency, key-value stores, monitoring
4. URL shortener, notifications, chat, news feed
5. Object storage, payments, wallet, stock exchange

## References

- Alex Xu, *System Design Interview – An Insider’s Guide*, Volume 1 (2020).
- Alex Xu and Sahn Lam, *System Design Interview – An Insider’s Guide*, Volume 2 (2022).
- [Volume 1 published contents](https://www.harvard.com/book/9798664653403)
- [Volume 2 published contents](https://books.google.com/books/about/System_Design_Interview_An_Insider_s_Gui.html?id=M5gDzwEACAAJ)

## Status

Conceptual study notes; not production implementations. Contributions and corrections welcome.
