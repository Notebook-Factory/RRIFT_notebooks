# RRIFT_notebooks

Paper: https://onlinelibrary.wiley.com/doi/full/10.1002/mrm.27913 <br> 
Code: https://github.com/MPUmri/RRIFT <br> 
Note: MATLAB. Reproduces ALL figures

# Setup instructions

## Prerequisites

Make sure you download ```simResults.mat``` and ```simMap.mat``` from the [OSF repository](https://osf.io/wr3kf/files/) and place it inside ```./RRIFT/data/```. Also make sure you have [```Anaconda 3```](https://www.anaconda.com/products/individual) installed on your system as well as ```MATLAB R2020b```.

## Installing MATLAB

You can download MATLAB from [here](https://uk.mathworks.com/downloads/).

## Making a conda environment

* ```conda create -n rrift_notebook python=3.6``` (you can set ```rrift_notebook``` to whatever you want the name of your environment to be)
* ```conda activate rrift_notebook```

## Setting up SoS and MATLAB 

* ```conda install sos sos-pbs -c conda-forge```
* ```conda install sos-notebook jupyterlab-sos sos-papermill -c conda-forge```
* ```conda install sos-python sos-matlab -c conda-forge```

## Installing Python packages

* ```pip install plotly=4.14.3 numpy=1.19.5 scipy=1.6.0 statsmodels=1.6.0 pandas=1.2.0```

## Start a Jupyter session

* ```jupyter notebook```
