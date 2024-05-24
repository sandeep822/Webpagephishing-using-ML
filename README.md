# Webpagephishing-using-ML

#Pgrimes6 - LSTM + CNN Phishing Detection

<img width="644" alt="image" src="https://github.com/sandeep822/Webpagephishing-using-ML/assets/50867031/32e20d43-a99e-408f-98b0-97ac18983859">

The above demonstrates the construction and training of a phishing website detection model using a combination of Long Short-Term Memory (LSTM) and Convolutional Neural Networks (CNNs). Initially, the necessary libraries and dependencies are imported, including NumPy, Pandas, TensorFlow, and scikit-learn. The dataset is loaded from a CSV file, and preprocessing steps are undertaken to prepare the data for model training. The target variable is encoded, and the dataset is split into training and validation sets. Notably, the input data is reshaped to accommodate the requirements of the Conv1D layer in the model architecture. The model architecture consists of a series of layers, including BatchNormalization, Conv1D, MaxPooling1D, Dropout, LSTM, and Dense layers. The model is compiled using the Adam optimizer and binary cross-entropy loss function. Training is conducted with early stopping implemented to prevent overfitting, and the training history is captured for visualization. The model achieves a best validation accuracy of 72.50% and a corresponding best validation loss of 0.6084 after training for 54 epochs.

![image](https://github.com/sandeep822/Webpagephishing-using-ML/assets/50867031/b6df480a-07f8-44d9-bb9b-265422d2c76f)

