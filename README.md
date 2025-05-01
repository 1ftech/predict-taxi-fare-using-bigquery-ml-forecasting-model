# 🚖 Predict Taxi Fare with BigQuery ML (BQML)

This project demonstrates how to use Google BigQuery and BigQuery ML (BQML) to forecast NYC taxi fares. You'll explore public datasets, build a machine learning model using SQL, and evaluate forecasting performance — all directly in BigQuery.

## 🎯 Learning Objectives

- ✅ Use BigQuery to find and explore public datasets
- ✅ Query and analyze the NYC taxi cab dataset
- ✅ Create training and evaluation datasets for batch prediction
- ✅ Build a forecasting model using linear regression in BQML
- ✅ Evaluate the performance of the machine learning model

## 🛠 Tools & Technologies

- **Google BigQuery**
- **BigQuery ML (BQML)**
- **SQL**
- **NYC TLC Public Dataset**

## ▶️ Steps to Run

1. **Explore the Dataset**  
   Use `Explore-NYC-cab-data.sql` to locate and explore the NYC Taxi Trip dataset in BigQuery's public datasets.

2. **Feature Engineering**  
   Run `Feature-selection-and-creating-training-data.sql` to prepare the dataset for modeling.

3. **Train the Model**  
   Execute `Model-creation-and-specify-model-options.sql` to train a linear regression model using BQML.

4. **Evaluate the Model**  
   Use `Evaluate-classification-model-performance.sql` to assess the model's performance.

5. **Make Predictions**  
   Run `Predict-taxifare-amount.sql` to generate fare predictions.

## 📊 Sample Output

- Daily predicted fare amounts
- Evaluation metrics (e.g., mean absolute error, RMSE)

## 📚 Dataset Info

- **Source**: [NYC TLC Trip Records](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- **Access**: `bigquery-public-data.new_york.tlc_yellow_trips`

## 📄 License

This project is based on the Google Cloud Skills Boost lab and is intended for educational purposes.

