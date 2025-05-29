# Olympic Medals Prediction Project

## 📌 Overview
A machine learning project that predicts Olympic medal counts for countries based on historical data, using linear regression.

## 🏆 Key Features
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Linear Regression model
- Performance evaluation (MAE: 3.42)

## 📊 Results
- Achieved Mean Absolute Error of 3.42 medals
- Identified strong correlation between previous medals and current performance
- Visualized relationships between athletes, age and medal counts

## 🛠️ Technologies Used
- Python
- Pandas (Data manipulation)
- Scikit-learn (Machine Learning)
- Seaborn (Visualization)

## 🚀 How to Run
1. Clone this repository
2. Install requirements: `pip install pandas scikit-learn seaborn`
3. Run the Jupyter notebook: `jupyter notebook notebooks/Olympic_Medals_Prediction.ipynb`

## 📂 Project Structure
Olympic-Medals-Prediction/
│
├── data/                   # Folder for datasets
│   └── teams.csv           # Original dataset
│
├── notebooks/              # For Jupyter/Colab notebooks
│   └── Olympic_Medals_Prediction.ipynb  # Your cleaned notebook
├── README.md               # Project documentation
│
└── images/                 # For visualizations
    ├── medals_distribution.png
    ├── age_medals_scatterplot.png
    └── pairplot.png
