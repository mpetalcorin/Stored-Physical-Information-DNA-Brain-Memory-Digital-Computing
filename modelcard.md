# Model Card

## Model name

**Information Is Physical Comparative Modeling Suite**

## Model summary

This repository contains a set of supervised and unsupervised machine learning models developed to analyze literature-anchored synthetic datasets representing three information-bearing systems:

- DNA information fidelity
- brain memory retention
- computer-bit reliability

The models are designed to test whether a shared thermodynamic logic of information preservation can be computationally recovered across mechanistically distinct systems.

## Intended use

These models are intended for:

- conceptual demonstration,
- educational use,
- interdisciplinary teaching,
- computational prototyping,
- methodological illustration,
- hypothesis generation.

They are suitable for exploring the idea that physically embodied information is shaped by the balance between destabilizing forces and energy-dependent maintenance.

## Not intended for use

These models are **not** intended for:

- clinical decision-making,
- diagnosis,
- biological inference from patient samples,
- direct interpretation of wet-lab data,
- hardware certification,
- claims of empirical causality,
- deployment in high-stakes settings.

Because the models are trained on synthetic benchmark data, they must not be interpreted as validated predictors of real biological or engineering outcomes.

## Data used

The models were trained on synthetic datasets whose feature ranges were inspired by peer-reviewed PubMed-indexed literature on:

- DNA damage and repair
- ATP-dependent chromatin remodeling
- synaptic plasticity and memory consolidation
- brain glucose metabolism
- thermodynamics of computation and Landauer’s principle

The datasets represent three domains:

### DNA domain
Features include lesion burden, oxidative fraction, repair efficiency, chromatin remodeling support, replication stress, antioxidant support, and cell-cycle pressure.

Target:
- **DNA information fidelity**

### Brain domain
Features include glucose utilization, glycogen support, protein synthesis capacity, synaptic plasticity support, sleep-related consolidation support, oxidative stress, and network noise.

Target:
- **memory retention score**

### Computer-bit domain
Features include temperature, energy barrier relative to the Landauer bound, hardware noise, error-correction strength, and reset-energy burden.

Target:
- **bit reliability score**

### Cross-system domain
Features are mapped into generalized comparative variables:
- stability index
- energy-support index
- noise index
- adaptation index
- system label

Target:
- **generalized information score**

## Model types

The notebook includes the following model families:

### Regression models
- Linear Regression
- Ridge Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- Multilayer Perceptron Regressor

### Classification models
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier
- Multilayer Perceptron Classifier

### Unsupervised methods
- Principal Component Analysis
- K-means clustering
- t-SNE

## Evaluation

Model evaluation is performed using held-out synthetic test data.

### Regression metrics
- R²
- Mean Absolute Error
- Root Mean Squared Error

### Classification metrics
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC where applicable

### Interpretability
- Permutation feature importance

## Key findings

Across the synthetic benchmark framework, the models consistently recover the intended logic that:

- information quality improves when stabilizing and energy-supportive variables dominate,
- information quality declines when noise, damage, or stress dominate,
- shared comparative indices capture a cross-domain architecture of information maintenance.

## Ethical considerations

This repository operates in a low-risk conceptual setting, but several points remain important:

- The data are simulated, not experimental.
- The models should not be used to make claims about individual people, cells, brains, or devices.
- Cross-domain comparisons are useful conceptually but must not be over-interpreted as proof that genomes, brains, and computers are mechanistically equivalent.
- Biological complexity is simplified to support interpretability.

## Limitations

- Synthetic data reflect the assumptions encoded into the simulation.
- Literature-anchored ranges improve plausibility but do not replace real datasets.
- Performance metrics reflect learnability of simulated structure, not external validity.
- Feature importances are meaningful within the synthetic framework only.
- Cross-system harmonization simplifies domain-specific biology and physics.

## Recommendations for future work

- Validate the framework using real genomic, neurobiological, and hardware datasets.
- Compare energetic cost and fidelity across experimentally measured systems.
- Extend model interpretation with SHAP or causal sensitivity methods.
- Explore disease states as failures of information preservation under thermodynamic constraint.
- Build domain-specific mechanistic submodels before attempting stronger cross-domain generalization.

## Contact

Add repository owner contact details here.
