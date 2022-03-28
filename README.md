# Cache

`Cache` is a high performance local cache package written by golang which is inspired by [Redis](https://github.com/redis/redis) and [LevelDB](https://github.com/google/leveldb). You can see it as a redis with no client-server support.

Mainly used in the following scenarios:

- In monolith, it can be used instead of redis, redis-server is no need.
- In microservice, it can be used as L2 cache to reduce the pressure of L1 cache and DB, which can support more requests.
