# Terrano-E-Mart-Product-Categorization

Streamlit Video Demo
https://youtu.be/6DHQ24nZdRA

This project focuses on automating the product categorization process for an online electronics and furniture retailer, Terrano E-Mart. By utilizing K-Means clustering, this project aims to efficiently group similar products based on key features, improving operational efficiency and customer experience.
Project Objectives

    Automate product categorization: Implement an unsupervised machine learning model to automatically group similar products into clusters.
    Optimize product organization: Provide meaningful insights on product groups to enhance inventory management and customer recommendations.
    Improve operational efficiency: Reduce manual effort required for categorizing thousands of products and ensure consistency in categorization.

# Project Overview

In this project, we used K-Means clustering to segment products into distinct clusters based on their attributes. We performed the following steps:

    Data Preprocessing: Handled missing values, scaled the features, and prepared the data for modeling.
    Exploratory Data Analysis (EDA): Analyzed key features and visualized relationships between them to understand the product data.
    K-Means Clustering: Applied K-Means with 3 clusters to group similar products and evaluated the model’s performance.
    Cluster Visualization: Visualized the clusters for better interpretability and understanding of the product groups.
    Model Deployment: Deployed the clustering model using Streamlit, providing a user-friendly interface for interacting with the model and visualizing the clusters.

# Key Features

    Streamlit App: A fully functional app that allows users to upload product data, apply K-Means clustering, and visualize the results in real-time..
    Data Analysis & Visualizations: Comprehensive visualizations of clusters to provide insights into the categorization process.

# Technologies Used

    Python: The programming language used for data processing, modeling, and visualization.
    Streamlit: A lightweight framework used to deploy the app and create an interactive interface.
    Pandas & NumPy: For data preprocessing and manipulation.
    scikit-learn: For implementing the K-Means clustering algorithm.
    Matplotlib & Seaborn: For visualizing data and clusters.

# Installation & Usage

To run the project locally, follow these steps:

    Clone the repository:

    bash

git clone https://github.com/ighobaby/Terrano-E-Mart-Product-Categorization.git

Navigate to the project directory:

bash

cd Terrano-E-Mart-Product-Categorization

Install the required dependencies:

bash

pip install -r requirements.txt

Run the Streamlit app:

bash

    streamlit run app.py


# Results

    The K-Means model successfully categorized products into three distinct clusters, providing a clear separation based on key product features.
    Visualizations help stakeholders easily interpret the product groups and make informed decisions about inventory and recommendations.

# Future Enhancements

    Tune Clustering Algorithm: Experiment with different numbers of clusters and other clustering algorithms for better performance.
    Refine Feature Selection: Include more detailed product features to improve clustering accuracy.
    Expand Model Capabilities: Integrate additional machine learning models to enhance predictive power.

# Contributing

If you would like to contribute to this project, feel free to submit a pull request or open an issue with your suggestions.
