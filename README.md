Task 1: Lattice Physics

The task involves predicting the Infinite Multiplication Factor (IMF) and Pin Power Peaking Factor (PPPF) using 39 given features.

Chose a NN, due to the large size of database and no. of features.

Also, when I was exploring the dataset, I came across a linked paper discussing the development of novel hyperparameter tuning methods, particularly for neural networks. This influenced my decision to use NN as well.

Key Features: 
1. Hyperparameter tuning with Optuna
2. Deep neural network architecture
3. Multi-output regression model



Task 2: Quarks and Gluons

Task involves making a classification model to distinguish quark or gluon jets.

Upon trying various models, concluded that almost all give the same accuracy.

Finally, used the Logisitic Regression model. 

Key Features:
1. Involves feature manipulatioon to find features with increased f-values
2. A simple Logistic Regression Model
3. Observation: Almost all models gave extremely similar accuracies



Task 3: SMILING Molecules

The task involves predicting molecular similarity using molecular descriptors and SMILES representation.

Encorporated a kNN model after analysing the plots and trying out various other models.

Iterated over to find the best k.

Key Features: 
1. Visualizing the data reveals key details
2. Using KNN-model
3. Iterated to find best-suited k value
