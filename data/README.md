# Data

## Dataset Source

The dataset used in this project is the NYC Yellow Taxi Trip Record Data
provided by the New York City Taxi and Limousine Commission (TLC).

The dataset is available from:

https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

The data is provided as monthly Parquet files containing NYC Yellow Taxi
trip records.

## Data Used in the Project

The project uses NYC Yellow Taxi trip records for the period covered by
the selected project dataset.

The raw data was downloaded from the NYC Taxi and Limousine Commission
(TLC) website and processed using PySpark.

## Data Storage

Due to the large size of the dataset, the raw and processed data files
are not included in this GitHub repository.

During development, the data was stored in Google Drive and accessed
through Google Colab.

The notebooks in the `notebooks/` directory contain the code used to
load and process the data.

## Data Processing

The data preparation process included:

- Combining the required monthly Parquet files
- Standardising column names and data types
- Handling missing values
- Checking for invalid values
- Checking trip dates and trip-related variables
- Checking passenger counts
- Checking trip distances
- Checking payment and rate code values
- Preparing the cleaned dataset for exploratory data analysis

The processed data was saved separately from the GitHub repository
because of its large file size.
