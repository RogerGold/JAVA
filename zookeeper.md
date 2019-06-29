## what is zookeeper

Distributed, open-source coordination service for destributed applications.

## what is distributed system

- Multiple computer systems working on a single problem.
- It is a network that consists of autonomous computers that are connected using a 
  distribution middleware.
- Key Freatures:Concurrent, resource sharing, independent, global,greater fault tolerance
  and perofrmance ratio is much better.
- Key Goals:Transparency, OPenness, Reliability, Performance, Scalability.
- Challenges:Security, Fault， Coordination and resource sharing.

## coordination challenge
- single point of failure
- synchronization is not easy
- mater node where the cluster data is stored, slave nodes get the data from this master node.

## zookeeper architecture
Every node contains its own in-memory databse, write requests to Leader node. after processing write requests,
it send changes to follower nodes by Atomic Broadcst.

## zookeeper data model
