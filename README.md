# US Accidents Analysis

This project conducts an exploratory data analysis on the US Accidents dataset from Kaggle. The dataset contains accident records in the US from February 2016 to March 2023.

## Data

The dataset is originally from the US Department of Transportation. It was compiled and uploaded to Kaggle.

The data dictionary provides details on each feature in the dataset. Key variables include:

- Location (city, county, state, latitude, longitude)
- Environment (weather, visibility, road conditions) 
- Time (timestamp, day of week, holiday)
- Accident severity and types
- Number of vehicles involved

The dataset can be found here: https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

## Methods

The analysis covers:

- Exploratory data analysis on the distributions of key variables
- Visualizations of major accident factors and trends over time/location
- Determining correlations between variables and accident severity
- Clustering analysis on the accident types

The project focuses on extracting insights from the data rather than developing a predictive model.

## Requirements

The project requires Python and common data analysis libraries like Pandas, Matplotlib, Seaborn, Folium and Scikit-Learn.

## Usage

The Jupyter Notebook `us_accidents_analysis.ipynb` contains the full analysis. To use:

1. Clone this repository
2. Download the dataset and add to the repository folder
3. Ensure the required libraries are installed
4. Run the notebook

## Key Findings

Some example insights from the analysis:

- Accident severity has increased over the 2016-2021 period
- The most dangerous weather conditions are heavy rain/storm and snow
- Interstate highways have more severe accidents than other road types
- SUVs and pickup trucks are involved in more severe accidents than other vehicle types

## References

The original dataset can be found here: https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

- Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. “A Countrywide Traffic Accident Dataset.”, 2019.

- Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. "Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights." In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019.

