raft
============
[![](https://img.shields.io/badge/oscillating-works-blue.svg?style=flat)](https://github.com/oscillatingworks/compass#phases)

Author
------
Conrad Parker

conrad@metadecks.org

http://blog.kfish.org/

Link
----
https://github.com/kfish/raft

Category
--------
Algorithms / Protocols

Language
--------
Haskell

Description
-----------
Haskell implementation of the Raft distributed consensus protocol.

:thumbsup:
----------
- Very early stage, one experienced contributor
- [Raft](https://raftconsensus.github.io/) is a very popular distributed consensus protocol with many implementations
- So far only one mature [Haskell Raft implementation](https://github.com/NicolasT/kontiki) not maintained for 1 year
- Would be interesting to learn Haskell
- Interesting distributed algorithm to learn
- Would be interesting to write sample applications

:thumbsdown:
------------
- Not sure about owner intentions / plans
- Project in very early stage
- Need to learn Haskell
- Need to learn Raft

Further comments
----------------
In general this project might have some potential. Just have a look on other Raft implementations ([Go](https://github.com/hashicorp/raft), [Go](https://github.com/peterbourgon/raft), [Java](https://github.com/kuujo/copycat), [Scala](https://github.com/ktoso/akka-raft)) - they are very popular and well maintained. Since Haskell is gaining more and more attention as a language to build distributed systems, sooner or later Haskell community will need this protocol implementation.

Another approach would be to take existing and well maintained Raft implementations like [Scala](https://github.com/ktoso/akka-raft), [Erlang](https://github.com/andrewjstone/rafter) or any other language and bring it to production ready state with proper documentation, tests and examples.