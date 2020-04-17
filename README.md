
# How to use Conda to manage virtual environments

## Clean up the conda env:
```sh
conda clean -a
```

## Update the conda env:
```sh
conda update --update-all
```

## To get the version numbers of the python:
```sh
conda search "^python$"
```

## Create a new virtual environment:
```sh
conda create -n [vm name] python=x.x
```
e.g.
```sh
conda create -n test python=3.8
```

## List the existing virtual envs:
```sh
$ conda env list
```
or
```sh
$ conda info --envs
```

## Activate the environment you have created:
```sh
$ conda activate [vm name]
```


## Install additional packages into the specific environment:
```sh
$ conda install -n [vm name] [package]
```

## Deactivate the environment = end the session:
(assume that you are in the environment)
```sh
$ conda deactivate
```


## Delete the existing environment (you do not need it):
```sh
$ conda remove -n [vm name] --all
```
