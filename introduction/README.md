# Substrate Recipes 🍴😋🍴
Substrate Recipes is a cookbook of working examples that demonstrate best practices when building blockchains with Substrate.

# Prerequisites
Should meet the following prerequisites:
- Have a working Substrate development environment.
- Learning Rust before learn Substrate.
- Complete the first few Official Substate Tutorials.

# Structure of a Substrate Node
![!](https://substrate.recipes/img/substrate-architecture.png)
It is useful to recognize that coding is all about abstraction.

To understand how the code in this repository is organized, let's first take a look at how a Substrate node is constructed.

Each node has many components that manage things like the 
- Transaction queue
- Communicationg over a P2P network
- Reaching consensus in the state
- Runtime logic.

