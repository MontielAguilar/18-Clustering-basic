# K-Means Clustering README

## Overview

This repository contains a Python script for performing k-means clustering on a housing dataset. The script utilizes the `pandas` library for data manipulation, `scikit-learn` for k-means clustering, and various visualization tools for result analysis.

## . Explore the Results

After running the script, you will find the following changes made to the dataset:

- Columns 'HouseAge', 'AveRooms', 'AveBedrms', 'Population', 'AveOccup', 'MedHouseVal' have been removed.
- The dataset has been split into training and testing sets.
- K-means clustering has been performed on the training set, and a cluster label has been assigned to each data point.
- Cluster labels have been added to both the training and testing sets.
## . Visualize the Clusters

A pair plot has been generated using `seaborn` to visualize the clusters in the training set. To view the plot, run the script and look for the generated plot.

## . Evaluate Clustering Metrics

Clustering metrics such as silhouette score, Calinski-Harabasz index, and Davies-Bouldin index have been calculated on the testing set. The results will be displayed in the console.

## . Save the Model

The trained k-means clustering model has been saved to a file named `modelo_clustering.joblib` using the `joblib` library.

## . Additional Resources

Check out the following resources for further information:

- [Clustering Validation PDF](https://disi.unal.edu.co/~eleonguz/cursos/mda/presentaciones/validacion_Clustering.pdf)
- [Persistencia de Modelos en Python](http://exponentis.es/persistencia-de-modelos-en-python-como-guardar-tu-modelo-entrenado-de-machine-learning)

Feel free to explore and modify the script based on your requirements. Happy clustering!
