# Expression-Recognisition
This project involves analyzing 3D facial landmarks using three classic machine learning classifiers: Random Forest (RF), Support Vector Machine (SVM), and Decision Tree (TREE). The aim is to experiment with subject-independent 10-fold cross-validation to classify facial expressions based on 3D coordinates.

Key Features
Language: Python
Algorithms:
Random Forest (RF)
Support Vector Machine (SVM)
Decision Tree (TREE)
Data: 3D facial landmarks from the BU4DFE_BND dataset
83 facial landmarks with x, y, z coordinates
Cross-Validation: Implemented subject-independent 10-fold cross-validation for robust evaluation
Experiments
Three sets of experiments were conducted for each classifier using:

Raw 3D Landmarks: Feature vectors composed of 249 data points (x, y, z coordinates).
Translated 3D Landmarks: Translated facial landmarks to center the face at the origin before classification.
Dataset Structure
The dataset is organized in subject directories with .bnd files, containing the facial landmark coordinates for various expressions.

How to Run
Run Project1.py to execute the classification process.
The code includes built-in cross-validation logic, so ensure the dataset is properly structured as per the original zip file.
