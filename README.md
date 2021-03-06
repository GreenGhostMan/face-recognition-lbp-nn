# Face Recognition with LBP and NN
This repository contains the source code of the experiments done in the paper entitled ***"Face Recognition Using Local Binary Pattern and Nearest Neighbour Classification"*** . This work will be presented at [the 2018 International Symposium on Advanced Intelligent Informatics (SAIN 2018)](http://sain.ijain.org/) on August 29-30, 2018 in Yogyakarta, Indonesia.

## Structure of the source code
- **db folder** Contains three datasets used in this experiment, i.e. JAFFE, AT&T, and Yale
- **localbinarypatterns.py** The implementation of LBP using scikit-learn module
- **knn.py** The implementaion of the system using k-NN (k Nearest Neighbour)
- **rnn.py** The implementation of the system using RNN (Radius Nearest Neighbour)
- **akurasi.py** Analyse the system accuracy (recognition rate) in terms of their parameters (number of neighbour points P, the radius P, and the chosen k value of the k-NN)
- **plotting.py** Plot the histogram of the feature vector from the LBP output
- **results folder** Contains experiments results for both k-NN and RNN, saved in csv files
