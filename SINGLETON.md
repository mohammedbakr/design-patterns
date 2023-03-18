## SINGLETON [_(creational)_](GAMMA.md#creatoinal-patterns)

A component which is instantiated only once

- For some components it only makes sense to have one in the system
  - Database repository
  - Object factory
- The constructor call is expensive
  - we want intialization to only happen once
  - We provide everyone with the same instance
- Want to prevent anyone creating additional copies
