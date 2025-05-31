# Anomaly Detection using LSTM Autoencoder

This project detects anomalies in jet engine sensor data using LSTM Autoencoders, trained on NASA CMAPSS dataset.

## 📁 Project Structure

- `train_FD002`, `test_FD002`: CMAPSS sensor data
- `best_lstm_autoencoder.h5`: Trained model
- `train_sequences.npy`, `val_sequences.npy`: Preprocessed sequences
- `standard_scaler.save`: Normalization scaler
- `remaining_sensor_columns.xlsx`: Important sensor columns used

## 🚀 How to Run

1. Clone repo
2. Install dependencies:
    ```
    pip install -r requirements.txt
    ```
3. Train or load model from `optimized_lstm_ae.h5`
