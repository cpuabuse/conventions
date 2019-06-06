## Types vs interfaces

**Prefer interfaces** over types. Object of type is literally of that type. Object implementing interface has the shape of that interface. In that sense, interface contains less information than a type. As a convention, we choose minimalist approach, and will generally work with shapes. If using types, a reason should be provided, explaining the need for extra information. For example, if the data is to be sent over the network, being exactly of type may be important.

## Intarface name prefix

Prefix **`I` is not used** for interfaces.