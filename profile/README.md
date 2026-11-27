<p align="center">
  <img src="assets/logo.png" alt="PhaseTensor" width="600">
</p>

<p align="center"><strong>Scientific software for computational research.</strong></p>

PhaseTensor develops Python libraries for researchers and developers in quantum computing and computational science. Our focus is on practical research problems, statistical reliability, and reproducible experiments.

Quantum computing is our initial research focus. Our quantitative finance work focuses on point-in-time data integrity, interest-rate curve validation and calibration risk. Computational chemistry applications are under evaluation.

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

### VintageCheck

[VintageCheck](https://github.com/Phasetensor/VintageCheck) audits point-in-time data integrity in quantitative research and backtesting. It reconstructs historical data vintages, detects future-information leakage, tracks revisions and release evidence, and distinguishes verified, invalid and unverifiable decisions.

[Scientific methodology](https://github.com/Phasetensor/VintageCheck/blob/main/docs/methodology.md) · [Release v0.2.0](https://github.com/Phasetensor/VintageCheck/releases/tag/v0.2.0) · [PyPI](https://pypi.org/project/vintagecheck/0.2.0/)

### CurveMetric

CurveMetric helps fixed-income researchers assess how calibration quotes and interpolation choices affect discount factors, forward rates and portfolio valuations. It includes calibration stability diagnostics, uncertainty propagation, historical curve PCA and separate discounting and projection risk. The repository includes analytical tests, QuantLib comparisons and reproducible benchmarks. [Repository](https://github.com/Phasetensor/CurveMetric) · [Scientific methods and results](https://github.com/Phasetensor/CurveMetric/blob/main/docs/advanced.md) · [Releases](https://github.com/Phasetensor/CurveMetric/releases)

## Research principles

- Start with a concrete research problem and an explicit baseline.
- Use reproducible experiments and transparent evaluation criteria.
- Document assumptions, uncertainty, and limitations.
- Publish methods and benchmark results alongside validated software.

## Availability

See each project's repository for installation instructions and release status.
