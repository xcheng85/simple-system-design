cdn is a form of cache

## data structure for cache

in memory map

tires

quadtree

## write cache

source of truth: db or kubernetes state

we are using "write-through" strategy, write to cache and then to kubernetes server, do we have the atomic

## cache stale handle

1.
2.
3.
4. ttl

lru

l frequency u




## cache failure
Do we need a back up depends


redis failure
1. pperiodic snapshot -> backup file
data could outdated, tradeoff backup freq

2. Write-ahead log
redis

each command write to log first
replay the log takes time


3. replication, 

redis multiple slaves





