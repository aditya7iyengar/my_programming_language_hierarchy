# Elixir

A general purpose, functional programming language which runs on top of BEAM.
Jose Valim created Elixir in 2011 as a part of an R&D project in Platformatec
and since then it has been used and adpoted by various companies worldwide.

Everything in elixir is an expression, which gets compiled to bytecode for
Erlang Virtual Machine to interpret. Due to this elixir boasts seamless
Erlang integration and interoperability.


## Architecture

- A ([close to purely](https://en.wikipedia.org/wiki/Purely_functional_programming)) functional language
- Everything is an expression
- [Dynamic Dispatch](https://en.wikipedia.org/wiki/Dynamic_dispatch) using Protocols
- Metaprogramming which allows manipulation of the generated AST at compile time
- Pattern Matching
- Great concurrency with message passing using [Actor Model](http://www.brianstorti.com/the-actor-model/)
