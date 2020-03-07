# trafficking_kdd
Repo for reproducibility of KDD paper

Add escort ads dataset 'Trafficking-10k' to data/ folder in the main directory. 

Inside trafficLight folder, is the pipeline for the paper. In the jupyter notebook, the first cell contains constants for input and output files. Update as required. 

This jupyter notebook will create a csv with 'final_label' as the cluster assignement, and a property file containing some properties of the clusters.
These 2 files are used as input to the visualization module.

In the visualization/processing.py, update the file names and paths.

Run python processing.py to produce the visualized outputs in the form of word documents. Three documents are produced corresponding to the three classes as per the average label of the cluster (corroboration, scooping, new attack discovery.)


For the canada data, there are no labels provided. Thus the only output is a single file as we cannot categorize data into classes. The pipeline and visualization codes are in trafficLight/canada_data.ipynb and visualization/processing_new.py respectively.

The code for baselines is in the nlp_techniques module.

Though the code is not modular currently, we plan to do it after our research phase when we are closer to converting it into a product.
