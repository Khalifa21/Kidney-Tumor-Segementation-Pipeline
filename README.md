## This repository shows a segmentation pipeline developed for the project of 'Deep Learning for Medical Images' course.
 
##### Pipeline is meant to help deep learning researchers in running different experiments easily by changing configuration file and running one command for the whole pipeline.
##### The goal of the project was to have a segmentation pipeline that has a proper data loader according to the data nature and allows the usage of the U-Net model with different enhancements (e.g. weighted maps, auto-context).   

##### I used this pipeline for a competition on kidney tumor segmentation https://kits19.grand-challenge.org/home/ 

### Pipeline consists of three steps: preprocessing, main task, postprocessing.

Preprocessing is to read competition data and save it in smaller size with certain structure (i.e. /Image for images and /Mask for masks). 

Main task is to train the model with availability of different kind of techniques (e.g. normal training, kfold training, weights maps, autocontext).

Postprocessing is meant for visualization and reporting, however for the project sake it is used for prediction.

To read more about the parameters you could use to build the pipeline, please read README file inside Keras directory.

If you would like to contribute for enhancements or have some questions, I will be happy to accept your contribution or answer your questions.
 