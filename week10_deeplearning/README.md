# activation functions
- ReLu - for hidden layers. Address vanishing gradient problem. return 0 or greater
- Tanh - returns between -1 and 1 
- Sigmoid - binary probability between 0 and 1 
- Softmax - multi-class classification 
- Linear (Identity) - for regression 

# Loss Function 
- squared differences - regression 
- negative log likelihood - classification
- cross-entropy loss - classificaiton

# Gradient Descent / Backpropagation 
-  Stochastic Gradient Descent - one data point at a time
- Adam - usually the best because of bias correction
- small step size to find best fit, bigger to train faster

# Regularization
- Weight Decay - weights go to zero 
- Early Stopping 
- Data Augmentation (creating new data)
- Dropout 
- Batch Normalization - normalize the data in the model