# SmartKisan AI – AI-Powered Crop Yield Prediction & Optimization

## Overview

SmartKisan AI is a machine learning-based web application designed to help farmers make better agricultural decisions. It analyzes historical agricultural data and environmental factors to predict crop yield and support suitable crop selection.

The system uses data analytics and machine learning techniques to understand patterns in agricultural data and generate predictions based on input parameters. It also integrates real-time weather information to provide additional environmental insights.

## Objectives

- Help farmers make informed crop selection decisions.
- Predict approximate crop yield using machine learning.
- Analyze agricultural and environmental data to identify useful patterns.
- Simplify agricultural information through an easy-to-use web interface.
- Support farmers through a multilingual application.

## Key Features

- **Crop Yield Prediction:** Predicts approximate crop yield using a trained machine learning model.
- **Data Preprocessing:** Handles missing values, duplicate records, and inconsistent data.
- **Agricultural Data Analytics:** Analyzes relationships between rainfall, temperature, crop types, and yield.
- **Data Visualization:** Uses charts and graphs to present agricultural trends and patterns.
- **Weather API Integration:** Retrieves real-time weather information using the OpenWeatherMap API.
- **Database Management:** Stores farmer details, farm information, and prediction history.
- **Multilingual Interface:** Makes the application more accessible to farmers through multiple languages.

## Technologies Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Frontend | HTML, CSS, JavaScript |
| Backend | Flask |
| Database | MySQL |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib |
| Machine Learning | Scikit-learn |
| ML Algorithm | Random Forest Regressor |
| API Integration | OpenWeatherMap API |

## Data Analytics and Preprocessing

The agricultural dataset is processed and analyzed using Python libraries.

### Data Preprocessing

- Load agricultural datasets using Pandas.
- Identify missing values and duplicate records.
- Clean and organize the dataset.
- Handle missing and inconsistent values.
- Select relevant features for machine learning.

### Exploratory Data Analysis (EDA)

- Analyze rainfall, temperature, humidity, and crop yield.
- Study relationships between environmental factors and agricultural production.
- Compare crop yield across different conditions.
- Identify patterns and trends in historical agricultural data.

### Data Visualization

- Generate charts and graphs using Matplotlib.
- Visualize agricultural trends and feature relationships.
- Present analytical results in an understandable format.

## Machine Learning Workflow

1. Collect historical agricultural data.
2. Preprocess and clean the dataset.
3. Perform exploratory data analysis.
4. Select relevant features for prediction.
5. Split the dataset into training and testing sets.
6. Train the Random Forest Regressor model.
7. Evaluate model performance using test data.
8. Generate crop yield predictions based on user inputs.

## Weather API Integration

The application integrates the OpenWeatherMap API to retrieve real-time weather information. This information provides additional environmental context for agricultural analysis and crop-related decisions.

## Database Management

MySQL is used to manage and store application data, including:

- Farmer information
- Farm details
- Agricultural inputs
- Crop prediction history

## Project Structure

```text
SmartKisan-AI/
│
├── app.py
├── run.py
├── model.py
├── config.py
├── requirements.txt
├── pyproject.toml
│
├── templates/
├── static/
├── models/
├── data/
│
└── README.md
```

Note: Adjust this structure to match the actual files and folders in your repository.

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Basheer909/SmartKisan-AI.git
```

### 2. Navigate to the Project Directory

```bash
cd SmartKisan-AI
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Add the required database credentials and OpenWeatherMap API key to your environment configuration. Do not upload secret keys or passwords to GitHub.

### 5. Run the Application

```bash
python run.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## Team Members

- Md Basheer Khan
- N Harika
- K Pranav
- N Nikhil

## Future Enhancements

- Improve prediction performance with additional agricultural datasets.
- Introduce more advanced data analytics and visualization.
- Expand multilingual support.
- Add additional crop recommendations based on environmental conditions.
- Develop a mobile-friendly application for farmers.

---

**SmartKisan AI – Using Data Analytics and Artificial Intelligence to Support Smarter Agricultural Decisions.**
