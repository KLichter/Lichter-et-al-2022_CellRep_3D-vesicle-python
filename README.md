# Lichter-et-al-2022_CellRep_3D-vesicle-python
This code is intended to support 3D coordinate analysis for IMOD model output of presynaptic active zones of giant hippocampal mossy fiber boutons. 

To use the code please follow the instructions in this file and the selected notebook. 
1. download Aanaconda (https://www.anaconda.com/distribution/#download-section).

2. open Anaconda prompt and create new environment.
```
conda create --name lichter_tomo-active-zones
```
activate new environment.
```
conda activate lichter_tomo-active-zone
```
install some dependencies.
```
conda install jupyter scikit-learn sklearn numpy scipy shapely statsmodels 
```

start jupyter notebook from Anaconda prompt.
navigate to and select one of the four notebooks.
follow the instructions in the notebook to analyze the exemplary text files (az-test_area/sv-pool/docked-sv-pool).
open animal-variability_LMM-bootstrapping.html for an executed version of the LMM and bootstrapping analysis.
