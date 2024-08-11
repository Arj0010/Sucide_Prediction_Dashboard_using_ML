# Sucide_Prediction_Dashboard_using_ML


This project analyzes and predicts suicides in India using a dataset from Kaggle. The analysis includes various visualizations and predictions using a Random Forest Regressor model.

## Index

1. [Dataset](#dataset)
2. [Key Steps](#key-steps)
   - [Data Exploration](#data-exploration)
   - [Data Visualization](#data-visualization)
   - [Prediction Model](#prediction-model)
   - [Interactive Dashboard](#interactive-dashboard)
3. [Usage](#usage)
4. [Results](#results)
5. [Conclusion](#conclusion)
6. [License](#license)

## Dataset

- **Source:** [Kaggle](https://www.kaggle.com/datasets/rajanand/suicides-in-india)
- **Content:** The dataset contains suicide data in India from 2001 to 2012, with 237,519 rows and 7 columns.

## Key Steps

### Data Exploration
   - Loaded the dataset and inspected basic information such as shape, summary statistics, and missing values.
   - Filtered out unnecessary data (e.g., rows where total suicides are zero).

### Data Visualization
   - **Type-wise Analysis:** Pie chart of suicide types.
   - **State-wise Analysis:** Bar chart of suicides by state.
   - **Gender-wise Analysis:** Pie chart of suicides by gender.
   - **Age-wise Analysis:** Histogram of suicides by age group.
   - **Year-wise Trend:** Line plot of suicides over the years.

### Prediction Model
   - Trained a Random Forest Regressor to predict suicides based on state, type, gender, and age group.
   - Evaluated the model using Mean Absolute Error (MAE).

### Interactive Dashboard
   - Created an interactive widget-based dashboard to explore suicides by state.

## Usage

- **Dependencies:** 
  - `numpy`, `pandas`, `matplotlib`, `ipywidgets`, `sklearn`
- **Execution:** 
  - Run the script in a Jupyter Notebook or Python environment to visualize and predict suicide trends.

## Results

- The analysis reveals that the age group 15-29 has the highest suicide rates, often influenced by educational and social factors.
- The model provides a predictive framework for understanding future suicide trends based on historical data.

## Conclusion

This project offers insights into the suicide trends in India and presents a predictive model to anticipate future occurrences, aiding in targeted interventions.

## License

This project is licensed under the MIT License.
