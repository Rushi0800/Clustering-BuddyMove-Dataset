# Clustering-BuddyMove-Dataset
This project applies K-means and DBSCAN clustering techniques to the BuddyMove dataset, analyzing user review behavior across different categories such as sports, nature, theatre, and more. 


Dataset Name**: BuddyMove  
Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/476/buddymove+data+set)  
Number of Objects: 249  
Attributes: 7  
  - 'Userid' (Categorical)
  - 'Sports', 'Religious', 'Nature', 'Theatre', 'Shopping', 'Picnic' (Continuous)

    
Prerequisites
- Python 3.10
- Libraries: pandas, numpy, matplotlib, seaborn, sklearn


Install required libraries:
pip install pandas numpy matplotlib seaborn scikit-learn


Running the Code
Clone the repository:
git clone https://github.com/yourusername/Clustering-BuddyMove-Dataset.git
cd Clustering-BuddyMove-Dataset/code


Run the script:
python clustering_analysis.py


View the results in the results/ folder.
Result
K-means Clustering
Number of Clusters: X
Cluster Sizes: [size1, size2, ...]
DBSCAN Clustering
Number of Clusters: Y (including noise)
Noise Points: Z

clustering output: https://raw.githubusercontent.com/Rushi0800/Clustering-BuddyMove-Dataset/refs/heads/main/results/clustering_output.txt


Visualizations:
K-means: https://raw.githubusercontent.com/Rushi0800/Clustering-BuddyMove-Dataset/refs/heads/main/results/visualizations/kmeans_k2.png
DB-Scan: https://raw.githubusercontent.com/Rushi0800/Clustering-BuddyMove-Dataset/refs/heads/main/results/visualizations/dbscan_eps0.3_min10.png


