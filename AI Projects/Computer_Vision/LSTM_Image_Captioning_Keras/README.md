# LSTM Image Captioning Using Keras
## Abstract
This notebook was a 'fill in the blank' homework for CSE 5368 Neural Networks. Its aim is to combine a computer vision model with an NLP model to generate image captions.  
The notebook uses InceptionV3 as the object detection model, and a bidirectional embedding layer (LSTM) for the text generation.
## Data
The dataset used in this notebook was [FLICKR8K](https://github.com/jbrownlee/Datasets/releases).
## Other Tasks In This Notebook
This notebook also covers the preparation of the text (caption) data as well as creating generators in python.
## Conclusions Reached
This combination model was able to reach an accuracy of about 51.79%. Had I trained for more than 20 epochs, I would have gained more accuracy.
```
Citations:  
Rethinking the Inception Architecture for Computer Vision (CVPR 2016).
```