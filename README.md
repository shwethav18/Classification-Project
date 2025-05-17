# Hierarchical Clustering of Swiss Provinces

Can Swiss provinces be grouped based on their socio-economic profiles, and what can these groupings tell us about regional development needs? This project applies hierarchical clustering to the Swiss dataset to uncover patterns in fertility, education, industrialization, and agriculture. The goal is to support regional policy-making through data-driven segmentation.

## Dataset

- **Source:** Swiss Dataset (built-in R dataset, commonly used for socio-economic clustering)
- **Observations:** 47 provinces
- **Variables:** Fertility, Agriculture, Examination, Education, Catholicism, Infant Mortality

## Objective

Cluster Swiss provinces into groups based on socio-economic indicators and analyze how these groupings can reveal regional disparities and development opportunities.

## Key Questions

- Which Swiss provinces exhibit high fertility and low education levels?
- Are there distinct socio-economic clusters based on industrialization and agriculture?
- How does socio-economic development vary across Swiss regions?

## Approach

1. **Exploratory Data Analysis**
   - Visualized distributions and variable relationships

2. **Preprocessing**
   - Standardized the data using Z-score normalization

3. **Clustering**
   - Applied hierarchical clustering with multiple linkage methods
   - Visualized dendrograms and compared tree structures
   - Chose optimal linkage based on interpretability and structure

4. **Interpretation**
   - Identified meaningful clusters and interpreted their socio-economic characteristics

## Transferable Skills Demonstrated

- Unsupervised machine learning (hierarchical clustering)
- Data preprocessing and normalization
- Linkage method comparison and evaluation
- Domain-relevant insight extraction
- Visual storytelling with dendrograms

## Future Improvements

- Add cluster validation metrics (e.g., Silhouette Score)
- Map clusters using geospatial visualization
- Extend to broader socio-economic datasets
- Perform longitudinal clustering if time-series data becomes available

## Tools Used

- R 
- Hierarchical clustering algorithms
- Dendrogram plotting functions
