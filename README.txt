This is the code appendix for paper
"Agreement, Diversity, and Polarization Indices for Approval Elections"

Download both data.zip and code.zip and unpack in the directory for the project.
=================================================================================

Folder structure overview:

"data" contains approval elections in the .app format

"data-creation" contains some of the code used for creating/parsing the data; running some of the code would require downloading respective source data

"src" many of the core functions including the functions to compute the index values

"workspace" executable Python files as well as computed outputs

"workspace/table_of_examples.py" code responsible for Table 1
"table-examples.json" contains results precomputed by table_of_experiments.py

"workspace/resampling_experiment.py" code responsible for Table 2 and "resampling experiment" row of Table 1
"resampling_experiment.json" contains results precomputed by resampling_experiment.py

"workspace/maps/" code responsible for Figures 2 and 3

"testing_suite/results_general/" the values of our indices for the main dataset

"testing_suite/results_pabulib/" the values of our indices for Pabulib elections

"testing_suite/old_data/" the values of indices from other papers

"testing_suite/run_suite.ipynb" Python notebook responsible for computing the index values

"testing_suite/analysis.py" code responsible for the analysis of the values, mostly for the purpose of Appendix C

"testing_suite/longtable.py" code responsible for Table 4

The following Python libraries are required for running our code:
-numpy
-matplotlib
-networkx
-scipy
-sklearn
-pandas
-pyparsing
-mapof
-pabutools
-prefsampling 
