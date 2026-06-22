# Netflix Movies and TV Shows Clustering

## Project Overview
This project applies unsupervised machine learning to analyze and cluster Netflix movies and TV shows based on their content-related features. The goal is to identify similar groups of titles and understand patterns in the Netflix catalogue.

## Objective
- Explore the Netflix dataset
- Clean and preprocess the data
- Perform Exploratory Data Analysis
- Apply clustering techniques
- Find the optimal number of clusters
- Interpret the final clusters
- Export the trained clustering model

## Dataset
The dataset contains information about Netflix titles such as:

- Title
- Type
- Director
- Cast
- Country
- Date added
- Release year
- Rating
- Duration
- Listed genres
- Description

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- K-Means Clustering
- Jupyter Notebook
- Joblib

## Project Workflow

### 1. Data Collection
The Netflix dataset was loaded into a Jupyter Notebook for analysis.

### 2. Data Cleaning
Missing values were handled, unnecessary columns were removed, and text/category features were prepared for analysis.

### 3. Exploratory Data Analysis
EDA was performed to understand:
- Movies vs TV Shows count
- Content released by year
- Top countries producing Netflix content
- Popular ratings
- Common genres/categories

### 4. Feature Engineering
Important features were selected and converted into a machine-learning-ready format using preprocessing techniques such as encoding and scaling.

### 5. Clustering
K-Means Clustering was applied to group similar Netflix titles.

### 6. Cluster Evaluation
The optimal number of clusters was selected using methods such as:
- Elbow Method
- Silhouette Score

### 7. Model Export
The final clustering model was saved using Joblib for future use.

## Model Files
The project exports the following files:
How to Run
Clone or download this project.
Install the required libraries:
pip install pandas numpy matplotlib seaborn scikit-learn joblib
Open the notebook:
jupyter notebook Netflix.ipynb
Run all cells from top to bottom.
Output

The final output of this project is a clustering model that can group Netflix titles into meaningful content segments based on similarity.

## Conclusion

This project helps understand hidden patterns in Netflix content using unsupervised machine learning. The clustering results can be useful for content recommendation, catalogue analysis, and entertainment data insights.
```python
netflix_clustering_pipeline.pkl
netflix_cluster_names.pkl
