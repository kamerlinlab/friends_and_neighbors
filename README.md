Tools follow up work with KIF.

The MD simulations and the KIF contacts calculation were run on a cluster with the contacts data added here for KIF analysis. The distances used to build the target variable for KIF were also calculated on the cluster but they are combined here (by summing the distances) to make the target variable. 


### Folders:

- raw_data: KIF calculated contacts for each trajectory. An MSA for each system to each other is also provided here ("align1d.ali"). 

- target_variable: The ".dat" files are the raw distances calculated for each trajectory. The ".txt" files is the target variable. This target variable is created in the notebook called: "make_target_variable.ipynb". 

- pdb_files: PDB files for each protein which is used to measure distances to the active site in the notebook called: 

- outputs: outputs from the kif analysis. 


### Notebooks:

In order in which they are run: 

- "1_make_target_variable.ipynb": Creates the target variable for KIF regression analysis and makes violin plots to show the distribution of the target variable. 

- "2_run_kif_regress.ipynb": Run the KIF regression analysis. 

- "3_analyse_kif_regress.ipynb": Analyse the KIF regression results. 

- "dist_to_active_site.ipynb": Calculates the distance to the active site for each residue in the different proteins. (Has no order in which it needs to be run). 


### Install/Enviroment

A "requirements.txt" file is included.
