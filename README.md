pyGlmNet is a Python package providing efficient and scalable procedures for fitting the entire regularization path of generalized linear models (GLM) with lasso or elastic-net penalties. It is inspired by the highly optimized glmnet package for R, extending its functionalities to the Python ecosystem.

### Capabilities of pyGlmNet:

Fits linear regression (Gaussian), multi-task Gaussian, logistic, multinomial (grouped or not), Poisson regression, and Cox models.
Utilizes a path-wise cyclical coordinate descent algorithm, optimizing for speed and efficiency.
Allows for a variety of GLM families beyond the built-in ones, accommodating a wide range of applications.
New Features in pyGlmNet Version 1.0:

Relaxed Fitting: Models along the regularization path can be refit without regularization. Cross-validation can select from these models or from specified mixtures of relaxed and regular fits.
Progress Monitoring: Includes a progress bar to observe computation advancements.
Model Assessment Tools: Features performance assessment functions for evaluating models on test data, including all measures from cross-validation, confusion matrices, and ROC plots for classification models.
Enhanced Output Display: Introduces print methods for clean and informative cross-validation result displays.
Matrix Building Functions: Provides utility functions for constructing the design matrix X, with support for one-hot encoding, handling missing values, and creating sparse matrices when appropriate.
Unpenalized Model Fitting: Ability to fit an unpenalized single version of any GLMs supported by pyGlmNet.

### Installation:
<code> pip install pyGlmNet
</code>

### Usage:

Quickstart guide and examples are provided in the documentation to help you get started with pyGlmNet.

### Contributing:

Contributions to pyGlmNet are welcome! Please read our contributing guidelines to learn about how you can contribute to this project.

Citation:

If you use pyGlmNet in your research, please cite the original glmnet R package papers:

Friedman, J., Hastie, T., and Tibshirani, R. (2010)
Simon, N. et al. (2011)
Tibshirani, R. et al. (2012)
Simon, N., Friedman, J., and Hastie, T. (2013)
License:

pyGlmNet is open-source and licensed under the MIT License.

