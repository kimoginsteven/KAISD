# KAISD
This repository contains the dataset, code, and pretrained models for KAISD (Korean language Alcohol Intoxicated Speech Detector).
This project was done for 2020 Fall KAIST CS470 course and was done by Team 9 (SeokJun Kim, Jeongeon Park, and Sujin Han).

## Dataset and Preprocessing

All the audio files for our collected data is in "CS group project wav recordings" folder.
The code for preprocessing (splitting audio files into 8 second segments and converting audio files to mel spectrograms) is in data_preprocessing.ipynb.

## Code for Training and Evaluation

The code for training and evaluation is split into two files KAISD_final.ipynb and KAIS_final_with_modifications.ipynb.
KAISD_final contains code for conv_original, pretrained_original, and inception_5.
KAISD_final_with_modifications contains code for all other models.
KAISD_final_with_modifications also contains code for visaulizing CNN filters and intermediates layers.

## Pretrained Models

The pretrained models can be found in the "models" folder. The pretrained models for conv_original, pretrained_original, and inception_5 can be found in "models/without_modifiction" while pretraiend models for all other models can be found in "models/with_modification".

## Link to Google Drive

Only codes (.ipynb files) and audio files labels (.csv files) are uploaded in this Github repository. To access pretrained models and other files necessary to run this code, please go to our google drive provided below.

https://drive.google.com/drive/folders/1e2BpwiHKOx6Zr9nq5CSd0H7dWHD9kX6J?usp=sharing

### Instructions for running our code

Please add a link to the given google drive folder in your Google Drive by clicking the upside-down triangle icon next to "root_for submission" and "Add Shortcut to Drive". Also, you should change the root variable at the beginning of every .ipynb file so that the root variable is the address of the "root_for_submission" in your Google Drive.  
