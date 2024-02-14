### Friends and Relatives - Manuscript Repository 

This is a repository associated with the manuscript titled: **"Friends and relatives: insight into conformational regulation from orthologues and evolutionary lineages using KIF and KIN"**

Authors: Dariia Yehorova, Rory Crean, Peter M Kasson, Shina Caroline Lynn Kamerlin

**Once a preprint is available, the repository will be updated to include a link to it.**

This repository provides the data needed to reproduce the calculations performed in the accompanying paper.


### Folders: 

The repository is broken up into several folders relating to the different aspects of the project. 

**substrate_parameters:** This folder contains the parameters for the substrates (simulated in their tetrahedral intermediate forms) used in the MD simulations. The substrates used are benzylpenicillin and cefotaxime and are covalently linked to Ser70 (TEM1 numbering). An example tleap file is included to show how these parameters can be used in an MD simulation. Please see the manuscript for a description of the parameterisation process. 

**md_simulations:** Input files used to run MD simulations for the different systems simulated. Topologies and coordinate files for each starting structure are also provided. 

**kif_analysis:** The analysis performed using [key interactions finder (KIF)](https://github.com/kamerlinlab/KIF) for the manuscript. The contacts and target variable values (a combintation of catalytic distances) were calculated on the computing cluster where the MD simulations were run. They were however merged inside this folder for the KIF analysis. Please see the Jupyter Notebooks for a detailed description of the analyses performed, alongside the manuscript. 



### Reproduce the Python Environment

To reproduce the python enviroment used in this work you can create a new virtual environment using a version of Python 3.11. With conda, could do this by typing:

``` 
conda create -n environment_name python=3.11
conda activate environment_name
``` 

Now, either clone/download this repository or download just the "requirements.txt" file provided with this repository. 

You can then install the required modules using:

``` 
pip install -r requirements.txt
``` 

After this, you'll have the required packages installed on your virtual enviroment to run the analysis with KIF or KIN. 


