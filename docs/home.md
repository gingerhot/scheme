---
title: Write You A Scheme, Version 2.0
date: November 28, 2016
author: Adam Wespiser
---


* [Fork me on github](https://github.com/write-you-a-scheme-v2/scheme)

#### chapter overview
* [Overview](00_overview.md) The view from above.
* [Introduction: The Bolts and Nuts of Scheme Interpreters in Haskell](01_introduction.md)  Scheme syntax and semantics, as well as the Haskell implementation.
* [Parsing](02_parsing.md) Transformation of text into abstract syntax tree.
* [Evaluation](03_evaluation.md) Interpretation of abstract syntax tree using monad transformers.
* [Error Checking and Exceptions](04_errors.md) Exception handling and messages used throughout project. Creation of error messages.
* [The Primitive Environment](05_primitives.md) Primitive functions that are loaded into the environment.
* [Read Eval Print Loop Repeat](06_repl.md) Creating a REPL so we can
  test out our Scheme.
* (Input/Output) Reading and writing to files for both Scheme commands and the reading of program files.
* (Standard Library) Creation of Scheme standard library from primitive functions.
* (Conclusion: Where We Go From Here) We conclude the project.
