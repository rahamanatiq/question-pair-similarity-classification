# Question Pair Similarity Classification

This task aims to develop and assess an NLP system that can identify semantic similarity between question pairs. The report details the complete development workflow, encompassing Exploratory Data Analysis, Text Preprocessing, Model Creation, Model Evaluation and Model Tuning and Hyperparameter Optimization.

# (1)	Environment Settings

•	Platform: Kaggle platform is used for the assigned task.

•	Dataset: Provided dataset train.csv and additional dataset glove.6B.100d.txt is used for embeddings.

•	Keras Conflict: To avoid keras conflict with Kaggle system install the intended version (Provided in the python code)



# (2)	Model Creation 
The following models are implemented:

•	Baseline Model: Logistic Regression is used as a benchmark model by utilizing the Hybrid (TF-IDF + Glove Embedding) features.

•	Deep Learning Model: Siamese + LSTM Model 

•	Artificial Neural Network (ANN): ANN is also implemented. An ANN is a computational model inspired by the human brain, consisting of interconnected layers of nodes (neurons) that learn to map inputs to outputs by adjusting connection weights.

•	Transformer Learning Model:

I.	BERT

II.	DistilBERT


# (3)	Model Evaluation
•	Each model is evaluated thorough classification metrics (Accuracy, precision, recall, F1 score), Confusion matrix and AUC-ROC curve (Provied in the python code)


# (4) Model Tuning and Hyperparameter Optimization
Different architectures, activation functions (sigmoid), and optimizers (Adam) are used.

