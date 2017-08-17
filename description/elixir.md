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
- Support for [High-Order functions, First-Class functions and Lambdas](http://elixirdose.com/post/basicfp)
- Lightweight concurrency
- Support for [Lazy Loading](https://hexdocs.pm/elixir/Stream.html)


### Summary

With a great architecture built on top of an already solid architecture of OTP,
Elixir's architecture is one of the best things about using it. It encourages
concurrency and separations of concerns, and is truely an example of using
concurrency as a variable in a well-designed application.

It might not have a superior architecture like Haskell or Rust, but features like
[Polymorphism](https://medium.com/elixirlabs/polymorphism-in-elixir-cd0c765b6929) through Protocols,
[Abstractions](https://elixirschool.com/en/lessons/advanced/behaviours) through Behaviors,
and Metaprogramming thourgh Macros show how much thought was put into Elixir's
architecture.


## Existence Justified?

__Yes__

Rails/Ruby developers are naturally drawn towards Elixir due to its syntax,
the fact that it solves a lot of problems Ruby has (less effecient concurrency) and
the emergence of a great web framework which solves a lot of design problems in Rails
, [Phoenix](http://phoenixframework.org/), Rails developers are increasingly switching over to Phoenix.
Therefore, I think it's existence is well justified.


## Potential for Future

__Yes__

Having a prominent member of the Rails team, Jose Valim, being the author and
maintainer, and a syntax strickingly similar to Ruby, Elixir has a bright future, imo.

## Pleasure of Writing
