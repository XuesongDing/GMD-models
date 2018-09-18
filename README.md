# ESurf input


Supporting information that contains all the input and forcing conditions files required to reproduce the experiments from the manusript: **Interpretation of long-term stratigraphic sequences in a source-to-sink numerical framework**.

You will need to download and install <a href='https://github.com/badlands-model/pyBadlands/releases' target="_blank">Badlands v2.0.0<a/> to run these experiments.

[![DOI](https://zenodo.org/badge/51286954.svg)](https://zenodo.org/badge/latestdoi/51286954)

An easy installation is provided through our Docker image _(pyBadlands-demo-serial image)_.

## Content

+ **XmL file**: Main entry point for defining the initial and forcing conditions used by **Badlands** to run any model (this is required)
+ **data**: This folder contains the node file for initial surface, the sea-level file and the thermal subsidence. 
+ **images**: This folder contains images used in post-processing scripts.
+ **strataAnalyse.ipynb & strataAnalyse.py**: Post-processing scripts to visualize predicted stratigraphic architecture and associated interpretations. 
+ **Run_pybadlands.ipynb**: Model settings and run badlands model.
