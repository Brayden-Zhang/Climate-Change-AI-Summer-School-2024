*Notes taken for Lily Xu's talk on **AI for Conservation Decisions** on June 26 2024.*


Main Drivers of Biodiversity Loss
* Changes in land/sea use
  * mostly due to agriculture
* Direct exploitation of species
  * logging
  * poaching
* Invasive species
* Climate Change
* Pollution

## Algorithmic Decision Making
Monitoring ==> Planning ==> Impact Evaluation

Classic Decision Treess
* US FAO's decision support tree for management of peatlands and organic soils

### Optimization:
* google maps routing
* air traffic control
* Conservation: prioritizing key land to conserve

Specifying a space of possible decision strategies and a performance measure to be mazimied, then using computational methods to efficiently search the space. 

### Online learning
* learn models incrementally from data as new samples arrive
  * useful when there is an action to be taken at repeated timesteps
  * can be combined with human feedback
* Key methods
  * multi-armed bandits
  * online clustering
  * density estimation

### Reinforcement learning
* learning in real time through repeated interaction with (simulated) environment

### Causal Inference
* Study cause-and-effect relationships
