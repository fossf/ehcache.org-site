---
---

# Configuration Overview

The following sections provide a documentation Table of Contents and additional information sources about Ehcache configuration.

## Configuration Table of Contents

| Topic | Description |
|:-------|:------------|
|[Introduction](/documentation/2.7/configuration/configuration)|The basics of cache configuration with Ehcache, including dynamically changing cache configuration, cache warming, and copyOnRead/copyOnWrite cache configuration.|
|[BigMemory](/documentation/2.7/configuration/bigmemory)|Introduction to BigMemory, how to configure Ehcache with BigMemory, performance comparisons, an FAQ, and more.|
|[Sizing Caches](/documentation/2.7/configuration/cache-size)|Tuning Ehcache often involves sizing cached data appropriately. Ehcache provides a number of ways to size the different data tiers using simple cache-configuration sizing attributes. This page explains simplified tuning of cache size by configuring dynamic allocation of memory and automatic load balancing.|
|[Expiration, Pinning, and Eviction](/documentation/2.7/configuration/data-life)|The architecture of an Ehcache node can include a number of tiers that store data. One of the most important aspects of managing cached data involves managing the life of the data in each tier. This page covers managing data life in Ehcache and the Terracotta Server Array, including the pinning features of Automatic Resource Control (ARC).|
|[Persistence and Restartability](/documentation/2.7/configuration/fast-restart)|This page covers cache persistence, fast restartability, and using the local disk as a cache storage tier. The Ehcache Fast Restart feature provides enterprise-ready crash resilience, which can serve as a fast recovery system after failures, a hot mirror of the cache on disk at the application node, and an operational store with in-memory speed for reads and writes.|


## Hit the Ground Running
Popular topics in Configuration:

* [Cache Warming](/documentation/2.7/configuration/configuration#cache-warming-for-multi-tier-caches)
* [Handling JVM startup and shutdown with BigMemory](/documentation/2.7/configuration/bigmemory#handling-jvm-lifecycle)
* [Sizing Distributed Caches](/documentation/2.7/configuration/cache-size#sizing-distributed-caches)


## Additional Information about Configuration
The following pages provide additional information about Ehcache configuration:

* [Discussion of Data Freshness and Expiration](/documentation/2.7/recipes/expiration)
* [Adding and Removing Caches Programmatically](/documentation/2.7/code-samples#adding-and-removing-caches-programmatically)
* [Creating Caches Programmatically](/documentation/2.7/code-samples#creating-caches-programmatically)






