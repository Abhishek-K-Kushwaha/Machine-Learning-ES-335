# MNIST and Fashion-MNIST Classification using MLP

This folder contains implementations for training and evaluating a Multilayer Perceptron (MLP) on the MNIST dataset and comparing its performance against Random Forest (RF) and Logistic Regression models. Additionally, the trained MLP is used to predict on the Fashion-MNIST dataset, and the embeddings from the second layer are visualized using t-SNE.

## Tasks Completed

### MNIST Classification
Trained an MLP with 30 neurons in the first layer, 20 in the second layer, and 10 in the output layer using a stratified subset of the MNIST training dataset. Compared the performance against RF and Logistic Regression models using F1-score and confusion matrix. Observed commonly confused digits.

### t-SNE Visualization
Plotted t-SNE for the output from the layer containing 20 neurons for the 10 digits in the MNIST dataset, both for the trained MLP and an untrained model. Contrasted the results to draw conclusions.

### Fashion-MNIST Prediction
Used the trained MLP to predict on the Fashion-MNIST dataset. Observed the performance and compared embeddings using t-SNE visualization for the second layer between MNIST and Fashion-MNIST images.
