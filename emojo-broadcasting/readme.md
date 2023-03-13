1. requirement

celebrity users and popular streams.

write emoji is high ,


2. api

websocket api

send emoji over websocket connection/rest

server fan out emoji to all the clients


3. diagram

write emoji is high, we need queue to handle the throughput

4. DB schema and ds

each stream have a list of websocket connections

fan out service use the list to forward emojo through websocket

5. deep dive

for celebrity,  a lot of concurrent send emoji,

a lot qps in queue, sharding.
emoji broadcasting is huge , batch, sample, 
