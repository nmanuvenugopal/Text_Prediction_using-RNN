# Text_Prediction_using-RNN

The entire process is divided into following parts:
1. Processing text (reading the corresponding documents and extracting the texts).
2. Cleaning text (The punctuations and special characters needed to be removed from the text before feeding it to the model).
3. Tokenizing the text using Spacy library.
4. Creating the batch sequnces.
5. Tokeninizing the input to numeric format using the Keras tokenozer module.
6. Converting the Sequences to a numpy array.
7. Separating the sequnces into features and label for training and testing puposes. All the words except the last word forms "X" (features) and last word in the sequence forms the "y" (labels).
8. Building a Deep Neural Network.
9. Training the Model with the X and y.
10. Make a prediction 
11.Evaluating the performance of the model.
