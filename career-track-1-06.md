***Redis
Redis stands for remote dictionary server, it is an open source, key-value data store in memory. It can be used as a database, cache, message broker, and queue. It is built to be fast, due to its in-memory design. Redis has more features than its closest equivalent, memcached.

***Queue
Queue is a data structure, that places elements in a sequence. It uses the first in first out method. It has four basic operation, Enqueue, Dequeue, isEmpty, and Top.

***Task Queue Overview
This is a process in which operations that take a significant amount of time can be deferred and prioritized.

***Task Queue -FIFO
First In First Out queues are the normal type, because they are fast and easy to implement. The example in the reading did not feel very clear to me, so I'm interested in exploring the subject during lecture.

***Bull Quick Start
Bull is a node library based on redis. It implements queues in a way that is more feature rich, easier to use, and enriches the basic redis commands. The three main roles that a queue instance can have are job producer, job consumer, and events listener. These exist in a many to many to many relationship, and a single instance can fulfill multiple roles depending on the situation. Producers are node programs that add jobs to the queue. Consumers are node programs that define a process function and run that process whenever the consumer is idling. Listeners are just things like console.logs that can give us information about the queue.