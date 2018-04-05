## Aimed at: 
Anyone interested in learning how to use the FESetup tool to automatically prepare protein and ligand files for simple molecular dynamics simulations or alchemical free energy calculations In particular allowing for alchemical free energy calculation setups. It will also help with how to run actual molecular dynamics simulations from the generated input. 
You can obtain FESetup for yourself [here](http://www.hecbiosim.ac.uk/fesetup).

## Requirements: 
Basic knowledge of how to execute cells in a Jupyter notebook, and how to edit a text file in a terminal. Basic knowledge of being able to execute commands on a terminal. 

## Abstract: 
This workshop is designed to introduce you to how to use FESetup to prepare protein and ligand files to create simulation input for simple molecular dynamics simulations. It will also address how to then use Sire SOMD to run either a standard molecular dynamics simulation or alchemical free energy simulation. The workshop will provide a quick overview of what exactly alchemical free energy calculations are.

## Training Material

The workshop consists of a set of introductory slides covering the basics of alchemical free energy simulations and two Jupyter notebooks. These are available
below, and can be run using the
<a href="https://ccpbiosim.github.io/workshop/events/bristol2018/server.html" target="_blank">workshop Jupyter server</a>.

Once you have logged in, navigate to the `fesetup_workshop` directory and you will find the
notebooks there.

The two workshop notebooks are `01_FESetup_ethane_methanol.ipynb` and `02_Lysozyme_and_Advanced_FESetup.ipynb`. The two notebooks do not depend on each other, but the first one covers the basics of FESetup whereas the second one covers more advanced topics. 

Furthermore you can find model answers to the notebooks in the `answers` directory. The set of presentation slides can be found as a pdf in the `slides` directory. 


## Contents

### [01 FESetup Ethane Methanol notebook](html/01_FESetup_ethane_methanol.html) ([answers](html/answers/01_FESetup_ethane_methanol_answers.html))

This notebooks teaches how to setup an alchemical free energy calculation for computing the relative hydration free energy between ethane and methanol. 

[download](01_FESetup_ethane_methanol.ipynb) | [download answers](answers/01_FESetup_ethane_methanol_answers.ipynb)

### [02 Lysozyme and advanced FESetup topics](html/02_Lysozyme_and_Advanced_FESetup.html) ([answers](html/answers/02_Lysozyme_and_Advanced_FESetup_answers.html))

The second notebook will guide you through using FESetup for preparing protein simulations using different outputs as well as how to setup protein simulations with ligands bound. 

[download](02_lists.ipynb) | [download answers](answers/02_lists.ipynb)
