# Datasheet for Datasets

## Dataset title

**Literature-Anchored Synthetic Benchmark Datasets for Physically Embodied Information**

## Motivation

These datasets were created to support a conceptual and computational study comparing three physically distinct information-bearing systems:

- DNA
- brain memory
- computer bits

The goal was to generate synthetic benchmark data that reflect biologically and physically plausible relationships reported in peer-reviewed PubMed-indexed literature, while remaining fully transparent and reproducible for exploratory analysis and machine learning.

## Composition

The project contains three primary synthetic datasets and one integrated comparative dataset.

### 1. DNA dataset
This dataset represents a genome-like information system subject to damage, repair, and chromatin regulation.

Representative variables:
- lesions_per_day
- oxidative_fraction
- repair_efficiency
- chromatin_remodeling_index
- replication_stress_index
- antioxidant_capacity_index
- cell_cycle_pressure_index
- dna_information_fidelity

### 2. Brain dataset
This dataset represents a memory-like information system dependent on metabolism, plasticity, and network stability.

Representative variables:
- brain_glucose_utilization
- glycogen_support_index
- protein_synthesis_index
- synaptic_plasticity_index
- sleep_consolidation_support
- oxidative_stress_index
- network_noise_index
- memory_retention_score

### 3. Bit dataset
This dataset represents a hardware-like digital information system constrained by thermodynamics and noise.

Representative variables:
- temperature_K
- barrier_multiple_landauer
- hardware_noise_index
- error_correction_strength
- reset_energy_practical
- bit_reliability_score

### 4. Integrated cross-system dataset
This harmonized dataset maps the three domains into shared higher-order indices.

Representative variables:
- system
- stability_index
- energy_support_index
- noise_index
- adaptation_index
- information_score

## How the data were generated

The datasets were generated synthetically in Python.

The generation process followed these principles:

1. Choose biologically or physically meaningful variables for each system.
2. Assign plausible ranges inspired by peer-reviewed journal literature.
3. Sample those variables with controlled variation.
4. Construct outcome variables using weighted relationships that reflect expected mechanistic logic.
5. Validate the resulting distributions using summary statistics and benchmark checks.

The datasets therefore combine:
- literature-informed ranges,
- explicit simulation assumptions,
- transparent outcome construction.

## Why synthetic data were used

Synthetic data were used because the project aims to compare very different systems within one controlled conceptual framework. Real datasets across these domains differ greatly in scale, measurement standards, and availability. Using synthetic benchmark data made it possible to:

- align variables across domains,
- preserve interpretability,
- test the framework transparently,
- evaluate machine learning behavior under known assumptions.

## Recommended uses

These datasets are suitable for:

- teaching and education,
- conceptual demonstration,
- exploratory statistics,
- machine learning prototyping,
- feature-importance analysis,
- dimensionality reduction and clustering,
- interdisciplinary discussion of information, entropy, and energy.

## Not recommended uses

These datasets are not suitable for:

- biomedical decision-making,
- patient-level inference,
- biological validation,
- engineering certification,
- real-world device optimization,
- causal inference about actual living systems or hardware.

## Relationship to real-world systems

The datasets are **inspired by** real literature, but they are **not measurements from real experiments**. They are best described as **synthetic benchmark datasets with literature-anchored values**. Any apparent pattern recovered by analysis reflects both the literature-inspired design and the simulation logic.

## Preprocessing and analysis

Within the notebook, the datasets are used for:

- descriptive statistics,
- histogram and scatterplot visualization,
- correlation analysis,
- supervised regression,
- supervised classification,
- permutation importance,
- cross-system harmonization,
- PCA,
- K-means clustering,
- t-SNE,
- thermodynamic reference plotting.

## Potential sources of bias

Because the datasets are simulated, the main sources of bias are:

- assumptions used in variable ranges,
- assumptions used in outcome weighting,
- simplification of highly complex biological systems,
- stronger controllability than would be present in real-world noisy datasets.

These biases are intentional to some degree because the notebook is designed as a conceptual proof of principle rather than a real-world benchmark challenge.

## Dataset maintenance

If the repository is expanded, future versions of the datasets should clearly version:

- the literature anchors,
- the simulation equations,
- the variable definitions,
- the output scaling logic,
- any preprocessing changes.

## Distribution
MIT repository license

## Citation guidance
**Mark I.R. Petalcorin** (2026). From Abstract Information to Physical Information: A Comparative Thermodynamic and Machine Learning Framework Linking DNA, Brain Memory, and Digital Computation. https://github.com/mpetalcorin/Stored-Physical-Information-DNA-Brain-Memory-Digital-Computing

If these datasets are reused, cite them as synthetic benchmark datasets created for conceptual comparison of physically embodied information across DNA, brain memory, and digital computation.
