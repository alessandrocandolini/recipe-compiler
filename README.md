# recipe-compiler

[![CI](https://github.com/alessandrocandolini/recipe-compiler/actions/workflows/ci.yml/badge.svg)](https://github.com/alessandrocandolini/recipe-compiler/actions/workflows/ci.yml) [![codecov](https://codecov.io/gh/alessandrocandolini/recipe-compiler/branch/main/graph/badge.svg?token=VFAMXI4W1W)](https://codecov.io/gh/alessandrocandolini/recipe-compiler)

## How to build and run locally

The project uses the [Haskell tool stack](https://docs.haskellstack.org/en/stable/README/).

Assuming `stack` is installed in the system, the project can be build by running
```
stack build
```
To build and also run the tests, run
```
stack test
```
which is equivalent to
```
stack build --test
```
To run the executable,
```
stack exec recipe-compiler-exe
```
For a faster feedback loop,
```
stack test --fast --file-watch
```
To run `ghci` (with a version compatible with the resolver) run
```
stack ghci
```
For more information, refer to the `stack` official docs.
