# KAGGLE-AIRPLANE CRASHES

## Team Members
* Anna Borosh
* Ivan Kliuchyshche
* Hans Eduard Säre

## Project Description

This project aims to analyze airplane crash data to understand trends, patterns, and factors influencing survivability. Using data visualization and predictive modeling, the project provides actionable insights to improve aviation safety.

## Project Goals
- **Data Cleaning**: Standardize and preprocess the dataset for analysis.
- **Data Visualization**: Explore trends, identify hotspots, and visualize key insights.
- **Survivability Model**: Develop a machine learning model to predict survivability based on key factors.
- **Insights & Recommendations**: Interpret the model to derive actionable insights for aviation safety.

---

## Project Structure
- **data/**: Contains the dataset.
- **notebooks/**: Jupyter notebooks for data cleaning, visualization, and model building.
- **reports/**: Final report and visual summaries.
- **README.md**: This file, providing an overview of the project.

## Installation and Setup

1. **Clone the Repository**:
   ```
   git clone https://github.com/Janspitoy/AirplaneCrashes.git
   cd AirplaneCrashes
   ```
2. **Install Required Libraries**:
    ```
    pip install -r requirements.txt
    ```
3. **Run the Notebooks**:
    ```
    jupyter notebook
    ```

## Usage

1. **Data Cleaning**:
   - Run `notebooks/data_cleaning.ipynb` to clean and preprocess the dataset.

2. **Data Visualization**:
   - Explore visualizations by running `notebooks/visualizations.ipynb`.

3. **Modeling**:
   - Use `notebooks/modeling.ipynb` to train and evaluate the survivability model.

4. **Reports**:
   - View the findings and insights in `reports`.

---

## Dataset

- **File**: `data/Airplane_Crashes_and_Fatalities_Since_1908.csv`
- **Source**: [Kaggle - Airplane Crashes and Fatalities](https://www.kaggle.com/datasets/nayansubedi1/airplane-crashes-and-fatalities-upto-2023)
- **Description**: Contains information on airplane crashes, including dates, locations, operator, aboard, fatalities, and more.

## Learning Data

- **File**: `data/learning_data.csv`
- **Description**: Contains data columns for training a model to predict survivability in airplane crashes. The dataset includes vectorized columns for features such as region, time of the crash, flight category, and the cause of the crash.
  
- **Data Format**:
    - `Date`: Date of the crash in `mm/dd/yyyy` format (e.g., `01/01/1999`).
    - `Region_Vector`: A vector representing the region of the crash. Example: `[0, 0, 0, 0, 0, 0, 0]` where `['America', 'Europe', 'Unknown', 'Other', 'Oceania', 'Asia', 'Africa']`.
    - `Aboard`: The number of people aboard the aircraft (e.g., `1.0`).
    - `Fatalities`: The number of fatalities in the crash (e.g., `1.0`).
    - `Survives`: A binary value indicating if anyone survived the crash. `1` if survived, `0` if not.
    - `Time_Vector`: A vector representing the time of the crash. Example: `[0, 0, 0, 0, 0]` where `['Unknown', 'Morning', 'Afternoon', 'Evening', 'Night']`.
    - `Category_Vector`: A vector representing the category of the flight. Example: `[0, 0, 0, 0, 0, 0]` where `['Military', 'Private', 'Commercial', 'Government', 'Other', 'Unknown']`.
    - `Summary_Vector`: A vector representing the cause of the crash. Example: `[0, 0, 0, 0, 0, 0, 0]` where `['Visibility Issues', 'Weather-Related', 'Mechanical Problems', 'Emergency Landing', 'Human Factors', 'Unknown Causes', 'First or Second War']`.
