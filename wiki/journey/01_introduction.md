# Journey 01 - Introduction

This is a very ambitious project that will probably lead to nowhere. Still, there
is something about it that grabs my interest and hopefully I'll be able to
help others as it goes.

It's not considered a good thing to learn a programming language and a new editor
at the same time, right? We should always minimize frustration and celebrate
short-term goals to keep every one motivated. I'll split this project in 4
achiavable parts.

1. Getting better with Rust.

Rust is a relatively new programming language with great performance and strong
safety guarantees. Safety here means it prevents seg-faults and memory leaks,
the most common errors I've encountered when writing C.

2. Data structures and algorithms

This will probably be the hardest part in this project. For what I have read,
most databases (at least NoSQL) uses B-Tree or some variation of it. LevelDB,
which will be the main inspiration, implements a LSM-tree.

3. Distributed systems

After we have a storage system that works locally, it's time to distributed
it. I'll probably look into Cassandra and RethinkDB for inspiration. Cassandra
uses a consistent-hashing algorithm to find which node a record belongs.
RethinkDB uses sharding to partition records by a shard key. This is all
I know.

4. Optimizations

I have no idea what will (or not) need to be optimized. I'll just leave it here
and update it later on.

To wrap it up, I have two goals with this project: learning and teaching. I'll 
write about each step, each new concept, things that worked and things that didn't work.
Hopefully you can 

