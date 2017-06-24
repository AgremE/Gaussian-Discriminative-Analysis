# Gaussian-Discriminative-Analysis

## Project Description

In the program, I design Gaussian Discriminant Analysis classifier on two image data sets, hand-writting image and face image dataset

## How to Run the Code
To try out the classification pipeline, run dataClassifier.py from the command line. This will classify the
digit data using the default classifier (mostFrequent) which blindly classify every example with the most
frequent label.

python dataClassifier.py

To activate the Gaussian Discriminant Analysis classifier, use -c GDA:

python dataClassifier.py -c GDA

To run on the face recognition dataset with different training data size, use -d faces and -t numTraining

python dataClassifier.py -c GDA -d faces -t 300

