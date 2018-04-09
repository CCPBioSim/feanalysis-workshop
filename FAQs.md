
# FAQs
The following represents FAQs in a very loose term. The document essentially covers anything that might be useful to know and have compiled in one document. The first section `1. Running the workshop notebooks` is only specifically for the CCP BioSim Workshop in April in Bristol. All further topics are more general FAQs to get sire to work smoothly. 


### 1. Running the workshop notebooks

In order for the workshop notebooks to run successfully a couple of steps will have to be carried out for this. 

1. Log into the notebook server: [Login](https://workshop.biosimspace.org/hub/tmplogin)
2. Navigate to the tab new on the top right hand side to open a terminal. 
3. In the terminal type: `update_workshops`
4. Navigate to fe_analysis: `cd fe_analysis`
5. Update the Sire patch by running `bash patch_sire.sh`
6. Make sure freenrgworkflows is installed by typing `pip install freenrgworkflows`

Then open the first notebook at start working with them. If you run into trouble please contact antonia.mey@ed.ac.uk.

### 2. Running SOMD on your GPU accelerated computer at home
Often you may get an error that seems a bit cryptic when you try and run somd on a GPU supported computer. Here are common problems you may encounter:   

1. Have you set the `OPENMM_PLUGINS_DIR` environment variable? This is done by simply either adding the following to your `~/.bashrc` or typing into your terminal `export OPENMM_PLUGINS_DIR=/path/to/sire/home/lib/plugins `  
2. Have you checked that you have the right version of CUDA installed that is supported with the compiled version of OpenMM? Click [here](insert/useful/link) to find out more. 
3. Check the platforms you have available after trying 1 and 2. Do you now ave access to your GPUs?

### 3. Automatic simulation setup and slurm submission scripts
More information on this will follow shortly.