# COVID-19 Data Analysis Script

## Overview
This script fetches COVID-19 data from a RapidAPI endpoint, converts it into a Pandas DataFrame, and then saves it as a CSV file. The data includes information about COVID-19 cases globally. 
This concludes the analysis for the senior design project our team displayed at UTA.

## Prerequisites
- Python 3
- Pandas library
- Requests library

## Setup
1. Install the required libraries using pip:
    ```
    pip install pandas requests
    ```

2. Obtain your RapidAPI key and replace `'YOUR_RAPIDAPI_KEY'` in the script with your actual key.

## Instructions
1. Run the script. Ensure not to run the API call too frequently to avoid null values in the dataset.
2. Check the status code printed to ensure the request was successful.
3. If successful, a CSV file named `covid_data_final.csv` will be created in the current directory.
4. The CSV file will be moved to the specified directory (`D:\FindMyCovidData\`) after creation.

## Important Note
- **Warning**: Do not run the API call too frequently as this may cause null values in the dataset for the USA row, rendering the analysis void.

## Author
[Your Name/Handle]

