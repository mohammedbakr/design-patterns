## FACTORY [_(creational)_](GAMMA.md#creatoinal-patterns)

A componet responsible solely for the wholesale (not piecewise) creation of objects

- Object creation logic becomes too convoluted
- Initializer is not descriptive
  - Name is always **init**
  - Can't overload with same sets of arguments with different names
  - Can turn into **_optional parameter hell_**
- Wholesale object creation (not-piecewise, unlike [Builder](BUILDER.md)) can be truoblesome
  - A separate method (Factory Method)
  - That may exist in a separate class (Factory)
  - Can create hierarchy of factories with Abstract Factory
