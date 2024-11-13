# Flight Data Analysis from Priceline

## Project Overview
This project involves exploratory data analysis (EDA) on flight data from the Priceline website, sourced from Kaggle. The aim is to understand trends, patterns, and general insights from the dataset, such as price distributions, common routes, and flight duration. The analysis is performed using **NumPy**, **scikit-learn**, and **matplotlib**.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Data Analysis and Methodology](#data-analysis-and-methodology)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset
The dataset used for this project is available on [Kaggle](https://www.kaggle.com/datasets/joyshil0599/comprehensive-flight-data-from-priceline), containing information about flights listed on Priceline. Key features include:
- **Airlines**: The carrier operating each flight.
- **Route**: The origin and destination of each flight.
- **Price**: The listed ticket price.
- **Flight Duration**: Time taken for each route.
- **Additional Fields**: Departure and arrival times, layovers, etc.


## Installation
To run this project locally:

1. **Clone the repository**:
   ```bash
   https://github.com/slytechiefrommagentashore/Flight-Data-Analysis-from-Priceline
   cd flight-data-analysis
## Data Analysis and Methodology
The analysis uses Python and includes the following libraries:

- **NumPy**: For numerical computations and data handling.
- **scikit-learn**: For preprocessing and data cleaning (no modeling was performed).
- **Matplotlib**: For visualizations, including graphs and plots to reveal data trends.

### Key Steps
#### Data Cleaning:
- Checked for missing values and handled them appropriately.
- Removed any obvious outliers to ensure a clean dataset for analysis.

#### Exploratory Data Analysis (EDA):
- Conducted descriptive statistical analysis to understand distributions in flight prices, durations, and airline frequencies.
- Created various graphs (within the Jupyter notebook) to visualize trends, such as:
  - **Price distribution** across different flights.
  - **Common routes** and their average prices.
  - **Airline comparisons** for average ticket prices.

## Results
Key insights from the analysis include:

- **Price Patterns**: Identification of high-cost and low-cost routes and the distribution of ticket prices.
- **Airline Insights**: Comparative analysis of different airlines based on their average prices.
- **Duration Trends**: Overview of how flight duration may influence ticket prices.

These findings can aid travelers in identifying cost-effective flights or provide insights for airline market analysis.

## Contributing
Contributions are welcome! If you’d like to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](https://creativecommons.org/publicdomain/zero/1.0/) file for more details.

### Dataset License
The dataset used in this project is made available under the **CC0: Public Domain** license. This means you are free to copy, modify, and distribute the data without any restrictions. For more information, please see the [Kaggle dataset page](https://www.kaggle.com/datasets/joyshil0599/comprehensive-flight-data-from-priceline).

