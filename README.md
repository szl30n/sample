# Sample
This repository is meant to showcase my work using programing languages

# Projects
This [capstone project](/conference_poster/) for my Data Science intensive course involved engineering a machine learning pipeline to investigate the relationship between shell morphology and genetic population structure in invasive mollusks. The goal was to determine if unsupervised and supervised learning could use shell characteristics as a proxy for genetic variability.

Key Activities:
* Applied advanced unsupervised learning techniques including PCA and tg-SNE for dimensionality reduction, and K-Means clustering
* Processed and analyzed both quantitative and qualitative morphological measurements
* Engineered features from shell characteristic data for model input
* Conducted rigorous validation of clustering results against known genetic data

Outcomes & Insights:
The analysis revealed that shell morphology did not form distinct, genetically meaningful clusters, providing the following conclusion:
* Conchological features alone are not reliable predictors of genetic population structure in this species (at least for the markers cox1 and lsu-rrna)
* The sample used was not representative of the conchological variability
* The number of records analyzed was insufficient for the ML algorithms used

Technologies: Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
Methods: PCA, t-SNE, K-Means Clustering, Feature Engineering, Data Visualization
