This section of the wiki is dedicated to explaining how Storm is implemented. You should have a good grasp of how to use Storm before reading these sections. 

- [[Structure of the codebase]]
- [[Lifecycle of a topology]]
- [[Message passing implementation]]
- [[Acking framework implementation]]
- [[Metrics]]
- How transactional topologies work
   - subtopology for TransactionalSpout
   - how state is stored in ZK
   - subtleties around what to do when emitting batches out of order
- Unit testing
  - time simulation
  - complete-topology
  - tracker clusters
