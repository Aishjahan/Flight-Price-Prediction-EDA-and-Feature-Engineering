# Flight Price Prediction: EDA and Feature Engineering

This project focuses on performing **Exploratory Data Analysis (EDA)** and **Feature Engineering** for predicting flight prices. The goal is to clean, analyze, and transform the dataset to extract useful insights and prepare it for machine learning models.

## Project Overview

The dataset contains information on flight prices, along with details such as airlines, routes, and flight durations. The primary objectives of this project are:
- To analyze and understand patterns within the data.
- To perform feature engineering to enhance model performance.
- To preprocess and prepare the data for machine learning algorithms.

### Key Steps in the Project

1. **Data Loading and Preprocessing:**
   - The dataset is loaded using `pandas` for initial inspection.
   - Missing values are handled appropriately through filling or dropping, depending on the context.

2. **Exploratory Data Analysis (EDA):**
   - Descriptive statistics are generated to better understand the structure of the dataset.
   - Visualizations, including plots and graphs, are used to explore relationships between features like flight prices, flight duration, and other attributes.

3. **Feature Engineering:**
   - Extracted new features such as `Date of Journey`, `Month`, `Year`, `Departure Hour`, `Arrival Hour`, `Duration in Hours` and `Minutes`.
   - Categorical features like `Airline`, `Source`, `Destination`, and `Additional_Info` are encoded using **one-hot encoding** for better model compatibility.

4. **Dropping Unnecessary Columns:**
   - Removed features like `Duration` that are no longer necessary after feature extraction, simplifying the data.

5. **Data Preparation:**
   - The dataset is transformed and combined with newly created features, making it ready for model training and testing.

### Next Steps

Future phases of the project will focus on:
- Training machine learning models (e.g., linear regression, decision trees) to predict flight prices.
- Fine-tuning the models to achieve higher accuracy and optimize performance.

## Tech Stack and Libraries

- **Programming Language:** Python
- **Libraries Used:**
  - `pandas` for data manipulation.
  - `numpy` for numerical operations.
  - `matplotlib` and `seaborn` for visualizations.
  - `scikit-learn` for preprocessing and encoding.

## How to Run the Project

To run the project on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Aishjahan/Flight-Price-Prediction-EDA-and-Feature-Engineering.git
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook to view the analysis.
