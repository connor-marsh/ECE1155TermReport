# Repository for Connor Marsh, Connor Murray, Sam Phillips, and Aaron Kuchta's Information Security report, on simulating control systems attacks.
## Installation Instructions
You need vpython and jupyter lab installed. You also need your python version 3.8, 3.9, 3.10
### Pip
You can do `pip install vpython` and `pip install jupyterlab-vpython`

### Conda
Install conda on your computer. Then in a conda prompt do `conda create --name [ENV_NAME]`
Then install vpython with `conda install -c conda-forge vpython=7.6.3`
Then install jupyterlab with `conda install -c conda-forge jupyterlab-vpython`

## Running it
### Starting Jupyter
From a terminal with the right environment, run `jupyter lab` and it will launch the jupyter client. Also it helps to run this command from the directory that contains this repository

### Running simulation
Press SHIFT+ENTER while in a code cell to run it. The simulation cell creates a button widget which will end the simulation when pressed
### Potential Error
If you encounter an error mentioning nbextensions, close the notebook and run “conda install jupyterlab=3.6.6” to revert to an older version, reopen the notebook and try running the cells again
