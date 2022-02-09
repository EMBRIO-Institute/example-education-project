# EMBRIO Institute Example Projects

 **View** | **Run with Binder** | **Run with Colab** |
| --- | --- | --- |
| [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/EMBRIO-Institute/example-education-project/) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/EMBRIO-Institute/example-education-project/HEAD) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/EMBRIO-Institute/example-education-project) |


[Binder](https://jupyter.org/binder) and [nbviewer](https://nbviewer.jupyter.org/) are open source [Project Jupyter](https://jupyter.org/index.html) tools that do not require authentication to use. (Binder enables you to launch an interactive instance of the notebooks in the repository. No changes will be saved. nbviewer simply renders the notebooks. This is now a built-in GitHub feature.)

[Google Colab](https://colab.research.google.com/notebooks/intro.ipynb) is a free cloud service provided by Google for executing Python code.

When running with Binder, you may also click [Voilà](https://voila.readthedocs.io/en/latest/?badge=latest) to open the notebook in a new tab with outputs from code cells evaluated and visible but with code cells suppressed from view for less clutter if desired.

## Description

Welcome to a example repository for the EMBRIO Institute!

This repository showcases students' work in Purdue's BME 695 Quantitative Systems Biology course project.

The major objective for this course is to study current problems in biology that are amenable to modeling, quantitative analysis, and systems biology approaches. The focus will be to understand current work on several aspects of embryo development, gene control networks, signaling cascades, and neurobiology, and to identify the component processes and associated modeling/mathematical tools needed to address them. These include basic material on how to model chemical reactions (both deterministically and stochastically) how to formulate a model of genetic regulatory networks, and how to model signaling via morphogens.

The final project in the course is an individual effort to create an exposition on a topic of the student's choice using Jupyter. The backbone of a notebook is the replication of some or all results in a peer-reviewed publication. Please click the links above to open a static rendering of the notebooks using nbviewer or an executable instance using Binder or Colab.

## Usage

To download and run these notebooks on your computer, clone the repository to a directory of your choice and create a virtual environment using [conda](https://docs.conda.io/projects/conda/en/latest/#) or, preferably, [mamba](https://mamba.readthedocs.io/en/latest/) for faster performance.

First, install your choice of conda ([miniconda](https://docs.conda.io/en/latest/miniconda.html#) or [Anaconda](https://www.anaconda.com/products/individual)).

Once this repository is cloned to your computer, the following commands need to be run from that directory:

Note: to access the embrio-institute-example-projects directory run the following

```
cd example-education-project
```

```
conda install mamba -n base -c conda-forge # Recommended for much faster performance
mamba env create --name example-education-project --file=environment.yml
```

(Note, you can name the environment anything you like; it doesn't need to match the repository name.)

Once the environment is set up, activate it by running:

`conda activate embrio-institute-example-projects`

Run Jupyter in your browser using `jupyter lab` or `jupyter notebook`.

When finished, run:
`conda deactivate`
