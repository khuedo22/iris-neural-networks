# iris-neural-networks
This project is intended for me to learn how to build a neural network classification model using [Iris Species](https://www.kaggle.com/datasets/uciml/iris) dataset. My goal is to build a neural network model that predicts the iris species given the length and width of the petal and sepal with the highest accuracy possible. The technologies used are Python, specifically the Keras library to build the model. The data cleaning and exploratoy analysis were done using Pandas, matplotlib, and Seaborn.  

resources used: https://machinelearningmastery.com/tutorial-first-neural-network-python-keras/

## Brief Workflow
1. loaded data, cleaned data, split data into X and Y components, then split into testing and training
2. performed exploratory data analysis by visualizing scatterplot, comparing relationship between class, and sepal and petal sizes
3. determined how many hidden layers and nodes to use after exploratory data analysis
4. defined Keras sequential model
5. compiled Keras model
6. fit Keras model using training data
7. evaluated accuracy of model
8. use model to predict testing data
