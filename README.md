# MOCCA at ICMI21

This repository contains the data for the MICCA@ICMI21 grand challenge. Please refer to the main site at https://competitions.codalab.org/competitions/31432 for a description of the competition and detailed instructions for participation.

## Training data 

- Since we are using videos that cannot be publicly distributed, we provide participants with scripts that allow you to download all of the videos, fragment them into scenes and generate the sample videos for training. The labels for the scenes and additional metadata is also provided for your reference. The following files are provided in the **mocca-training.zip** file:
  * Dataset_ComicMischief_Training_Scene_Binary_Annotations.csv --> `Annotations and metadata information for the binary detection task (track 1).`
  * binary_detection.sol  --> `ground truth labels for the binary detection task (track 1) in the training set. There is one line per each of the videos in the binary_detection_metadata.csv file. Submissions to track 1 should adhere to this format.`
  * Dataset_ComicMischief_Training_Scene_Multiclass_Annotations.csv --> `Annotations and metadata information for the fine grained detection task (track 2).`
  * finegrained_detection.sol  --> `ground truth labels for the fine grained detection task (track 2) in the training set. There is one line per each of the videos in the finegrained_detection_metadata.csv file, and there is a column per each of the considered labels as indicated in the  finegrained_detection_metadata.csv. Submissions to track 2 should adhere to this format.`
  * Python scripts  --> `Off-the-shell scripts for downloading videos, segmenting them and generating the training scenes. The code is easy to use and have minimal requirements. `
  * ReadMe.txt   --> `Text file with details on how to run the scripts for generating the training data `



## Test data

Code for downloading the test data that will be used in the final phase will be posted here.

