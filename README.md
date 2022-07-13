# Insurance-Pricing-XGBoost-Example
This example Xgboost model was created as I was thinking about useful model documentation for boosted tree models. It is far from a perfect model.
The main focus was on demonstrating useful types of plots for improving model interpretability. This example code includes most plots that are mentioned in the CASTF 
Trees Appendix, which is a document that highlights a list of information elements that it may be useful for model reviewers to ask for. The CASTF Trees Appendix is meant
to be applicable to a variety of tree based methods including xgboost, gbm, random forest, bagged trees, etc.

The CASTF Trees Appendix is located here:
https://content.naic.org/sites/default/files/inline-files/CASTF%20Random%20Forest%20Appendix%20%28Trees%29.docx
This document is open for exposure and has not been formally adopted by CASTF (Casualty Actuarial and Statistical Task Force).

This example is a xgboost model targeting insurance claims frequency based on a dataset from CASdatasets. The example includes the following:
- Preliminary Data Assembly
- Hyperparameter Tuning and model selection via grid search
- Plots of Model Fit by hyperparameter value
- Plot of Model Fit by tree for the final model
- Variable Importance Plot
- Partial Dependence Plots
- Shapley Plots
- Decile Plot Lift Chart
- Tree Diagrams
- Actual vs Expected Plots by Variable

