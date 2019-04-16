# Computer Vision Model for my W210 Project

**[Project Overview](https://docs.google.com/presentation/d/1Fi1OmfEWdFu1Ia78LGhylEfKgvrozeYX9Z_VCgd1gjE/edit?usp=sharing) (updated with final model performance evaluation)**

### This repo contains my code for:
 - exploring the 2017 COCO training data,
 - augmenting images,
 - updating and creating COCO annotation files,
 - re-training object detection models, and
 - evaluating model performance
 
#### CLEAN UP IS IN PROGRESS!
To be added:
 - instructions for use,
 - a public AMI for this project in particular, and
 - lessons learned / suggestions for improvements and future development
 
## Data
 - This project used the 2017 COCO (Common Objects in Context) training and validation [data](http://cocodataset.org/#download).

## Toolkits
 - This project leveraged the [GluonCV](https://gluon-cv.mxnet.io/index.html) deep learning toolkit for computer vision.
 - GluonCV is built upon the popular [Apache MXNet](http://mxnet.incubator.apache.org/) deep learning library.
 
 ## Training Environment
  - To train any of the GluonCV models on an Amazon EC2 instance, I recommend the following:
    * AMI Name: Deep Learning AMI (Ubuntu) Version 22.0
    * AMI ID: ami-060865e8b5914b4c4
    * Instance Type: p2.xlarge
  - You'll just need to use the python 3 MXNet virtual environment and install GluonCV ('pip install gluoncv --upgrade').
 
