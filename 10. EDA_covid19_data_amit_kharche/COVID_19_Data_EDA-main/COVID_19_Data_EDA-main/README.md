# COVID-19 Data EDA

## Overview
This project involves performing an Exploratory Data Analysis (EDA) on a COVID-19 dataset to understand the spread, impact, and trends of the COVID-19 pandemic. The dataset used for this analysis includes information on confirmed cases, deaths, and recoveries across different countries over time.

## Dataset
The dataset used in this project is the COVID-19 dataset from Johns Hopkins University, which can be downloaded from [Kaggle](https://www.kaggle.com/datasets/imdevskp/corona-virus-report).

### Features
- **SNo**: Serial number
- **ObservationDate**: Date of observation
- **ProvinceState**: Province or state
- **CountryRegion**: Country or region
- **LastUpdate**: Last update timestamp
- **Confirmed**: Number of confirmed cases
- **Deaths**: Number of deaths
- **Recovered**: Number of recoveries

## Project Structure
The repository contains the following files and directories:
- `data/`: Directory containing the dataset
  - `covid_19_data.csv`: The dataset file
- `COVID_19_Data_EDA.ipynb`: Jupyter Notebook with the complete EDA process
- `README.md`: This file

## Steps and Analysis

### 1. Data Loading and Exploration
- Load the dataset and display the first few rows
- Summarize the dataset to understand the basic statistics
- Check for missing values in the dataset

### 2. Data Cleaning
- Rename columns for easier access
- Convert date columns to datetime format
- Fill missing values in `ProvinceState` with 'Unknown'

### 3. Data Visualization
- Plot the distribution of confirmed cases, deaths, and recoveries
- Visualize trends over time for confirmed cases, deaths, and recoveries
- Perform a country-wise analysis to identify the top 10 countries with the highest confirmed cases

## Visualizations
The project includes several visualizations to aid in the understanding of the data:
- **Histograms**: To visualize the distribution of confirmed cases, deaths, and recoveries
- **Trend Plot**: To visualize the trends of confirmed cases, deaths, and recoveries over time
- **Bar Plot**: To visualize the top 10 countries with the highest confirmed cases

## How to Run the Notebook
1. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/COVID_19_Data_EDA.git
    cd COVID_19_Data_EDA
    ```

2. **Install Required Libraries**:
    Ensure you have the required Python libraries installed. You can install them using pip:
    ```sh
    pip install pandas numpy matplotlib seaborn
    ```

3. **Open the Jupyter Notebook**:
    Start Jupyter Notebook and open `COVID_19_Data_EDA.ipynb` to run the analysis step-by-step.

## Contributing
Contributions are welcome! If you have any improvements or suggestions, please create a pull request or open an issue to discuss.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements
- The dataset used in this project is available on [Kaggle](https://www.kaggle.com/datasets/imdevskp/corona-virus-report).

## Author
- Ivy Qwinn
