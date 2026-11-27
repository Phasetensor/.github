# PhaseTensor

**Scientific software for computational research.**

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

### BornLens — Planned

BornLens will compare an observable measured on two versions of a quantum circuit against a predefined tolerance, accounting for statistical uncertainty. It will distinguish three outcomes: difference within tolerance, difference beyond tolerance, and insufficient evidence to reach either conclusion.

## Research principles

- Start with a concrete research problem and an explicit baseline.
- Use reproducible experiments and transparent evaluation criteria.
- Document assumptions, uncertainty, and limitations.
- Publish methods and benchmark results alongside validated software.

## Availability

The projects above are in development or planning. Installation instructions, PyPI links, and release information will be added when public releases become available.
