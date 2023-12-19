# Movie Recommender System Project

## Overview

This project aims to implement a movie recommender system using the K-Nearest Neighbors (KNN) machine learning model. The dataset for the recommender system is constructed by merging two .csv files through a join operation in an SQL database.

## Dataset Composition

The dataset is composed of two .csv files, which are merged using an SQL join operation. The resulting dataset is then extracted as a pandas dataframe for further processing.

## Data Processing

### Feature Selection

We filter the dataset based on relevant columns that are crucial for the movie recommender system's purpose.

### Data Cleaning

The dataset undergoes a cleaning process to handle missing values and ensure data integrity.

## Vectorization

Once the desired features are selected and the dataset is cleaned, we proceed to vectorize the data. Vectorization is essential for training the machine learning model, involving the transformation of textual or categorical data into a numerical format suitable for algorithms like KNN.

## Training the Model

The vectorized dataset is used to train the KNN model, enabling it to learn patterns and relationships within the data.

## Project Structure

- **data/:** Contains the dataset files.
- **src/:** Contains the Jupyter Notebook script and source code files for data processing, model training, and implementation of the movie recommender system.
- **README.md:** Project documentation providing an overview and details about the project.



Feel free to contribute, report issues, or provide feedback!

