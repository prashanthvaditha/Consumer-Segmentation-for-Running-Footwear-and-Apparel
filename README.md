Here’s a draft README file for your project:

---

# Consumer Segmentation for Running Footwear and Apparel

## Project Overview

This project aims to identify distinct consumer segments for a running footwear and apparel company using clustering analysis on survey data. The segmentation helps to uncover actionable insights for tailored product offerings and targeted marketing strategies.

The analysis employs **hierarchical clustering** and **K-means clustering**, and includes the following steps:
1. **Data Exploration and Preparation**: Cleaning and transforming the dataset for clustering.
2. **Similarity Metrics Calculation**: Calculating relevant distance measures.
3. **Cluster Determination**: Using the Elbow method to identify the optimal number of clusters.
4. **Clustering Implementation**: Conducting hierarchical and K-means clustering.
5. **Cluster Profiling**: Analyzing cluster characteristics to derive actionable insights.

---

## File Descriptions

### 1. Notebook File: `Consumer Segmentation for Running Footwear and Apparel Notebook.ipynb`
This Jupyter Notebook contains the full analysis pipeline:
- Data exploration, cleaning, and preparation.
- Implementation of hierarchical and K-means clustering algorithms.
- Determination of the optimal number of clusters using the Elbow method.
- Profiling and interpretation of the identified consumer segments.

### 2. Dataset: `survey_data.xlsx`
This Excel file includes the raw survey data used for clustering analysis. It contains consumer responses related to preferences, demographics, and purchasing behaviors relevant to running footwear and apparel.

---

## Key Insights
The project segments consumers into distinct clusters based on behavioral and demographic data:
1. Each cluster represents a unique consumer profile, enabling precise targeting.
2. Insights derived from cluster profiling support:
   - Development of tailored product lines.
   - Customization of marketing strategies for each consumer segment.

---

## Requirements

### Software and Libraries
- Python 3.8+
- Jupyter Notebook
- Required Python Libraries:
  - `pandas`
  - `numpy`
  - `scipy`
  - `matplotlib`
  - `seaborn`
  - `sklearn`

### Installation
Install the required libraries using:
```bash
pip install pandas numpy scipy matplotlib seaborn scikit-learn
```

---

## Usage

1. Open the Jupyter Notebook `Consumer Segmentation for Running Footwear and Apparel Notebook.ipynb`.
2. Ensure the dataset `survey_data.xlsx` is in the same directory as the notebook.
3. Run the notebook cells step-by-step to reproduce the analysis.

---

## Results and Deliverables

- **Cluster Profiles**: Detailed characteristics and preferences of each consumer segment.
- **Actionable Recommendations**: Suggestions for product differentiation and targeted marketing strategies based on the cluster profiles.

---

## Authors

This analysis was conducted as part of a data-driven marketing strategy for a running footwear and apparel company. For questions or collaborations, please contact vaditha.s@northeastern.edu


---
