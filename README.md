# 🌦️ Seattle Weather Analysis and Prediction

## 📌 Project Overview

This project uses Python to analyze Seattle weather data and predict weather conditions using Machine Learning.

The project explores weather information such as precipitation, maximum temperature, minimum temperature, wind speed, and weather conditions. It also uses different charts to visualize the data and a Decision Tree Classifier to predict weather categories.

This project is created using Google Colab as part of my Data Science learning journey.

## 🎯 Objectives

- Analyze Seattle weather data using Python.
- Explore temperature, precipitation, and wind speed.
- Count different weather conditions.
- Create charts to understand weather patterns.
- Build a Machine Learning model to predict weather conditions.
- Evaluate model performance using accuracy score.

## 📂 Dataset

**Dataset name:** `seattle-weather.csv`

The dataset contains the following columns:

| Column | Description |
|---|---|
| `date` | Date of weather observation |
| `precipitation` | Amount of precipitation |
| `temp_max` | Maximum temperature |
| `temp_min` | Minimum temperature |
| `wind` | Wind speed |
| `weather` | Weather condition |

Weather categories include rain, sun, drizzle, snow, and fog.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

## 📊 Data Visualizations

This project includes the following visualizations:

1. **Bar Chart:** Displays the number of days for each weather condition.
2. **Line Chart:** Compares maximum and minimum temperatures.
3. **Wind Speed Chart:** Shows changes in wind speed.
4. **Precipitation Chart:** Visualizes precipitation values.
5. **Pie Chart:** Displays the percentage distribution of weather conditions.
6. **Histogram:** Shows the distribution of maximum temperatures.
7. **Scatter Plot:** Shows the relationship between maximum temperature and wind speed.
8. **Heatmap:** Displays correlations between numerical weather features.
9. **Weather Count Plot:** Visualizes the frequency of weather categories.

## 🤖 Machine Learning Model

A **Decision Tree Classifier** is used to predict weather conditions.

### Input Features
- Precipitation
- Maximum temperature
- Minimum temperature
- Wind speed

### Target Variable
- Weather condition

### Model Workflow
1. Load the weather dataset.
2. Prepare input features and target variable.
3. Split the data into training and testing sets.
4. Train the Decision Tree Classifier.
5. Predict weather conditions on the test data.
6. Calculate the model's accuracy score.

The dataset is split using an 80% training set and a 20% testing set.

## ⚙️ How to Run the Project

### Step 1: Download the Project
Download the Jupyter Notebook and `seattle-weather.csv` dataset.

### Step 2: Open Google Colab
Visit [Google Colab](https://colab.research.google.com/).

### Step 3: Upload the Notebook
Upload the `.ipynb` file to Google Colab.

### Step 4: Upload the Dataset
Run the notebook's file-upload cell and select `seattle-weather.csv`.

### Step 5: Run the Code
Run the notebook cells in order to perform data analysis, generate visualizations, train the model, and evaluate its accuracy.

## 📁 Project Structure

```text
Seattle-Weather-Analysis/
│
├── Seattle_Weather_Analysis.ipynb
├── seattle-weather.csv
└── README.md
```

Replace the notebook filename above with your actual filename if needed.

## 📚 Key Learnings

- Reading CSV files using Pandas.
- Exploring datasets and selecting columns.
- Checking and handling missing values.
- Analyzing weather conditions.
- Creating different types of data visualizations.
- Splitting data into training and testing sets.
- Training a Decision Tree Classifier.
- Making predictions and evaluating model accuracy.

## 🚀 Future Improvements

- Improve prediction accuracy through model tuning.
- Compare Decision Tree with other classification algorithms.
- Create an interactive weather analysis dashboard.
- Add more performance metrics, such as a confusion matrix and classification report.
- Explore seasonal weather patterns.

## 👨‍💻 Author

**Your Name**

GitHub: https://github.com/GuruprasadSunagar

## ⭐ Acknowledgment

This project was developed for learning and practicing Python, Data Analysis, Data Visualization, and Machine Learning.

If you find this project useful, please consider giving the repository a star!
