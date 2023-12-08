# Detecting and Classifying Fallacies 

## Part1: Sliding Window
This folder encapsulates the sliding window approach from out presentation where we attempt to classify whether a pair of sentences is fallacious.
This folder contains the trained model and the notebook used in training the model. 
To run the notebook follow the following steps:

1) Unzip the dataset file.
2) Replace "/data/notebook\_files/datasets/" in load labeled passages function with the location of the unzipped dataset.
3) Make sure you have access to an Nvidia GPU (otherwise the training will fail, or you will need to change the code).
4) You are now able to run the notebook.

## Part2: SI

This folder encapsulates Part 2 of our presentation and is essentially our attempt at the SI task from Semeval 2020 Task 11. 
This folder contains already preprocessed data and the model files. In order to run the notebook, follow the following steps:

1) Open the notebook on Google Colab
2) Make sure the runtime used is GPU (CPU can be used but the model trains faster on a GPU)
3) Upload `train.txt`, `val.txt` and `vocabulary.pkl` to the runtime (which can be found in the folder).
4) You are all set! Feel free to simply click `Run All`



