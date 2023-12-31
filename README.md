<img width="258" alt="image" src="https://github.com/oubbatimo/Housing-Price-Prediction/assets/92709052/1e9380cc-7633-4e79-9a3c-e0dd9bb55f1d">

# Housing Price Prediction using Deep Learning
In this project I trained feedforward neuron network using the training dataset california_housing_train.csv to estimate housing prices.

This dataset contains information regarding the demography (income, population, house occupancy), the location of the house (latitude, longitude), and some general infos regarding the house (number of rooms, number of bedrooms, age of the house). These factors seem to be correlated to the housing price, i.e. median house value. 

Based on this hypothesis we trained feedforward neuron network with the following architecture:
8 Inputs, 2 Hidden Layers, and 1 output (see figure)

<img width="459" alt="image" src="https://github.com/oubbatimo/Housing-Price-Prediction/assets/92709052/10cc4c2a-e90f-4c29-a269-e6d3d9b327e2">


![image](https://github.com/oubbatimo/Housing-Price-Prediction/assets/92709052/e1c5c1e5-7398-4eba-8c7b-069aca594c3b)

The Neural net could deliver satisfactory preliminary results due to the generalization on test data. Further tests should be conducted using other machine learning models, including new inputs such as distance to the center, renovation condition, area of the house, etc.
