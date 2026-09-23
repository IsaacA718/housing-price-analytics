🏠 Housing Price Analytics

<p align="center"><strong>Predicting Housing Prices Using Machine Learning</strong></p>

<p align="center">
  <a href=https://colab.research.google.com/drive/19Lg9iMx-cDXiO4e34o7Xqwaqc4IQ1KfY?usp=sharing>📓 Open in Google Colab</a> ·
  <a href="https://github.com/IsaacA718">👨‍💻 GitHub Profile</a>
</p>

✨ Overview

This project explores housing prices using the Ames Housing Dataset and develops a machine learning workflow for predicting residential property sale prices.

The project follows an end-to-end data science process, beginning with data exploration and cleaning and progressing through statistical analysis, visualization, feature preparation, model development, and evaluation.

🎯 Problem Statement

Housing prices are influenced by many factors, including property size, location, quality, condition, amenities, and age. The goal of this project is to use historical housing data to identify important pricing factors and build a model capable of predicting SalePrice.

📊 Dataset

The project uses the Ames Housing Dataset, downloaded through Kaggle.

According to the project analysis, the dataset contains:

2,930 residential property observations

82 columns

Numerical and categorical variables

Residential sales from Ames, Iowa

SalePrice as the target variable

Example feature categories

🏠 Structural characteristics

📍 Neighborhood and location

🛁 Bathrooms and living areas

🚗 Garage characteristics

🔥 Fireplace and basement features

🌳 Lot and exterior characteristics

📅 Year built and remodeling information

🔎 Exploratory Data Analysis

The project investigates the structure and quality of the dataset before modeling.

Data Preparation

The notebook addresses:

Missing numerical values using median imputation

Missing categorical values using "None"

Data-type verification

Examination of potential outliers

Removal of extreme Gr Liv Area observations above 4,000 square feet

Initial Findings

🤖 Machine Learning

The project develops a regression-based machine learning workflow to predict housing prices.

The notebook explores:

Feature preparation

Categorical-variable handling

Train/test splitting

Regression modeling

Model comparison

Hyperparameter tuning

Model evaluation

📁 Repository Structure

housing-price-analytics/
├── Housing_Price_Analytics.ipynb    # Complete analysis and ML workflow
├── README.md                         # Project documentation
└── .gitignore                        # Notebook / Python exclusions

🚀 Run the Project

Option 1 — Google Colab

Open the notebook in Google Colab:

📓 Launch Housing Price Analytics →

Option 2 — Jupyter Notebook

Clone the repository:

git clone https://github.com/IsaacA718/housing-price-analytics.git
cd housing-price-analytics

Then open:

Housing_Price_Analytics.ipynb

The notebook expects the AmesHousing.csv dataset used in the original analysis. If the dataset is not included in the repository, it must be supplied separately before running the notebook from scratch.

🧠 What I Practiced

This project provided hands-on experience with:

Data cleaning and preprocessing

Exploratory data analysis

Statistical analysis

Data visualization

Feature preparation

Regression modeling

Random Forest modeling

Hyperparameter tuning

Cross-validation

Model evaluation

Feature importance

Translating technical analysis into business context

👨‍💻 Author

Isaac Arika

IT Infrastructure • Data • Systems

[GitHub](https://github.com/IsaacA718) · [LinkedIn](https://www.linkedin.com/in/isaac-arikax718/)

---

<p align="center">Built to explore how data and machine learning can support better housing-price decisions.</p>
