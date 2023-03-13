same resouce is access and modify by multiple requests

single thread: through a queue
low throughput

batch and then single thread. latency to compose a batch

pessimistic locking : redlock

optimistic locking : version comparison, like a patch