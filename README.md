# Arpit Bhayani System Design Notes

## Day 1

### Pre-Reads
- [CDN](https://www.cloudflare.com/en-in/learning/cdn/what-is-a-cdn/)
- [KV Stores](https://en.wikipedia.org/wiki/Key%E2%80%93value_database)
- [Web Sockets](https://www.twilio.com/docs/glossary/what-are-websockets)
- [Load Balancer](https://www.digitalocean.com/community/tutorials/what-is-load-balancing)
- [Message Broker](https://tsh.io/blog/message-broker/)
- [Heartbeat](https://en.wikipedia.org/wiki/Heartbeat_(computing))
- [Relational DB Schema](https://medium.com/@kimtnguyen/relational-database-schema-design-overview-70e447ff66f9)
- [Blocking Bounded Queue](https://morestina.net/blog/1400/minimalistic-blocking-bounded-queue-for-c)
- [Blocking Queue in Go](https://johannes-weigend.medium.com/concurrency-in-go-32a8b1e35337)
- [DynamoDB](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html)
- [Redis](https://redis.io/about/)

### Topics to Cover
- [Design Online Offline Indicator](https://github.com/arpitbbhayani/system-design-questions/blob/master/online-offline-indicator.md)
- [Design Blogging Platform](https://github.com/arpitbbhayani/system-design-questions/blob/master/blogging-platform.md)

### Post Reads


### Things Learnt

- Framework of Opposites

### Design a Connection Pool

- Use BlockingQueue

### Caching

Same request comes more than once cache miss happens, that routes to 
- Request Hedging
- Cache Debouncing
- Semaphore, MutEx


Find all places where you can cache
- CDN
- API Cache
- 
