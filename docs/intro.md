# Introduction

Welcome to the documentation for napari-stress! This ressource provides information, links and examples to navigate and use the functionality of napari-stress, which provides the code for [Gross et al. (2021): STRESS, an automated geometrical characterization of deformable particles for in vivo measurements of cell and tissue mechanical stresses](https://www.biorxiv.org/content/10.1101/2021.03.26.437148v1).

## Contents

- [Functions](glossary/Readme.md): Overview about modular functions in napari-stress and how to use them from code or interactively from the napari viewer. 

- [Toolboxes](02_toolboxes/Readme.md): Key feature for retrieving all measurements napari-stress has to offer with minimal amount of coding/interactive analysis.

![](imgs/viewer_screenshots/all_outputs.png)

- [Workflows](03_workflows/Readme.md): Set of workflows, the entirety of which make up the functionality that is embedded in the toolboxes.

- [Utilities](04_utility/Readme.md): Other interesting pieces of code or widgets.

## Installation

In order to make napari-stress on your machine, you can follow these tutorials:

- [Getting started with Python and Anaconda](https://biapol.github.io/blog/johannes_mueller/anaconda_getting_started/): If you have not yet installed Python or Anaconda on your computer, this explains how to set it up and create an environment that contain the most basic functionality ([napari](https://napari.org/stable/) & [Jupyterlab](https://jupyter.org/))
- [Devbio-napari](https://github.com/haesleinhuepf/devbio-napari): Not strictly necessary but strongly recommended - this package brings many handy functionalities to an otherwise quite plain napari-viewer.

After both of these are installed, install napari-stress into the environment you created by typing

```
pip install napari-stress
```

in your Anaconda prompt. If you encounter any issues during installation, please 

* browse the [FAQ section](FAQ:installation) for known issues
* file an [issue on github](https://github.com/BiAPoL/napari-stress/issues)
* check out the [image.sc forum](https://forum.image.sc/) for help (Please tag @EL_Pollo_Diablo to notify the developers)