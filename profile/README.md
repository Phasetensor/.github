<p align="center">
  <img src="assets/logo.png" alt="PhaseTensor" width="600">
</p>

<p align="center"><strong>Scientific software for computational research.</strong></p>

PhaseTensor develops Python libraries for researchers and developers in quantum computing and computational science. Our focus is on practical research problems, statistical reliability, and reproducible experiments.

Quantum computing is our initial research focus. Applications in quantitative finance and computational chemistry are under evaluation.

## Current projects

### ShotWeave — In development

ShotWeave aims to help researchers allocate a limited measurement budget across quantum circuits, particularly when measurement uncertainty differs between circuits.

The first benchmark will compare uniform, weighted, and adaptive shot allocation for a common estimation target under the following constraints:

- 10,000 total shots, including preliminary measurements.
- At most two device submissions.
- Evaluation of estimation error, number of submissions, and total elapsed time.

The objective is to determine when alternative allocation strategies improve estimation accuracy under the same experimental constraints. Performance advantages remain to be validated.

### BornLens

[BornLens](https://github.com/Phasetensor/BornLens) compares the same Pauli observable on two circuit versions. It reports whether the difference is within tolerance, beyond tolerance or inconclusive. The repository includes a Qiskit simulator adapter and [reproducible benchmarks](https://github.com/Phasetensor/BornLens/tree/main/benchmarks).

## Research principles

- Start with a concrete research problem and an explicit baseline.
- Use reproducible experiments and transparent evaluation criteria.
- Document assumptions, uncertainty, and limitations.
- Publish methods and benchmark results alongside validated software.

## Availability

See each project's repository for installation instructions and release status.
