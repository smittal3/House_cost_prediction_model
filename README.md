# House price prediction model
Built a neural network to predict whether a house is above or below median price based on data from Zillow's Home Value Prediction Kaggle Competition. The price of the house is dependant on 10 input features such as Lot Area (Sq ft), Overall Quality (1-10), Number of Full Bathrooms, Number of Half Bathrooms, etc. 
The data set was normalized using the MinMaxScaler from sklearn. The model is built using the Keras sequential model. Matplotlib is used to visualize loss and accuracy (training vs validation data set)
