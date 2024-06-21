# **Task - 2 : Predicting the Optimum Number of Clusters using Unsupervised Machine Learning**

## **Overview**

This project aims to predict the optimum number of clusters for the Iris dataset using unsupervised machine learning techniques. By employing K-Means clustering, we identify the best clustering solution and visualize the results. 

## **Dataset**

The dataset used is the famous Iris dataset, which consists of 150 samples of iris flowers with four features:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

## **Project Steps**

### **1. Data Loading and Exploration**

- Load the Iris dataset.
- Display the first few rows to understand its structure.
- Check the shape of the dataset.
- Inspect dataset information to ensure there are no missing values.
- Remove any duplicate rows if present.
- View statistical properties of the dataset.

### **2. Data Visualization**

- Create box plots for each feature to observe their distribution.
- Generate a heatmap to understand the correlation between features.

### **3. Finding the Optimal Number of Clusters**

- Use the Elbow Method to determine the potential optimal number of clusters.
- Validate the choice using silhouette analysis.

### **4. Building the K-Means Model**

- Build and fit the K-Means model with the determined number of clusters.
- Visualize the clusters using 2D and 3D scatter plots.

## **Results**

The analysis suggests that clustering the Iris dataset into three clusters provides the best separation. The clusters are visualized along with their centroids.

## **Installation**

To run this project locally, you'll need Python and the following libraries:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install these dependencies using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## **Usage**

Clone the repository and navigate to the project directory:

```bash

```

## **Contributing**

Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.
