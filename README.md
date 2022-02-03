# üK 259 Machine Learning

## Setup

## Install anaconda package manager

**Important! Install anaconda in a path without spaces (« »)**\
**Important! Be sure to select the option "Add Anaconda to my PATH environment variable" during installation**

https://docs.anaconda.com/anaconda/install/

Help: https://medium.com/@GalarnykMichael/install-python-anaconda-on-windows-2020-f8e188f9a63d

Test your installation by running `conda -V`

## Clone the GitHub-Repo

[GitHub Repo](https://github.com/LuWidme/uk259)

## Install dependencies in an environment

Navigate to the cloned directory and run:

`conda env create --file environment.yml`

Activate environment:

`conda activate uk259`

The command prompt should have changed to something like this:

`(uk259) C:\Work\ÜKs\259>`

run:
`ipython kernel install --user --name=uk259_kernel`

## Get started

Start **Visual Studio** in the current directory:

`code .`

Alternativiely, you can use **JupyterLab**:

`jupyter-lab .`

Your browser should open to a online IDE.

## Common Issues and fixes

- Make sure you are running your code in the correct environment (in this case uk259)
- Rerun your code from the beginning of the notebook one cell at a time
- If `conda -V` does not execute in a fresh terminal window, try to add the anaconda installation to your path environment variable or rerun the installation step and select the option "Add Anaconda to my PATH environment variable" during installation.
- If all else fails, delete your environment (you will not loose any progress) using the comand '`conda env remove uk259`' and reinstall the environment. Then restart your IDE.
