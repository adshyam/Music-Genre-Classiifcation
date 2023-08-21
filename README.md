# Music Genre Classiifcation

Overview
This project aims to classify music genres based on extracted features from 3-second audio clips. The Jupyter notebook "Music Genre Composition.ipynb" provides a step-by-step process, starting from data loading to exploratory data analysis, preprocessing, and model building.

Steps Covered in the Notebook
Importing Libraries: The notebook begins by importing necessary libraries such as pandas, numpy, matplotlib, seaborn, keras, and scikit-learn.
Loading the Dataset: The dataset, named features_3_sec.csv, is loaded from Google Drive. This dataset presumably contains various features extracted from 3-second audio clips. 
dataset link : https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification

Data Preprocessing: The notebook processes the data, ensuring it's suitable for analysis and model training.
Exploratory Data Analysis (EDA): The notebook performs an exploratory data analysis to gain insights into the dataset's structure and distribution.
Model Building and Evaluation: Using Keras, a neural network model is built, trained, and evaluated on the dataset.

Requirements
To run the notebook, ensure you have the following libraries installed:

pandas
numpy
matplotlib
seaborn
os
keras
scikit-learn

If you're running the notebook in a local environment, make sure you have the dataset features_3_sec.csv available in your directory or adjust the path accordingly.

Load the Jupyter notebook.
Execute the cells in sequence. If you're not using Google Drive, adjust the data loading step to point to the correct location of the dataset on your machine.

Notes
The dataset features_3_sec.csv contains various music-related features from 3-second audio clips.
The notebook was initially set up to load data from Google Drive. Adjust the data loading cell if you're using a different source.

Conclusion
The "Music Genre Composition" project provides a comprehensive approach to understanding and classifying music genres based on audio features. By following the steps in the notebook, one can build, train, and evaluate a neural network model for music genre classification.




