### KIF Analysis

As described in the main README file, this subfolder contains the analysis performed for the manuscript involving the tool [key interactions finder (KIF)](https://github.com/kamerlinlab/KIF). 

### Folders 

The folders inside this section contain as follows: 

- **raw_data:** KIF calculated contacts for each trajectory. An MSA for each system to each other is also provided here ("align1d.ali"). 

- **target_variable:** The ".dat" files are the raw distances calculated for each trajectory. The ".txt" files is the target variable. This target variable is created in the notebook called: "make_target_variable.ipynb". 

- **pdb_files:** PDB files for each protein which is used to measure distances to the active site in the notebook called: 

- **outputs:**  Outputs from the kif analysis. 


### Notebooks:

The order in which they are run matters. You can use the virtual enviroment as described in the main README file in order to run these notebooks. 

- "1_make_target_variable.ipynb": Creates the target variable for KIF regression analysis and makes violin plots to show the distribution of the target variable. 

- "2_run_kif_regress.ipynb": Run the KIF regression analysis. 

- "3_analyse_kif_regress.ipynb": Analyse the KIF regression results. 

- "4_analyse_kif_per_feat_scores.ipynb": Specific analysis focussed on the per feature scores. 

- "dist_to_active_site.ipynb": Calculates the distance to the active site for each residue in the different proteins. (Has no order in which it needs to be run). 