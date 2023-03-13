# schema

primary key, 
foreigh key

# indexing

bst log n vs n 


what is the clusterred index

index could help: 

search record by match

sort by attribute

search record by prefix match


geohash

composite index

how to index is drived by the your query 

geo index (longtitude, latitude)

CAP (consitency, available, partition)

multiple db types in one question ? 






sql: 
when we need transactional query and non-trivial query, data is structured

bad: write is slower than read due to b-tree re-blancing


document store: 
when data is unstructured. very rare

wide column store:  Cassandra and Bigtable.HBase
columnar db:  influxdb
for time-series, 
store continuously by column, good for compression using delta,OLAP(Online Analytical Processing),streaming data


replication: leader-follower, and leadrless 





blob store: image,video, 

object/file storage: log, pdf, csv




inverted index store: search text
elastic search, lucene
inverted index is a data structure

in-memory store: redis, memcache



geo-spatial db: location-based query
yelp, people nearby

zookeeper: store configs, regstries





# Distributed Transaction

money transaction, 2 phase commit


blob storage and metadata storage as a transaction. 

if failed,  a background job to clean the dangling resource.