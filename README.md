# Prediction-Using-Time-Series-Analysis
This project demonstrates the use of time series analysis to predict weather conditions. It utilizes Python for data processing, feature engineering, and machine learning model implementation, focusing on predicting temperature and weather trends based on historical data.

## Features
 
- **Data Preprocessing**: Handles missing values, performs feature extraction, and ensures data is ready for model training.
- **Exploratory Data Analysis (EDA)**: Visualizes seasonal patterns, trends, and anomalies in the dataset using tools like Matplotlib and Seaborn.
- **Model Implementation**:
  - REGRESSION Models
- **Performance Evaluation**: Evaluates models using metrics such as RMSE, MAE, and R-squared.
- **Visualization**: Presents results with clear and intuitive graphs to interpret model performance.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Data Processing: Pandas, NumPy
  - Visualization: Matplotlib, Seaborn
  - Machine Learning: Scikit-learn, Statsmodels
  - Deep Learning: TensorFlow/Keras (for LSTM)

## Dataset

The dataset used for this project includes historical weather data with features such as temperature, humidity, wind speed, and more. Data is cleaned and processed to extract meaningful insights.

## Results

- **ARIMA Model**: Captured linear trends and seasonal variations effectively for short-term predictions.
- **LSTM Model**: Achieved better accuracy for long-term predictions by capturing non-linear relationships and temporal dependencies.
- **Visualizations**: Highlighted the model's ability to predict temperature variations over time.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Amine-Staali/Prediction-Using-Time-Series-Analysis.git
   ```
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Notebook**:
   Open the Jupyter notebook `weather.ipynb` and execute the cells step-by-step.

## Future Improvements

- Integrate additional features like cloud coverage and precipitation for improved prediction accuracy.
- Deploy the model as a web application using Flask or Django.
- Automate data collection and updates using APIs (e.g., OpenWeatherMap).

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Author

**Mohamed Amine Staali**  
- [LinkedIn](https://www.linkedin.com/in/mohamed-amine-staali-b12275224/)
