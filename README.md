# LRU-Cache

An LRU (Least Recently Used) cache is a type of cache mechanism that discards the least recently used items first when the cache reaches its capacity. This caching strategy is useful in situations where you want to keep track of a limited number of items and ensure that the most frequently or recently accessed items remain available.

## Key-Concepts

- **Capacity:** The cache has a fixed size or capacity, meaning it can only store a specific number of items at any given time.

- **Recency:** Each item in the cache has a usage record that tracks when it was last accessed or used.
  
- **Eviction Policy:** When the cache reaches its maximum capacity and a new item needs to be added, the cache will evict the least recently used item to make space for the new one.