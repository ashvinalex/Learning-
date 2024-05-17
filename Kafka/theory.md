# Basics

## Topic
* is a stream of data
* like a table in a database without all constraints
* have n number of topics
* supports multiple formats JSON, Avro, Binary
* the sequence of messages are called a stream
* data can be pushed to a topic using a producer and retrieved using a consumer

## Partitions
a topic is split into multiple partitions 
message are ordered within a portions
each message has an incremental ID called an offset
Topics are Immutalable; once written cannot be changed

