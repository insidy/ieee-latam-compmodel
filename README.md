# IEEE Latin America Transactions
## A computational model for identifying behavioral patterns in people with neuropsychiatric disorders

Supplementary code and documentation for the paper "A computational model for identifying behavioral patterns in people with neuropsychiatric disorders".

In code_and_model folder you can find the following files:
 - `EigenbehaviorsComparison.ipynb`: Data extraction from Depresson, Eigenbehavior calculation, plotting and comparison with other algorithms
 - `SimulatePatients.ipynb`: Python notebook that can be used to generate a number of patient records as described in the paper.
 - `modelo_mcare.owl`: OWL model used to simulate the patients
 

 You will need the DEPRESJON dataset shared by Garcia-Ceja et. al. to run the comparison and the simulation. 
 You can find it [here](https://zenodo.org/record/1219550#.YY5sn71Kj0o). [^1] 
 

In data folder you can find the simulation outputs generated with SimulatePatients.ipynb:
 - `n-people.xml`: Simulation output with n people.

[^1]: Make sure all files (scores, control and condition) are in the same folder as the notebook.