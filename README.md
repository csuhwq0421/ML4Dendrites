# ML4Dendritic
## ML4Dendritic is the official repository for the paper ‘Machine intelligence-guided growth and multifactorial mechanism deciphering of two-dimensional ReSe2 dendrites’.
Taking the dendrite growth of rhenium selenide (ReSe2) materials as an example, ML4dendritic contains code for a two-stage machine learning framework: 1) Parameter optimization, which enables rapid optimization of chemical vapor deposition (CVD) synthesis parameters of high-branching two-dimensional dendrites through Bayesian optimization; 2) mechanistic comprehension: quantitatively understand the relationship between CVD multi-parameters and material morphology through interpretable machine learning techniques. Between these two parts, we design the data extension module to make the model of the mechanism understanding stage accurate enough.
### Data and code description
- The Bayesian optimization folder holds the code and data for quickly optimizing the CVD parameters for the high fractal dimension of the 2D ReSe2.
* The data expansion folder holds the code and data for filtering the largest dataset by MAE on the Bayesian dataset.
+ The ExplainableML process folder holds the code and data for interpreting XGBoost models via SHAP methods.
