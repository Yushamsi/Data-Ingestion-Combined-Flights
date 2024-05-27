# Data Ingestion and Efficiency Analysis for Flight Data

## Project Overview
This project explores efficient data ingestion methods for large datasets (2+ GB) using various libraries like Dask, Modin, Ray, and pandas. The focus is on reading and processing a large flight dataset from 2018 to 2022 to identify the most computationally efficient approach.

## Data Used (Extracted from Kaggle: https://www.kaggle.com/datasets/robikscube/flight-delay-dataset-20182022)
- **flight-delay-dataset-20182022.zip**
- **Cleaned_Combined_Flights_2021.csv.gz**

## Key Processes
- **Data Reading:** Experiment with different data reading libraries (Dask, Modin, Ray, Pandas) to benchmark performance.
- **Data Validation:** Perform basic validations such as cleaning column names of special characters and whitespace.
- **Configuration Management:** Use a YAML file to manage data schemas, including column names and file separators.
- **Data Writing:** Output the cleaned data into a pipe-separated text file in gzipped format.

## Results
- Summary metrics such as total rows, total columns, and file size are computed and reported.

## Getting Started
Clone this repository and follow the notebooks to see the detailed steps and benchmarks for each data reading method tested.

## Contributing
Contributions to improve efficiency or extend the benchmarks are welcome. Please fork the repository and submit a pull request with your updates.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
