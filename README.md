## Project Overview

This repository is dedicated to the project developed during the seminar 'Programming with Large Language Models'. The objective of this seminar was to explore the practical applications of Large Language Models (LLMs) by undertaking a project in any domain of our choice. Initially, our project aimed to implement selective sound cancellation using deep learning models. The concept involved identifying different sounds within an audio file and utilizing a deep learning model to suppress user-selected sounds. However, due to the unavailability of an adequate dataset, we encountered challenges in training the deepfilternet model specifically for baby sounds. Despite this setback, we have documented our progress with deepfilter training in the 'Future Work' section of this repository, hoping it may serve as a valuable resource for those interested in continuing this project.

## Notebooks and Files

- **Sound_Recognition_And_Cancellation.ipynb**: This notebook demonstrates the usage of Yamnet to identify the sounds present in the audio file and Deepfilter to suppress the noise in the audio file. An example audio file, `Speaking_and_applause.m4a`, is provided.
  
- **FutureWork_Training_deepfilternet_on_own_data.ipynb**: This notebook contains the steps we followed to use Deepfilternet to train it on baby sounds. The notebook concludes with the preparation of a configuration file.

## Environment Setup

- **requirements.txt**: This file contains all the pip libraries needed for this project.

The notebooks have been created in Google Colab. 

Feel free to explore and contribute to this project!
