

# Clustering Analysis Application

<a href="https://streamlit.io" target="_blank" rel="noreferrer"> 
  <img src="https://streamlit.io/images/brand/streamlit-mark-color.svg" alt="streamlit" width="40" height="40"/> 
</a>
<a href="https://opencv.org" target="_blank" rel="noreferrer"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/opencv/opencv-original.svg" alt="opencv" width="40" height="40"/> 
</a>
<a href="https://www.mongodb.com" target="_blank" rel="noreferrer"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="mongodb" width="40" height="40"/> 
</a>

A comprehensive Streamlit application for data exploration, preprocessing, and clustering analysis with multiple algorithms.

## Features

### 1. Data Loading & Exploration
- Upload CSV files or use built-in sample datasets (Blobs, Moons, Circles)
- Basic dataset information and statistics
- Column-wise analysis of unique values and distributions

### 2. Data Preprocessing
- Interactive handling of non-numeric columns (keep, delete, or encode)
- Missing value identification and treatment:
  - Removal
  - Replacement (mean, median, mode)
- Invalid value detection and handling
- Data normalization:
  - Min-Max scaling
  - Z-score standardization

### 3. Visualization Tools
- Box plots for numerical feature distributions
- Scatter plots and pair plots for feature relationships
- Interactive controls for plot customization

### 4. Clustering Analysis
- Multiple clustering algorithms:
  - **K-Means**: Partition-based clustering
  - **K-Medoids**: Robust version of K-Means
  - **AGNES**: Agglomerative hierarchical clustering
  - **DIANA**: Divisive hierarchical clustering
  - **DBSCAN**: Density-based clustering
- Elbow method for optimal K selection
- Cluster visualization in 2D and 3D (PCA-reduced space)
- Performance metrics:
  - Silhouette score
  - Intra-cluster distance
  - Inter-cluster distance
  - Computation time

### 5. Results Comparison
- Side-by-side comparison of different algorithm runs
- Metrics visualization for performance evaluation
- Results history with option to remove specific runs

## Technologies

- **Python 3.7+**
- **Streamlit** - Web application framework
- **Scikit-learn** - Machine learning algorithms
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **SciPy** - Scientific computing

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/clustering-app.git
cd clustering-app
