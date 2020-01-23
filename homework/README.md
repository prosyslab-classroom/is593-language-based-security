# Homework

This directory provides instructions and skeleton code of programming assignments for this course.
The main goal is to implement an interpreter and a static analyzer for LLVM IR in OCaml.

## Setup
### Prerequisites
- [OCaml](https://ocaml.org) 4.08.0
- [Opam](https://opam.ocaml.org) 2.0
- [LLVM](https://llvm.org) 8.0

### Installation
Assuming the above prerequisites are installed in the system, the following command will install all the dependencies:
```
./setup.sh
eval $(opam env)
```

### Recommendation
Students are highly encouraged (not mandatory though) to use
[OCamlFormat](https://github.com/ocaml-ppx/ocamlformat) (source code formatter for OCaml)
and [Merlin](https://github.com/ocaml/merlin) (IDE feature set for OCaml).
Setting up an efficient programming environment is the most basic task you should do as a professional programmer.

## References
- [OCaml Standard Library](http://caml.inria.fr/pub/docs/manual-ocaml/libref)
- [LLVM OCaml Binding](https://llvm.moe/ocaml/index.html)
- [OCamlFormat](https://github.com/ocaml-ppx/ocamlformat)
- [Merlin](https://github.com/ocaml/merlin)
