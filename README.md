# Defunctionalization with dependent types
This is the Tex repository for my PartIII dissertation.

## Abstract

This dissertation studies *defunctionalization*, a program transformation that turns a higher-order functional program into a first-order one. 
Type-preserving defunctionalization for
simply-typed and polymorphic systems is well-studied in the literature, and my work
extends defunctionalization further to dependently-typed systems.

I illustrate that Pottier and Gauthier’s polymorphic defunctionalization does not extend to
dependently-typed languages. Then, I present *abstract defunctionalization* as an alternative
approach. Abstract defunctionalization consists of a target language with a primitive
notion of function labels that fits the abstract description of defunctionalization, and a
transformation from the source language to the target language. I prove the transformation
type-preserving and correct, and I show that the target language is type-safe and consistent.
An interpreter of the target language and the transformation are implemented in OCaml.

