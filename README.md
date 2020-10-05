# Unintended-Bias-in-Toxicity-Classification

The repo contains notebooks for the Jigsaw Unintend Bias in Toxicity Classification contest hosted on Kaggle

- Kaggle : https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification
- Discord Bot Based on this : https://github.com/Sid200026/ToxicBot

### Score 1

<img src="https://github.com/Sid200026/Unintended-Bias-in-Toxicity-Classification/blob/main/Output/Attempt1.png" />

### Score 2

<img src="https://github.com/Sid200026/Unintended-Bias-in-Toxicity-Classification/blob/main/Output/Attempt2.png" />

## Methodology

Both the attempts use GloVe embeddings. However Attempt2 uses a custom loss function but the AUC-ROC score was less than Attempt1. Also BERT embedding mostly would have givven a superior result, however it wasn't possible to run it on Google Colab as the ram limit exceeded everytime. An alternative was to train on only 40% of the dataset using BERT but we could lose some valuable information.
