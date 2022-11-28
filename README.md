# XDD-Net: Explainable Dual Learning Deep (Neural) Network for Process Outcome Prediction

This project is a deep neural architecture designed for which uses two feature sets for learning (Dual Learning) and one feature set for explaining the model prediction.

## Project File Description
#### SQL scripts
The sql scripts to convert the three event logs into datasets that can be used as inputs for the model

#### Main experiment folder (XD2_Net_Rep)
The experiment is originally run on google colab (https://colab.research.google.com/).
To replicate the environment, directly upload this folder to the google drive and run the main notebooks.
If required to run in a local environment, save this folder in a suitable location and change the code which specifies the folder location appropriately.

##### Functions
Support functions for the main notebooks are written as packages in these files
* `experiment_setup.py` : To setup the frequent parameters used in the experiment
* `data_proc.py` : Data pre-processing functions
* `generate_inputs.py`: Generating input vectors with pre-processed dataset
* 
##### Main notebooks
* `XD2_Net.ipynb`: Main note book in which outcome prediction and generation of explanations is done
* `XD2_Net_Explanation_Evaluation.ipynb`: Notebook for evaluating the model performance and model explanations
