# ☀️ Solar Power Forecasting using LSTM & Transformers

##  Overview
Accurate solar power forecasting is essential for efficient energy management and grid stability in renewable energy systems. This project applies deep learning techniques to predict solar power generation using historical time-series data.

The system compares traditional sequence models like **LSTM (Long Short-Term Memory)** with advanced architectures such as **Transformers** to evaluate performance and forecasting accuracy.



##  Objectives
- Predict solar power generation using historical data  
- Compare performance of LSTM and Transformer models  
- Improve forecasting accuracy using deep learning  
- Analyze model performance using evaluation metrics  
- Explore the potential of AI in renewable energy systems  



##  Tools & Technologies
- Python  
- TensorFlow / Keras  
- NumPy  
- Pandas  
- Matplotlib  
- Google Colab  



##  Dataset
- Time-series dataset containing:
  - Solar power output (kW)
  - Timestamp (Date & Time)
  - Environmental factors (if available)



##  Methodology

### 1. Data Preprocessing
- Handled missing values  
- Normalized data for deep learning models  
- Converted data into time-series sequences  

### 2. Model Development

#### 🔹 LSTM Model
- Captures temporal dependencies in sequential data  
- Suitable for time-series forecasting  
- Trained using sliding window approach  

#### 🔹 Transformer Model
- Uses attention mechanism for sequence learning  
- Handles long-term dependencies more effectively  
- Provides improved prediction performance  



##  Model Evaluation

Performance was evaluated using:

- RMSE (Root Mean Square Error)  
- MAE (Mean Absolute Error)  
- sMAPE (Symmetric Mean Absolute Percentage Error)  

###  Results

| Model        | RMSE (kW) | MAE (kW) | sMAPE (%) |
|-------------|----------|----------|-----------|
| LSTM        | 11.74    | 8.01     | 80.24     |
| Transformer | 9.73     | 6.92     | 81.28     |

 Transformer model showed better performance in terms of RMSE and MAE.



##  Visualization
- Actual vs Predicted power output  
- Model comparison graphs  
- Error distribution plots  



##  Key Insights

- Transformer models outperform LSTM in capturing long-term dependencies  
- Solar power generation shows strong time-based patterns  
- Deep learning significantly improves forecasting accuracy  
- Accurate forecasting can optimize energy distribution  



##  Real-World Impact

This project can help:

- Energy companies optimize power distribution  
- Reduce energy wastage  
- Improve grid stability  
- Support renewable energy adoption  



##  Future Improvements

- Integrate weather data for improved accuracy  
- Deploy as a real-time forecasting system  
- Build a web dashboard for monitoring predictions  
- Experiment with hybrid models (LSTM + Attention)  



##  Project Structure

---

##  Author

**Sachin Moktan**  
Data Analyst | AI/ML Engineer  

📍 Kathmandu, Nepal  
🔗 LinkedIn: https://www.linkedin.com/in/sachinmoktan/  

---

## ⭐ If you found this project useful, consider giving it a star!
