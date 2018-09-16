# Deep Learning Based Damage Detection on Post-Hurricane Satellite Imagery

This repo contains the materials presented in the paper "Deep Learning Based Damage Detection on Post-Hurricane Satellite Imagery" submitted to the INFORMS 2018 Best Student Paper Competition.

The repo contains the following items:

* Source python code for image classification
* Source python code for extract, filter, crop the bounding boxes from raw satellite imagery
* Source code to download raw satellite imagery from Digital Globe website
* Source code to manipulate geoTIFF files using gdal library
* The short paper in PDF 
* The poster presentation in PDF
* The dataset: 
  1. train_another     : the training data; 5000 images of each class
  2. validation_another: the validation data; 1000 images of each class
  3. test_another      : the unbalanced test data; 8000/1000 images of damaged/undamaged classes
  4. test              : the balanced test data; 1000 images of each class
