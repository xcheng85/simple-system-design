# realtime data update
store, monitoring dashboard


1. short polling, refapp, startup
2. long pooling, there is a disconnect threadhold

3. server sent event: 
stock, one direction, server push

4. websocket
bidirectional
stateful, machine crash


scale out websocket

stateful, connection

websocket load balancer is different 

gcp External HTTP(S) Load Balancing supports websockt
https://cloud.google.com/load-balancing/docs/https

istio:

upgraded websockets connection on an ingress traffic when using Istio VirtualService.
https://github.com/istio/istio/tree/master/samples/websockets

client send heartbeat to websocket server to handle disconnection and network interruption



## Replication

cdn is a example
redis master slave

inconsitent result from master and replica due to lag

single leader: 
leader down, outage for some time for writing


multiple leaders: handling conflicts between leaders


quorom read and quorom writes. 



## sharding for db,cache
for db:
vertical sharding, by columns

horizontal sharding, by rows. 


consistent hashing:
help: even distribution and minimize data migration due to server add/remove
cannot help: hot key


source for sharding
db rows, 
tree
grid
graph
hashmap


scatter and gather
hotspot
machine hop

