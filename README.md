# Sequential deep learning models for prediction of potent BACE1 hits  
**Summary**

This repository contains data used for JCIM paper: **Sequential Deep Learning Models Driven Novel Virtual Screening Workflow for the Identification and Biological Evaluation of BACE1 Inhibitors.** All the constructed hyperparameter tuned DNN models trained on 10 datasets with different random seeds were assigned a task to make a prediction on the screening library for the collection of potent inhibitors against BACE1. 

The labelled 10 datasets provided in the folder "balance_chem_pub" contains files in csv format that are used for DNN model generation . The folder "Screening library" contains maybridge library represented in the form of maacs fingerprints  

To visualise the docking poses , the Pymol open source version was used.
The folder "BACE1_and_Hits" contains cocrystallized protein, preprocssed protein and shortlisted hits represented in pdb format 
The folder "Docking_poses" contains all the files in pdb format. Each filename is written by its maybridge code name. Each contains hits docked with the BACE1 protein.

In each of the folders, a text file is also provided that gives the description of each of the files.  

The rest of the information containing graphs, step wise methodology used for virtual screening and comparison of performance of different models represented in the form of both tabular and graphical fomat and other details are provided in the Supplementary Information of the publication.






