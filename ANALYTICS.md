# ANALYTICS

TRAIN DATA → DEV/VALIDATION DATA → TEST DATA

- If dev metrics are biased or overfitting, we need tuning without leaking test data
- If the dev metrics is performing well and test data fails to perform we need to make dev set similar to test set for our model to learn
- Divide data 60-20-20 for normal data set
- For a larger dataset around millions → Prefer 98-1-1 or 96-2-2

TECHNIQUES TO IMPLEMENT MODEL TUNING

- More Data
- Regularization → L1, L2
- Trying Bigger Networks/Deeper Neural Networks → if the model is underfitting or not learning
- Trying Smaller Networks → if the model is overfitting
- Try Dropouts → Dropping insignificant Features
- #work on hidden inputs → no. of nodes in a layer
- Using **ADAM** optimizer instead of Simple Gradient Descent and providing more training time to find optima

COMPARING MODELS

- Take the average of results/metrics
- Use ranking criteria for equal opportunities to every metric
- Use single measure instead of multiple → F-score instead of Precision & Recall
-