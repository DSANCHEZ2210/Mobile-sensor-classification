# Mobile Sensor Classification

This project classifies physical activities based on smartphone motion sensor data, using readings from the accelerometer and gyroscope. The model was optimized for real-time inference.

## Objective
Detect different physical activities (e.g., walking, running, standing) from raw mobile sensor data collected via Phyphox app.

## Tools & Libraries
- Python
- XGBoost, MLP, SVM
- Scikit-learn
- Feature extraction from time-domain and frequency-domain signals
- Real-time classification with Streamlit (optional)

## Results
- Accuracy: up to **98%** with XGBoost
- Real-time predictions successfully tested with unseen data
- Feature selection and cross-validation included

## Files
- `data/`: sensor readings (accelerometer & gyroscope)
- `models/`: trained models (.pkl)
- `notebooks/`: feature engineering & model training
- `streamlit_app.py`: optional UI for real-time use

## How to Run
```bash
python train_model.py
streamlit run streamlit_app.py  # for real-time classification
