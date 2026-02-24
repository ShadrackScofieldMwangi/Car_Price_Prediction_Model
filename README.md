Car Price Prediction Model

A supervised machine learning regression project that predicts the selling price of used cars based on key vehicle attributes. This repository implements data preprocessing, feature engineering, model training, and evaluation using Python’s scikit‑learn library.

🚗 Project Overview

Used car price prediction is a common regression problem where the goal is to estimate the market value of a car based on features such as year, brand, mileage, fuel type, engine capacity, and more. This model helps users and dealerships estimate fair prices given a set of car characteristics.

The notebook provided demonstrates the full pipeline: from loading the dataset to training and evaluating regression models (including Linear Regression).

📁 Repository Structure

├── Car Price Prediction Model.ipynb     # Main Jupyter Notebook

├── car data.csv                         # Dataset with car features and prices

├── README.md                            # Project documentation

└── (Optional) requirements.txt          # Python dependencies

🧰 Technologies & Libraries

This project uses:

Python

pandas – Data loading and manipulation

NumPy – Numerical operations

scikit‑learn – Model training and evaluation

Matplotlib & Seaborn – Visualization

Jupyter Notebook – Interactive development

🧠 How the Model Works

The notebook guides you through:

Loading the Dataset

The car dataset (car data.csv) contains features like year, present price, kilometers driven, fuel type, seller type, transmission type, owner count, engine size, and more.

Exploratory Data Analysis (EDA)

Visualizing feature distributions and relationships between features and target variable (selling price).

Data Cleaning & Preprocessing

Handling categorical variables using encoding.

Scaling or transforming variables if necessary.

Model Training

Splitting the dataset into training and test sets.

Training regression models (e.g., Linear Regression).

Model Evaluation

Evaluating model performance using metrics such as R² score and mean absolute error.

Prediction

Predicting prices for new car inputs based on trained model.

🛠️ Setup & Installation

1. Clone the Repository
git clone https://github.com/ShadrackScofieldMwangi/Car_Price_Prediction_Model.git
cd Car_Price_Prediction_Model

3. Install Dependencies

Make sure you have Python 3.7+ installed, then install:
pip install pandas numpy scikit-learn matplotlib seaborn notebook

3. Run the Notebook

Launch the Jupyter notebook:

jupyter notebook "Car Price Prediction Model.ipynb"

Then run the cells step‑by‑step to:

Prepare and explore the data

Train regression models

Evaluate performance

Use the trained model for predictions

📊 Example Use Case

Predicting the price of a car with attributes like:

Brand and model year

Fuel type (Petrol/Diesel)

Kilometer reading

Ownership history

Engine capacity and power

The model estimates a likely selling price based on historical trends in the dataset.

📈 Results and Insights

The notebook includes:

Feature correlation analysis

Model performance evaluation

Visualizations showing how features influence predicted prices

These insights help interpret the regression model and understand which factors most affect car pricing.

🤝 Contributing

Contributions are welcome! You can:

⭐ Star the repository

🐛 Report issues or suggest improvements

✨ Submit pull requests
