# Bipolar Disorder Statistical Analysis

## Overview

The **Bipolar Disorder Statistical Analysis** project aims to analyze data related to bipolar disorder by leveraging various statistical techniques and machine learning algorithms. Using **K-Means clustering**, the project groups participants based on ordinal responses to identify distinct participant clusters. The project also includes a variety of **visualizations** like heatmaps, histograms, and PCA plots to uncover key patterns and trends. Additionally, statistical tests like **correlation analysis**, **chi-square tests**, and **Z-tests** are used to examine relationships between demographics and responses, providing valuable insights into mental health trends.

## Features
- **K-Means Clustering**: Applies K-Means clustering to segment participants into groups based on their ordinal responses.
- **Visualization Tools**: Generates heatmaps, histograms, and PCA plots to explore data and highlight significant trends visually.
- **Statistical Analysis**: Performs correlation, chi-square, and Z-tests to uncover relationships between demographics and responses.
- **Data Insights**: Provides insights into mental health trends and patterns, aiding in the understanding of bipolar disorder.

## How it Works
1. **Data Preprocessing**: The dataset is cleaned and preprocessed, handling missing values and encoding ordinal responses.
2. **Clustering**: K-Means clustering is applied to the ordinal response data to identify distinct participant groups.
3. **Visualization**: Various visualizations such as heatmaps, histograms, and PCA plots are generated to explore the relationships in the data.
4. **Statistical Testing**: Correlation, chi-square, and Z-tests are used to examine the relationships between demographic data and responses.

## Requirements

- Python 3.x
- `pandas` (for data manipulation)
- `numpy` (for numerical computations)
- `matplotlib` (for visualizations)
- `seaborn` (for advanced plotting)
- `scikit-learn` (for K-Means clustering and PCA)
- `scipy` (for statistical tests)
- `statsmodels` (optional, for additional statistical methods)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Bipolar_Disorder-Statistical-Analysis.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Load and Preprocess Data**: Preprocess your dataset by loading it and handling missing values:
    ```python
    python preprocess_data.py --data_path <path_to_data>
    ```
2. **Run Clustering**: Apply K-Means clustering to identify participant groups:
    ```python
    python kmeans_clustering.py --data_path <path_to_processed_data>
    ```
3. **Generate Visualizations**: Create heatmaps, histograms, and PCA plots:
    ```python
    python visualize.py --data_path <path_to_processed_data>
    ```
4. **Run Statistical Tests**: Conduct correlation, chi-square, and Z-tests:
    ```python
    python statistical_tests.py --data_path <path_to_data>
    ```

## Example

```bash
python kmeans_clustering.py --data_path /path/to/processed_data.csv
```

This will apply K-Means clustering to the data and save the results to a file. You can also visualize the results and perform statistical tests with the provided scripts.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
