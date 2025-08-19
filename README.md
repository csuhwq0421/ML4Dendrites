# ML4Dendrites
## ML4Dendrites is the Official Repository for the paper ‘Machine intelligence supports the full chain of material synthesis: A case study on chemical vapor deposition growth of 2D ReSe2 dendrites’.
Exemplified by the chemical vapor deposition growth of two-dimensional ReSe2 dendrites, which has potential applications in catalysis and presents a parameter-intensive, data-scarce and reaction process-complex model problem, we devise a machine intelligence-empowered framework for the full chain support of material synthesis, encompassing rapid process optimization, accurate customized synthesis, and comprehensive mechanism deciphering. First, active learning is integrated into the experimental workflow, identifying an optimal recipe for the growth of highly branched, electrocatalytically active dendrites through 60 experiments (4 iterations), which account for less than 1.3% of the numerous possible parameter combinations. Then, a discrepancy-based data augmentation strategy is developed combined with a tree-based machine learning (ML) algorithm, unveiling a non-monotonic, non-linear correlation between 5 process variables and fractal dimension (DF) of ReSe2, dendrites with only 9 experiment additions, which guides the synthesis of various user-defined DF. Finally, we construct a multifactorial growth mechanism by integration of cross-scale characterizations, interpretable ML models, and domain knowledge in thermodynamics and kinetics, unraveling synergistic contributions of multiple key process parameters to the product morphology, which aligns with both human cognition and ML conclusions. This work demonstrates the ML potential to transform the research paradigm and is adaptable to broader material synthesis.

## Data and Code Description
- **Process optimization** :This module is designed to quickly retrieve the optimal process conditions for the CVD growth of highly branched 2D ReSe2 crystals from a vast parameter space using as little experimental cost as possible.
* **Customized synthesis**  :This module aims to construct a mapping between the five process variables and the dendritic morphology of ReSe2, enabling easy determination of process conditions corresponding to various user-defined DF.
+ **Mechanism deciphering** :This module is to unveil a multifactorial growth mechanism by integrating interpretable ML models, cross-scale spectroscopic/microscopic characterizations, and researchers’ domain knowledge in thermodynamics and kinetics.
Specific details can be referred to the code comments.

## Hardware requirements
You can run all the code completely on your PC.

## Python Dependencies

Installation Requirements:
Python 3.8 is recommended.
```
emukit 0.4.11
emcee 3.1.6
gpy 1.13.2
matplotlib 3.9.2
numpy 1.23.0
pandas 2.2.3
xgboost 2.1.1
scikit-learn 1.6.1
scipy 1.12.0
seaborn 0.13.2
shap  0.47.0
shapiq 1.3.1
```
## Citation

## License
This project is licensed under the terms of the MIT license. See [LICENSE](https://github.com/csuhwq0421/ML4Dendrites/blob/main/LICENSE) for additional details
