## Customer Segmentation using Hierarchical Clustering

This project explores customer segmentation using Agglomerative Hierarchical Clustering combined with PCA visualization and Silhouette analysis to evaluate clustering performance.

The objective was to identify meaningful customer groups and compare different linkage methods to determine the most appropriate clustering structure.


## Project Overview

Clustering is an unsupervised learning technique used to group similar observations. In this project, I:

- Standardized the dataset

- Applied Agglomerative Clustering

- Compared multiple linkage methods: Ward, Complete, Average, Single

- Evaluated performance using Silhouette Score

- Visualized clusters using Principal Component Analysis (PCA)


## Technologies Used

- Python

- Pandas

- NumPy

- Scikit-learn

- Matplotlib

- Seaborn

## Methodology
1. Data Preprocessing

- Feature scaling using standardization

- Preparation of matrix X = data_standardized

2. Clustering

For each:

- Number of clusters: 2 → 10

- Linkage methods: Ward, Complete, Average, Single

I:

- Fit AgglomerativeClustering

- Computed silhouette score

- Stored results including cluster labels

results.append({
    "num_of_clusters": n_clusters,
    "linkage": linkage,
    "silhouette_score": score,
    "labels": labels
})

3. Model Evaluation

Clustering performance was compared using:

- Silhouette Score

- Visual inspection in PCA space

The four best Ward-linkage models were selected and visualized for comparison.


## Key Findings

- Ward linkage produced the most stable and interpretable clusters.

- Silhouette score helped identify optimal cluster numbers.

- Visual inspection in PCA space confirmed separation quality.

- Storing cluster labels ensured accurate visualization across models.

This project highlights the importance of:

- Combining quantitative metrics with visual validation

- Careful result tracking when comparing multiple models

- Debugging clustering pipelines through visual consistency checks


## Example Output

The project includes:

- Silhouette score comparison table

- PCA cluster visualizations

- Best-performing clustering configurations

## How to Run

Clone the repository

Install dependencies: 
       -pip install pandas numpy scikit-learn matplotlib seaborn

Open the jupyter notebook:
jupyter notebook ThuVu_DAKD_2025_exercise_1.ipynb

## Project Structure
- ThuVu_DAKD_2025_exercise_1.ipynb
- README.md
- shopping_centre.csv

## Skills Demonstrated

Unsupervised Machine Learning

Hierarchical Clustering

Model Evaluation (Silhouette Score)

PCA for dimensionality reduction

Analytical debugging

Experimental result tracking

Data visualization


