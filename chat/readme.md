group chat

read or not status

text, image video, audio

message history (pagination)

modifying/delete message 

group size

message size

latency of delivery message


# 

websocket

queue for heavy write case

db for saving messages


maintaine websocket connection on the server side for broadcasting


# probrlm

concurrent write message

order, use server's timestamp


# db choice

write heavy

column based, all the message are store continuously 
leader-follower: hbase

leaderless; cassandra

db sharding by channels (chatroom id)

