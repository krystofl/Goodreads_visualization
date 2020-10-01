# Krystof's Getting Started Guide

This assumes you already have python3 installed, including virtualenv.

Install R and jupyter:

    sudo apt-get update
    sudo apt-get install -y r-base jupyter

Get submodule:

    git submodule init && git submodule update

Activate your virtualenv; call it `Goodreads_visualization` for simplicity.

Install python packages
(I suggest you do this in a virtualenv):

    pip install -r requirements_FULL.txt

Add the virtualenv to Jupyter
([source](https://janakiev.com/blog/jupyter-virtual-envs/)):

    python -m ipykernel install --user --name=Goodreads_visualization

Start the notebook:

    jupyter notebook README.ipynb

In the notebook, select the virtualenv: Kernel > Change kernel > Goodreads_visualization
