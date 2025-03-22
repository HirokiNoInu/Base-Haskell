# Base-Haskell
A basic project for Haskell with Cabal and tests.

Current versions:
- cabal: 3.12.1
- GHC: 9.10.1
- HLS 2.9.0.1
- GHCup 0.1.40

## Build/Run/Test

These are the commands to build, run, and test the project:

```
cabal build
```
```
cabal run
```
```
cabal test
```

## Install Libs
A simple way to install libs is this:
```
cabal install --lib HUnit --package-env .
```
