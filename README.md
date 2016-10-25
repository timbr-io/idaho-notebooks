# idaho-notebooks

## Setup

The setup procedure assumes that Continuum.io's [Anaconda Python Distribution](https://www.continuum.io/downloads) is installed and you have already cloned this repository onto your computer.  From this folder, create a conda environment named "ship", with the necessary dependencies installed, activate it, and launch the jupyter notebook using the following commands:

```Bash
idaho-notebooks $ conda env create -f environment.yml
idaho-notebooks $ source activate ship
idaho-notebooks $ pip install git+git://github.com/timbr-io/idaho-map.git
(idaho) idaho-notebooks $ jupyter notebook
```

Make sure that your gbdx credientials are setup at `$HOME/.gbdx-auth` according to the instructions [available here](https://github.com/TDG-Platform/gbdx-auth#ini-file)

### Environment Setup Issues

If you already have an environment name "ship" setup, setup will fail.  Removing the "ship" environment by running `conda env remove -n idaho` will allow setup to succeed.

## Running the notebook

Just execute the cells!
