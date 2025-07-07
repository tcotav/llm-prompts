# Top 10 System Design Topics for Technical Interviews

A comprehensive study guide covering the most important system design topics you should master for technical interviews.

## 1. URL Shortener (like bit.ly)

Essential for understanding basic system design principles including database design, caching, and handling high read/write ratios. Great starting point that covers encoding schemes and simple scaling patterns.

**Key Concepts:**
- Base62 encoding
- Database schema design
- Caching strategies
- Rate limiting
- Analytics tracking

## 2. Chat/Messaging System (like WhatsApp)

Demonstrates real-time communication patterns, WebSocket connections, message queuing, and handling online/offline states. Shows understanding of push notifications and message delivery guarantees.

**Key Concepts:**
- WebSocket connections
- Message queuing (FIFO)
- Online presence tracking
- Push notifications
- Message delivery status
- End-to-end encryption

## 3. Social Media Feed (like Twitter/Instagram)

Covers complex topics like fanout strategies (push vs pull), timeline generation, content ranking algorithms, and handling celebrity users with millions of followers.

**Key Concepts:**
- Fanout on write vs fanout on read
- Timeline generation
- Content ranking algorithms
- Celebrity user problem
- Media storage and CDN
- Like/comment systems

## 4. Video Streaming Platform (like YouTube)

Introduces content delivery networks (CDNs), video encoding/transcoding, global distribution, and massive storage requirements. Shows understanding of media processing pipelines.

**Key Concepts:**
- Video encoding/transcoding
- Content Delivery Networks (CDN)
- Video metadata storage
- Global distribution
- Video processing pipelines
- Adaptive bitrate streaming

## 5. Ride-sharing Service (like Uber/Lyft)

Demonstrates geospatial indexing, real-time matching algorithms, location tracking, and handling high-frequency location updates. Great for discussing mapping and routing systems.

**Key Concepts:**
- Geospatial indexing (QuadTree, Geohash)
- Real-time location tracking
- Driver-rider matching algorithms
- ETA calculation
- Pricing algorithms
- Trip state management

## 6. Web Crawler/Search Engine

Shows understanding of distributed crawling, data processing pipelines, inverted indexes, and handling massive scale data ingestion. Covers both breadth-first strategies and ranking algorithms.

**Key Concepts:**
- Distributed web crawling
- Inverted index construction
- PageRank algorithm
- Duplicate content detection
- Politeness policies
- Search result ranking

## 7. Key-Value Store/Cache (like Redis)

Fundamental building block for many systems, covering distributed hashing, replication strategies, consistency models, and memory management. Essential for understanding caching layers.

**Key Concepts:**
- Consistent hashing
- Replication strategies
- CAP theorem
- LRU/LFU eviction policies
- Data partitioning
- Failure detection and recovery

## 8. Rate Limiter/API Gateway

Demonstrates throttling algorithms (token bucket, sliding window), distributed rate limiting, and API protection strategies. Shows understanding of system resilience and abuse prevention.

**Key Concepts:**
- Token bucket algorithm
- Sliding window rate limiting
- Distributed rate limiting
- API authentication/authorization
- Request routing
- Circuit breaker pattern

## 9. Payment/Transaction System

Covers ACID properties, distributed transactions, double-entry bookkeeping, fraud detection, and handling financial data consistency. Critical for understanding data integrity at scale.

**Key Concepts:**
- ACID properties
- Two-phase commit
- Double-entry bookkeeping
- Fraud detection
- Payment processing workflows
- Reconciliation systems

## 10. Notification System

Shows understanding of multi-channel delivery (email, SMS, push), user preferences, delivery guarantees, and handling failures. Demonstrates event-driven architecture and queuing systems.

**Key Concepts:**
- Multi-channel delivery
- User preference management
- Message queuing
- Delivery guarantees
- Failure handling and retries
- Template management

## Study Approach

These systems progressively build complexity and cover the core concepts you'll encounter in most system design interviews:

- **Scalability**: Horizontal and vertical scaling strategies
- **Consistency**: ACID properties, eventual consistency, strong consistency
- **Availability**: Fault tolerance, redundancy, disaster recovery
- **Partitioning**: Data sharding, consistent hashing
- **Caching**: Multi-level caching, cache invalidation strategies
- **Real-time processing**: Event-driven architectures, stream processing

## Interview Tips

1. **Start with requirements**: Always clarify functional and non-functional requirements
2. **Estimate scale**: Calculate read/write ratios, storage needs, and bandwidth
3. **High-level design first**: Begin with a simple architecture, then add complexity
4. **Deep dive**: Be prepared to explain any component in detail
5. **Trade-offs**: Discuss pros and cons of different approaches
6. **Monitoring**: Don't forget to mention logging, metrics, and alerting

