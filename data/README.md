
# Data

## Dataset Source

The dataset used in this project is the NYC Yellow Taxi Trip Record Data
provided by the New York City Taxi and Limousine Commission (TLC).

The dataset consists of monthly trip-record files in Parquet format.

Source:

https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

## Data Used

The project uses NYC Yellow Taxi trip records covering the period
specified in the project analysis.

The raw data and processed datasets are not included in this GitHub
repository because of their large file size.

## Data Storage

The data used during development and analysis was stored in Google Drive
and accessed through Google Colab.

The notebooks contain the paths and loading instructions used to access
the data during the analysis.

## Data Processing

The data was processed using PySpark. The processing included:

- Standardising column names and data types
- Handling missing values
- Checking invalid values
- Removing or filtering inappropriate records
- Preparing the data for exploratory data analysis
