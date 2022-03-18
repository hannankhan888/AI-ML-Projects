# XRay Pointcloud Registration & Classification
## Abstract
This notebook aims to create a model for registering chest pointclouds (using PointNetLK), and then classifying them into their atrial fibrillation types using support vector machining. This notebook also covers the features importances in this classification.  
## Data
Some features of the dataset:

* Data is anonymized.
* Each patients pointcloud is classified based on atrial fibrillation.
* Each observation contains data about the patients unipolar and bipolar values.

## Other Tasks In This Notebook
This notebook also covers the feature importances of each feature.
## Conclusions Reached
The XYZ coordinates of each patients' pointcloud contribute most to the classification of chest pointclouds into atrial fibrillation types. The unipolar values contribute slightly more than the bipolar values.

