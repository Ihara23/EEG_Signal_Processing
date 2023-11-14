# EEG Eye Blink Detection

## Overview

This repository contains EEG (Electroencephalogram) signal data for eye blink detection. The dataset consists of two files: eeg_train.csv and eeg_test.csv. 
* Channels: 14 channels were used to capture EEG signals.
* Sampling Rate: Signals were sampled at 256 Hz.

## File Descriptions
1.eeg_train.csv:
* This file contains training data.
* Each row corresponds to a sample, and each column represents a different channel.
* The label column contains binary values:
'1' indicates the eye-closed state.
'0' indicates the eye-open state.

1.eeg_test.csv:
* This file is meant for testing and evaluating the trained model.
* Similar structure to eeg_train.csv but without the label column.
* Use this file to fit your model and make predictions on the test set.

## Data Exploration
* The first 1000 samples from the training set have been extracted for initial analysis and visualization.
* The eye blinking state is indicated in these samples to facilitate visual inspection.

##Correlation Analysis
* The correlation between EEG signals for two users has been computed.
* This information can be useful for understanding the relationship between the signals captured from different users.
