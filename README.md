# vism
Virtual Iota Stack Machine

The aim is to implement the *simplest unithread programming language*, to be used as a building block for more complex programming endeavours, such as evolutive distributed programming, and more exciting stuff...

# Inspiration

- http://piumarta.com/software/maru/
- https://web.archive.org/web/20160312050150/http://semarch.linguistics.fas.nyu.edu/barker/Iota/zot.html

# Roadmap

## Language Study
- Idris Zot implementation to verify types (matching monads) for input/output in Zot.
- Scheme implementation for ease of comparison with others minimalist languages
- Elm implementation for simple demos (+ github pages)

## Interpreter refining
- Bootstrap a stack (Rust & Scheme & Idris & Elm) as VM
- Define an Interpreter (Rust & Scheme & Idris & Elm) for our vism code based on the stack.
- Implement a few *meta circular definitional interpreters* (VISM) to solidify the language definition.
- Implement translator for unlambda, lazy-k, and others... for simple comparison testing.
- Lots of testing...

## Type Checking / Effect Theory
- Bootstrap a queue (Rust & Scheme & Idris & Elm) as VM interface to the outside
- Define proper side-effects (Rust & Scheme & Idris & Elm) for our vism code based on the queue.
- Check how interpreter theory, reflection, can be used as theoritical fundation for side-effects in a meta circular implementation (check the *reflective tower of interpreters*) -> Meta Circular Definitional Type Checker ?
- and more...

## Evolution
- Implement mutation (randomly change existing program)
- Implement expansion (expand the program, but keep it s functionality)
- Define how input/output influence which program dies or survives (using types ?). Need more theoritical background, probably require a bunch of prototypes (Scheme & Idris + VISM)
- ...
