# Workflow Overview

This project currently exposes the workflow direction at a public-summary level rather than as a complete polished software release.

## Main Workflow Threads

### MOF Workflow

The MOF workflow is a config-driven path for starting new screening projects, applying structure modifications, and preparing or running adsorption simulations for specific discovery goals.

Key ideas:

- project setup from a seed CIF and a goal preset
- configuration-driven modifications
- preparation of simulation-ready inputs
- support for either live simulation or surrogate execution paths
- machine-readable results and short reports

### Reticular Pipeline

The reticular pipeline is a broader modular scaffold for designing, assembling, optimizing, and evaluating MOFs on a laptop-class machine.

Key ideas:

- building block and topology representation
- structure assembly and export
- optional external-tool integration for optimization and simulation
- lightweight dry-run behavior when heavy binaries are unavailable
- iterative candidate generation and scoring

## Important Boundary

These workflows help organize candidate generation and evaluation. They do not, by themselves, prove that a generated modified structure is physically realizable or experimentally validated.

## Public Standard

Any future public code release should preserve that boundary clearly:

- workflow output is not the same as physical proof
- generated candidates still require external validation
- negative results remain valuable data
