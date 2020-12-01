![build](https://github.com/z5labs/qiskit/workflows/build/badge.svg)

# qiskit **!!WIP!!**

Qiskit is an open-source framework for quantum computing. This is the home
for a Rust implementation influenced by the original Python implementation.

## Goals

1) Leverage Rusts great type system to provide a seamless API
2) Support Web Assmebly to provide a near-native performance web experience
3) Be testable

## Monorepo Structure

This monorepo structure is meant to hold a set of crates which can be composed
together to provide any level of use cases when it comes quantum computing. Some
cases include: simulating on a traditional pc, experimenting on an actual
quantum pc, and designing quantum circuits.

*MVP Structure*
* `qiskit` - Quantum Computing SDK
* `qiskit-ibm` - IBM Quantum Backend

*Future Structure (WIP)*
* `qiskit` - Quantum Computing SDK
* `qiskit-ibm` - IBM Quantum Backend
* `qiskit-sim` - A collection of Quantum simulators
