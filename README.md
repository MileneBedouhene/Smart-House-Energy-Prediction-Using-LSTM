# Smart Home Energy Prediction using LSTM

This repository contains a deep learning model for predicting smart home energy consumption using Long Short-Term Memory (LSTM) networks. The model achieves a loss of **2.98%**.

## Dataset
The dataset used for this project can be found here: [Smart Home Energy Consumption Dataset](https://www.kaggle.com/competitions/soai-lab-smart-home-energy-consumption-prediction/data). It contains time-series data on energy usage, temperature, humidity, and other environmental factors.

## Model and Approach
The model is built using the following steps:
1. **Data Preprocessing**:
   - Handling missing values and outliers.
   - Normalizing numerical features.
   - Reshaping data for sequential modeling.
2. **LSTM Architecture**:
   - Multiple LSTM layers for capturing time dependencies.
   - Dropout layers to prevent overfitting.
   - Fully connected dense layers for prediction.
3. **Training the Model**:
   - Optimized using Adam optimizer.
   - Mean Squared Error (MSE) as the loss function.
   - Early stopping and validation monitoring.
4. **Evaluation**:
   - Achieved a **loss of 2.98%**.
   - Performance measured using RMSE and MAE metrics.

## Results
- Effective energy consumption forecasting with **low loss (2.98%)**.
- Improved accuracy with LSTM's sequential modeling capabilities.
- Robust performance for future energy usage prediction.

## Future Improvements
- Experimenting with transformer-based models for enhanced forecasting.
- Integration with real-time IoT data for live predictions.
- Deployment as a cloud-based API for smart home applications.


## Acknowledgments
- Kaggle for providing the dataset.
- TensorFlow and Keras for deep learning frameworks.

