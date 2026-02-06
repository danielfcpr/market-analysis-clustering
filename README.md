# Market Analysis & Country Segmentation (Clustering Case Study)

This project is an end-to-end data analytics case study focused on identifying
high-potential export markets using demographic, economic, and food consumption data.

The final deliverables were a technical analysis report and a business presentation,
produced as part of an analytics project where insights and recommendations were
the primary objective.

## Objective
Identify and segment countries with high potential for poultry exports by combining:
- Consumption indicators
- Import / production dependency
- Economic and demographic variables

## Approach
The analysis followed a structured analytics workflow:
- Data ingestion and preprocessing (multiple public datasets)
- Feature engineering and data quality validation
- Exploratory data analysis and correlation analysis
- Outlier treatment and scaling (RobustScaler)
- Unsupervised learning (Hierarchical Clustering, K-Means)
- Dimensionality reduction (PCA) for interpretation
- Business-oriented interpretation of clusters

## Key Techniques
- Pandas, NumPy
- Exploratory Data Analysis (EDA)
- K-Means clustering & silhouette score
- Hierarchical clustering (dendrogram)
- Principal Component Analysis (PCA)
- Data visualization with Matplotlib & Seaborn

## Results
Three distinct country clusters were identified.
One cluster showed strong dependence on poultry imports, high purchasing power,
and economic stability, making it a strong candidate for export market targeting.

## Deliverables
- `analysis_report.pdf`: Full technical analysis and methodology
- `presentation.pdf`: Executive summary and business recommendations

> Note: The original notebook was produced in French.
> The PDF version are shared here to document the analytical reasoning
> and results.
