1. Requirments

functional requirments;

non-functional: 

2. API

normal http api

server side push api

3. high-level diagram

4. DB Scheme and Data Structure

5. E2E Work Flow

6. Deep Dive




timestamp of watched video:

server generated timestamp


queue + aggregation service

each minutes, each video has a count, in the db, 
sort and retuturn top k 
min heap with size k

if input too big, sharding, like map reduce

sorted array merge

storage of all the event. 


aggregation service down: 

need to know what is the last processed point





