# Handwriting Recognition Using KNN On USPS Data
## Abstract
This short notebook aims to create a handwriting recognition model (based on KNN) to classify images containing numbers.
## Data
The data is provided with the notebook [here](https://github.com/hannankhan888/AI-ML-Projects/blob/main/AI%20Projects/Computer_Vision/Handwriting_Recognition_Using_KNN_USPS_Data/usps.h5).  
Other sources of the same data can also be found online.
## Other Tasks In This Notebook
This notebook also covers using grid search to find the best parameters for the KNN model.
## Conclusions
The KNN model has reached an accuracy of 94.37% using the parameters below.  
```
{'leaf_size': 20,
 'metric': 'minkowski',
 'n_neighbors': 1,
 'p': 2,
 'weights': 'uniform'}
```