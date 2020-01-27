# Breast-Cancer-detection
Predicting nature of a breast mass to be malignant (cancerous) or Benign (non-cancerous)
Class distribution: 357 benign, 212 malignant

Feature Analysis and Selection:
ANOVA (all independent variables are continuous, so needed ANOVA to check relationship with the categorical target)
Correlation-heatmap (many continuous-independent variables were collinear, so needed a removal to reduce processing and overfitting)
Lasso-Linear and Random-Forest regression's feature importance/selection technique

Model development:
Decision Trees, 
Random Forest,
Logistic Regression,
K-Nearest-Neighbours
Gaussian Naive-Bayes
Support-Vector-Classifier
DNN using Keras

Have compared the accuracy metrics like accuracy-scores and False-Negative-Rate between all the above applied models over the dataset.
