# Comprehensive Cyber Security Attacks Analysis

This repository contains an in-depth analysis of a cyber security attacks dataset. The dataset has been refined to address all missing values, and the analysis includes comprehensive exploratory data analysis (EDA), correlation analysis, clustering, predictive modeling, anomaly detection, and advanced analysis techniques.

## Overview

The objective of this analysis is to gain insights into the nature and patterns of cyber security attacks. We explore the data to visualize distributions, trends, and correlations, and apply machine learning techniques to identify patterns, predict attack severity, and detect anomalies.

## Dataset Description

The dataset provides a realistic portrayal of cyber security attacks, including various details such as:
- Timestamp
- Source and Destination IP Addresses
- Source and Destination Ports
- Protocol
- Packet Length
- Packet Type
- Traffic Type
- Attack Type
- Severity Level
- Geographic Information (Country, Region, City, Latitude, Longitude)
- ISP and Organization Information
- Log Source, Browser, Device/OS
- Date and Time Components

The dataset is synthetic and has been meticulously crafted to be versatile for various analytical tasks.

The dataset can be found in **Kaggle**: [Cyber Security Attacks | Cleaned](https://www.kaggle.com/datasets/saadatkhalid/cyber-security-attacks-cleaned)

## Analysis Details

### Exploratory Data Analysis (EDA)
- Distribution of attack types
- Geographic distribution of attacks
- Trends over time (yearly, monthly, weekly)

### Correlation Analysis
- Computation and visualization of correlations between numerical features

### Clustering Analysis
- Application of PCA and K-Means clustering to identify patterns

### Predictive Modeling
- Building and evaluating a Random Forest model to classify the severity of attacks

### Anomaly Detection
- Implementing anomaly detection techniques using Isolation Forest

### Additional Analysis
- Time series decomposition to analyze attack trends
- Feature importance assessment using Random Forest
- PCA for dimensionality reduction
- Hyperparameter tuning with Grid Search for model optimization

## Setup Instructions

### Prerequisites

- Python 3.6 or higher
- Jupyter Notebook
- Required Python libraries (listed below)

### Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/debjit-mandal/cyber-security-analysis.git
    cd cyber-security-analysis
    ```

2. Install the required Python libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
    ```

### Usage

1. Open the Jupyter notebook:
    ```bash
    jupyter notebook cyber_security_analysis.ipynb
    ```

2. Run the cells in the notebook to execute the analysis. The notebook includes detailed comments and explanations for each step of the analysis.

## Summary and Conclusion

This comprehensive analysis provides valuable insights into the nature and patterns of cyber security attacks. The findings can aid in developing more effective prevention and mitigation strategies. The use of clustering, predictive modeling, and anomaly detection techniques demonstrates the potential of machine learning in enhancing cyber security defenses.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

This analysis was inspired by the need to understand and mitigate cyber security threats using advanced data analytics and machine learning techniques.

---

Feel free to contribute to this repository by submitting issues or pull requests. 
