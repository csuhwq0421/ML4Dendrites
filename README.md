# ML4Dendritic
## ML4Dendritic is the Official Repository for the paper ‘Machine intelligence-guided growth and multifactorial mechanism deciphering of two-dimensional ReSe2 dendrites’.
Taking the dendrite growth of rhenium selenide (ReSe2) materials as an example, ML4dendritic contains code for a two-stage machine learning framework: 1) Parameter optimization, which enables rapid optimization of chemical vapor deposition (CVD) synthesis parameters of high-branching two-dimensional dendrites through Bayesian optimization; 2) mechanistic comprehension: quantitatively understand the relationship between CVD multi-parameters and material morphology through interpretable machine learning techniques. Between these two parts, we design the data extension module to make the model of the mechanism understanding stage accurate enough.

## Data and Code Description
- **Bayesian optimization** : designed to quickly optimize the CVD parameters for the high fractal dimension of the 2D ReSe2.
* **Data expansion**  : designed to filter the data points with the largest MAE on the Bayesian dataset and then conduct experiments near these points to supplement the data.
+ **Explainable ML process** : designed to interprete the XGBoost model via SHAP techniques.

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

```
## Citation

## License
This project is licensed under the terms of the MIT license. See [LICENSE](https://github.com/csuhwq0421/ML4Dendritic/blob/main/LICENSE) for additional details
