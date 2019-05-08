![A stylized worker bee, the Ape logo](./ape_logo.svg)

# Ape - the Arbitrary PEG library

Ape (ah-peh) is a set of crates for writing grammars (specifically, Parsing Expression Grammars) over arbitary types. In particular, Ape aims to simplify multi-stage parsers, which produce and consume one or more intermediate representations, by allowing for a grammatical definition of each stage.

The project is currently split into two crates:
  * `ape`, which provides the types used at runtime for invoking an Ape parser
  * `ape_macros`, which provides compile-time code generation from a DSL
