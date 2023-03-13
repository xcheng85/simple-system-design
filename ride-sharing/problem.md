1. High QPS 

database: 500 qps

ssd: 10000 qps

cache cluster: 50000

lower the frequency can decrease qps by magnitute 2 or 3


2. db failure

leader-follower:    select new leader, outage

leaderless: no outage


3. location,

quadree


4. concurrency 

1. serially process with queue
2. serially processing with batch 
3. pessimistic locking
4. opt locking 