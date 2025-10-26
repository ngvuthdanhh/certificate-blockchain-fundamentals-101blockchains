# Experimental Analysis

### Objective
Perform small-scale experiments to understand blockchain behavior and performance metrics.

### Experiment 1: Block Propagation Latency
- **Setup:** 2 local Ethereum nodes.  
- **Metric:** Average block propagation delay.  
- **Observation:** Propagation time increases linearly with network size.

### Experiment 2: Gas Cost Benchmarking
- **Setup:** Simple Solidity contract (storage and computation heavy).  
- **Metric:** Gas used per transaction.  
- **Observation:** Functions with more storage writes cost 60–70% more gas.

### Experiment 3: Consensus Comparison
- **Setup:** Simulate PoW vs. PoS networks.  
- **Metric:** Energy consumption and time-to-finality.  
- **Observation:** PoS offers faster finality with minimal energy footprint.
