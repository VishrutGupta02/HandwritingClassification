I have used the following techniques which will get you a step by step increment on the test set accuracy

**1. Random Forest Algorithm (93.5% on the Test set)**

> A limited parameter (max_depth = 20) ensemble of only 20 Decision Trees (default value is 100) which prevents overfitting and provides satisfactory accuracy on the validation set (around 95%) 

**2. A Simple Convolutional Neural Network (98.5% on the Test set)**

> A simple CNN with minimal parameters. No advanced techniques like Batch Normalization, Learning Rate Annealer, or Data Augmentation. The validation accuracy will be around 99%

**3. CNN with Data Augmentation (99.35% on the Test set)**

> Apply Data Augmentation on the CNN along with learning rate annealer and Nadam optimizer. The validation accuracy was around 99.5% at 20 epochs

**4. An ensemble of CNNs (99.67% on the Test set)**

> Combined 7 previously designed CNNs to work on random shuffled subsets of training and validation data. The ensemble technique used is Bagging. The validation accuracy achieved is 99.55%!
