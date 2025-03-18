# Stock-price-prediction-using-a-hybrid-CNN-LSTM-model
Stock price prediction using a hybrid CNN+LSTM model on Nvidia stock data (2014–2024). 
This project focuses on predicting Nvidia stock prices from 2014 to 2024 using a hybrid deep learning model that combines Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks. The goal was to evaluate how different batch sizes (64, 128, and 256) impact the model's performance while maintaining a constant learning rate of 0.0001.

The CNN layers were used to extract spatial features from the time series data, while the LSTM layers captured temporal dependencies. The model was trained and evaluated using standard performance metrics such as Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared score to assess accuracy and robustness.

This project highlights how batch size influences the learning dynamics and predictive power of a deep learning model under a fixed learning rate. Libraries such as:
1. NumPy
2. Pandas
3. Seaborn
4. Matplotlib
5. Scikit-learn
6. TensorFlow 
