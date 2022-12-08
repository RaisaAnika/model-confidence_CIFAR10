# model-confidence_CIFAR10

Machine Learning is a part of every industry accross the worlds and thereby also imapcts our everyday lives. Though most of the times the beneficial side of these technologies are shown, yet some adversaries rises. Once such adversary is the leakage of sensitive data
In the python notebook : CIS545_Fall22_ModelConfidence_Main.ipynb 

CIFAR 10 dataset has been used to establish a mean of model securiry.
The aim was to divide the member data into 5 disjoint set and run them through a base model and derive their prediction confidence. 
The model which resulted in a higher prediction accuracy was then eliminated from model training to ensure that the attack result's accuracy would be dropped. 

The afore mentioned notebook can be ran sequentially and has been sectioned as below:

Relavent libraries installations:
Library Imports
Load Dataset - CIFAR 10
Data Explorations & Pre-processing
Machine Learning Model
Generating Subset of the Dataset
Model Tuning
Generate Prediction Vector
ATTACK 1 (Threshold attack) on each model
ATTACK 2 (MLP attack) on each model
Plotting of attack result to visualize the accuracy 

Attack on a Combination of all model probability vectors [with highest confidence]

Exclusion Oracle generation
Attack on the oracle and attack accuracy visualization


The additional notebook : CIS545_Fall22_ModelConfidence_increased_epoch.ipynb is for the purpose of displaying how increasing the iterations while training the model helps in improving privacy.
