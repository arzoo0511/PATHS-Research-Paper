# PATHS – Predictive AI Traffic Handling System
PATHS (Predictive Analysis of Traffic Handling Systems) is a data-driven urban traffic analytics framework that combines computer vision, time-series forecasting, and statistical anomaly detection to support proactive traffic monitoring and congestion analysis.
The system processes CCTV traffic footage to extract vehicle counts, constructs state-level time-series signals, and predicts short-term traffic evolution using recurrent neural networks. An anomaly detection layer identifies spikes, drops, and outliers in traffic flow to assist strategic traffic planning.
---
## Key Features
- YOLOv8-based vehicle detection from CCTV footage  
- Frame-wise vehicle count aggregation and smoothing  
- Short-term traffic forecasting using RNN, LSTM, and GRU  
- Statistical anomaly detection for congestion profiling  
- State-wise traffic behavior analysis  
- Modular pipeline for future intelligent transport integration  
---
## Usage
1. Extract frames from traffic videos  
2. Run YOLO detection to obtain vehicle counts  
3. Generate time-series sequences  
4. Train or load forecasting models  
5. Apply anomaly detection for traffic insights  
---
## Purpose
This repository accompanies the research work on PATHS and is intended for academic, experimental, and reproducibility purposes.
