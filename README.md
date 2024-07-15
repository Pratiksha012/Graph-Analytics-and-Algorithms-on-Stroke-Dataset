# Graph Analytics and Algorithms on Healthcare Stroke Dataset

## Introduction
This project explores the application of graph analytics and algorithms on a healthcare stroke dataset. We conduct a comprehensive case study involving data preprocessing, exploratory data analysis (EDA), graph centrality measures, and various machine learning models. The primary aim is to gain insights from the dataset and improve predictive modeling using graph-based approaches.

## Dataset
The dataset used in this study is focused on healthcare data related to strokes. It contains the following columns:

- **id**: Unique identifier for each patient.
- **gender**: Gender of the patient.
- **age**: Age of the patient.
- **hypertension**: Whether the patient has hypertension (1) or not (0).
- **heart_disease**: Whether the patient has heart disease (1) or not (0).
- **ever_married**: Marital status of the patient.
- **work_type**: Type of work the patient is involved in.
- **Residence_type**: Type of residence (Urban/Rural).
- **avg_glucose_level**: Average glucose level in the blood.
- **bmi**: Body Mass Index of the patient.
- **smoking_status**: Smoking status of the patient.
- **stroke**: Whether the patient has experienced a stroke (1) or not (0).

## Project Structure

### 1. Data Preprocessing and Cleaning
- **Data Cleaning**: Handled missing values, outliers, and irrelevant data to ensure the dataset is suitable for analysis.
- **Label Encoding**: Converted categorical data into numerical labels for analysis, making it easier to apply machine learning algorithms.
- **Exploratory Data Analysis (EDA)**: Conducted EDA to understand the distribution of various features, identify patterns, and gain initial insights into the data. This included visualizations and statistical analysis.

### 2. Graph Centrality Analysis
- **Graph Construction**: Created graphs representing relationships within the data. Each node represents a patient, and edges represent relationships based on various features.
- **Centrality Measures**:
  - **Degree Centrality**: Identified nodes (patients) with the highest number of connections, indicating potential key influencers.
  - **Closeness Centrality**: Measured the average shortest path from a node to all other nodes, indicating the speed of information spread within the network.
  - **Betweenness Centrality**: Determined nodes that act as bridges between other nodes, highlighting important connectors within the network.
- **Graph Visualization**: Visualized the graphs to interpret centrality measures and understand the network structure better.

### 3. Machine Learning Models
- **Naive Bayes**:
  - Implemented a Naive Bayes classifier to predict the likelihood of a stroke based on the features.
  - Evaluated the model using a confusion matrix and performance scores such as accuracy, precision, recall, and F1 score.
- **Support Vector Machine (SVM)**:
  - Implemented an SVM classifier to enhance predictive accuracy.
  - Assessed the model with a confusion matrix and performance metrics to compare with the Naive Bayes model.

### 4. Graph Convolutional Network (GCN)
- **Model Implementation**:
  - Implemented a Graph Convolutional Network to leverage graph structures for improved predictions.
  - Trained the GCN model to refine the predictive capabilities by learning from the graph's structural information.

## Conclusion
This project demonstrates the potential of combining graph analytics with traditional machine learning approaches to gain deeper insights and improve predictive performance on healthcare datasets. The use of centrality measures and graph convolutional networks provides a robust framework for analyzing complex relationships within the data.
