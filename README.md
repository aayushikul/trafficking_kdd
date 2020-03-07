# trafficking_kdd
Repo for reproducibility of KDD paper

Add escort ads dataset 'Trafficking-10k' to data/ folder in the main directory. 

Inside trafficLight folder, is the pipeline for the paper. In the jupyter notebook, the first cell contains constants for input and output files. Update as required. 

This jupyter notebook will create a csv with 'final_label' as the cluster assignement, and a property file containing some properties of the clusters.
These 2 files are used as input to the visualization module.

In the visualization/processing.py, update the file names and paths.

Run python processing.py to produce the visualized outputs in the form of word documents.
