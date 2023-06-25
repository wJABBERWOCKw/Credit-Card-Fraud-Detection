# Credit-Card-Fraud-Detection

Dataset:- https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Detecting credit card fraud involves a combination of preventive measures and ongoing monitoring.

 Implementing advanced machine learning algorithms that can analyze patterns, identify anomalies, and detect fraudulent activities based on historical transaction data. These algorithms can learn from past instances of fraud and improve their accuracy over time.

 Neural Networks: Deep learning models, such as feed-forward neural networks or recurrent neural networks (RNNs), can learn complex patterns in the data and are capable of capturing non-linear relationships. They often require large amounts of labeled training data and computational resources.

 Given the highly unbalanced nature of the dataset, where fraudulent transactions account for only 0.172% of all transactions, it is important to use neural network techniques that can effectively handle class imbalance.

Oversampling or Undersampling: One approach to address class imbalance is to either oversample the minority class (fraudulent transactions) or undersample the majority class (non-fraudulent transactions). This can be done by randomly replicating instances from the minority class or randomly removing instances from the majority class. These techniques can help balance the class distribution and improve the model's ability to learn from the minority class.


The neural network model I used  is a basic architecture with three layers:

The first layer is a dense layer with 64 units and 'relu' activation function. It takes input with the shape of the number of features in the training data (X_train.shape[1]).


The second layer is another dense layer with 32 units and 'relu' activation function.


The final layer is a dense layer with 1 unit and 'sigmoid' activation function. This layer is typically used for binary classification problems as it outputs a probability value between 0 and 1.


Overall, this model consists of two hidden layers with 'relu' activation and one output layer with a 'sigmoid' activation function. It is commonly used for binary classification tasks.

Test Accuracy: 99.91%
​
