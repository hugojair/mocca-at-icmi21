# MOCCA at ICMI21

This repository contains the data for the MICCA@ICMI21 grand challenge. Please refer to the main site at https://competitions.codalab.org/competitions/31432 for a description of the competition and detailed instructions for participation. Please refer to our workshop site at: https://mocha-grand-challenge.github.io/ for further information on the associated workshop. 

## Training data 

- Since we are using videos that cannot be publicly distributed, we provide participants with scripts that allow you to download all of the videos, fragment them into scenes and generate the sample videos for training. The labels for the scenes and additional metadata is also provided for your reference. The following files are provided in the **mocca-training.zip** file:
  * Dataset_ComicMischief_Training_Scene_Binary_Annotations.csv --> `Annotations and metadata information for the binary detection task (track 1).`
  * binary_detection.sol  --> `ground truth labels for the binary detection task (track 1) in the training set. There is one line per each of the videos in the Dataset_ComicMischief_Training_Scene_Binary_Annotations.csv file. Submissions to track 1 should adhere to this format.`
  * Dataset_ComicMischief_Training_Scene_Multiclass_Annotations.csv --> `Annotations and metadata information for the fine grained detection task (track 2).`
  * finegrained_detection.sol  --> `ground truth labels for the fine grained detection task (track 2) in the training set. There is one line per each of the videos in the Dataset_ComicMischief_Training_Scene_Multiclass_Annotations.csv file, and there is a column per each of the considered labels as indicated in the  Dataset_ComicMischief_Training_Scene_Multiclass_Annotations.csv. Submissions to track 2 should adhere to this format.`
  * Python scripts  --> `Off-the-shell scripts for downloading videos, segmenting them and generating the training scenes. The code is easy to use and have minimal requirements. `
  * ReadMe.txt   --> `Text file with details on how to run the scripts for generating the training data `



## Test data
(test.zip)

- We also provide participants with scripts that allow you to download all of the test videos, fragment them into scenes and generate the sample videos for training and testing. The labels for the training scenes is also provided. Please note this code will allow you to dowload both, training and test scnees. The following files are provided in the **test.zip** file:

Files:

  * Dataset_ComicMischief_Training_Scene_Binary_Annotations.csv --> `An updated version of the training-code version.`
  * binary_detection.sol  --> `ground truth labels for the binary detection task (track 1) in the training set. There is one line per each of the videos in the Dataset_ComicMischief_Training_Scene_Binary_Annotations.csv file. 
  * Dataset_ComicMischief_Training_Scene_Multiclass_Annotations.csv --> `Annotations and metadata information for the fine grained detection task (track 2).`
  * finegrained_detection.sol  --> `ground truth labels for the fine grained detection task (track 2) in the training set. There is one line per each of the videos in the Dataset_ComicMischief_Training_Scene_Multiclass_Annotations.csv file, and there is a column per each of the considered labels as indicated in the  Dataset_ComicMischief_Training_Scene_Multiclass_Annotations.csv.
  * Python scripts  --> `Off-the-shell scripts for downloading videos, segmenting them and generating the training scenes. The code is easy to use and have minimal requirements. `
  * sample-submissions-test --> `A directory with sample submissions for the final phase. You should prepare your submissions for Tracks 1 and 2 in a similar way as this files. `
  * ReadMe.txt   --> `Text file with details on how to run the scripts for generating the training and test data `




