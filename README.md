# McDonald's Dataset Exploratory Data Analysis (EDA) with K-means Clustering
## Project Overview

This project aims to perform Exploratory Data Analysis (EDA) on the McDonald's dataset using the K-means clustering algorithm. The goal is to uncover insights and patterns within the data that can help understand customer preferences and behaviors.

## Dataset

The dataset contains various attributes related to customer perceptions and demographics regarding McDonald's. The attributes include:

- `yummy`, `convenient`, `spicy`, `fattening`, `greasy`, `fast`, `cheap`, `tasty`, `expensive`, `healthy`, `disgusting`: Customer perceptions about different aspects of McDonald's.
- `Like`: A numerical score representing how much a customer likes McDonald's.
- `Age`: Age of the customers.
- `VisitFrequency`: Frequency of customer visits.
- `Gender`: Gender of the customers.

## Steps Performed

1. **Data Loading and Preparation**:
   - Loaded the dataset into a pandas DataFrame.
   - Converted categorical data to numerical values using Label Encoding.

2. **Data Scaling**:
   - Scaled the data to normalize the feature values using StandardScaler.

3. **K-means Clustering**:
   - Applied the K-means algorithm to the scaled data to form clusters.
   - Chose 3 clusters (`n_clusters=3`) for this analysis.

4. **Cluster Analysis**:
   - Analyzed the clusters by computing the mean of each feature for each cluster.
   - Visualized the clusters using scatter plots to understand the distribution based on different features.

## Insights

- The clustering results helped in identifying distinct groups of customers based on their preferences and demographics.
- Visualizations provided a clear understanding of how different clusters are distributed in terms of `Age` and `Like` scores.

## Visualization

Included scatter plots to visualize the clusters formed by the K-means algorithm, which helps in understanding the distribution and characteristics of each cluster.

## Conclusion

This project demonstrates the application of K-means clustering for exploratory data analysis on the McDonald's dataset, providing valuable insights into customer preferences and behaviors.

## Requirements

- pandas
- scikit-learn
- matplotlib
- seaborn

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mcdonalds-eda-kmeans.git
   ```
2. Navigate to the project directory:
   ```bash
   cd mcdonalds-eda-kmeans
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebook or Python script to perform the analysis:
   ```bash
   jupyter notebook
   # or
   python analysis.py
   ```

## Repository Structure

- `data/`: Contains the dataset.
- `notebooks/`: Jupyter notebooks with the EDA and clustering analysis.
- `scripts/`: Python scripts for data processing and analysis.
- `README.md`: Project overview and instructions.

## Contact

For any questions or suggestions, feel free to open an issue or contact me anshmatto1234@gmail.com

