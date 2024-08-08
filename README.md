# US Housing Data Analysis

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Project Structure](#project-structure)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Analysis](#analysis)
7. [Conclusion](#conclusion)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction
Welcome to the US Housing Data Analysis project! This project aims to analyze housing data from various metropolitan regions in the United States. Our goal is to uncover trends, patterns, and insights about the housing market, including price variations, inventory levels, and more.

## Dataset
The dataset used in this project contains information on the median listing price of single-family homes and condos across different metropolitan areas in the US. Key columns include:
- **RegionName**: Name of the metropolitan region
- **Date**: Date of the data record
- **MedianListingPrice**: Median listing price for homes in that region

The data spans from March 2018 to April 2024.

## Project Structure
The project is organized as follows:


## Installation
To get started with this project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/us-housing-data-analysis.git
    cd us-housing-data-analysis
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python3 -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install the dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To run the analysis, you can use the Jupyter notebooks provided in the `notebooks` directory. Here is a brief overview:

1. **Data Exploration**:
    Open and run the `01_data_exploration.ipynb` notebook to get an initial understanding of the dataset.

2. **Data Cleaning**:
    Use the `02_data_cleaning.ipynb` notebook to clean and preprocess the data.

3. **Data Analysis**:
    The `03_data_analysis.ipynb` notebook contains detailed analyses, including visualizations and insights.

## Analysis
### Example Questions Answered
1. **What is the trend in median listing prices over time?**
2. **Which regions have the highest and lowest median listing prices?**
3. **How does the inventory of homes for sale change over time in different regions?**

### Key Insights
- **Trend Analysis**: The median listing price shows a consistent upward trend in most metropolitan areas.
- **Regional Differences**: Some regions like New York, NY, and Los Angeles, CA have significantly higher median listing prices compared to others.
- **Inventory Levels**: Inventory levels fluctuate seasonally, with noticeable drops during certain months.

### Example Visualization
![Median Listing Price Trend](assets/median_listing_price_trend.png)

## Conclusion
This project provides a comprehensive analysis of the US housing market using the given dataset. The insights gained can help stakeholders make informed decisions regarding real estate investments, market analysis, and policy-making.

## Contributing
We welcome contributions from the community! If you have any suggestions, improvements, or new features, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Thank you for visiting my project! I hope you find the analysis insightful and useful.

