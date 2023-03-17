# Tree roots impact on pipes and tree rearrangement solutions

This public repository provides an extended version of the methodology and results of the research work called "Towards securing wastewater networks: Tree roots impact on pipes and tree rearrangement solutions". For more information and documentation, please check the original manuscript.

## License 

GNU v3 Public License. See LICENSE.

## Assets

The implemented algorithms use the following assets:

 - *./assets/Girona_Trees_2022_Up_2023.csv*: The tree dataset of the case study of Girona.
 - *./assets/Girona_City_Sewer_V5.graphml*: The wastewater network of the case study of Girona in graphml format.

## Algorithms

This public repository contains a JupyterHub notebook that is the implementation of the algorithms described on the research work called "Towards securing wastewater networks: Tree roots impact on pipes and tree rearrangement solutions". All of them are implemented in python.

 - *./algorithms.ipynb*: Main file of the JupyterHub notebook. The file is full of comments to understand the code implementations, easy to be adapted to other case studies.

## Results

This public repository also contains the results for the original case study of Girona:

 - *./results/htmls*: Folder containing the generated HTML interactive maps. 
 - *./results/pdfs*: Folder containing the genetared PDF images (vectorial, without quality loss on zoom) used in the manuscript and additional ones.
 - *./results/pickles*: Folder where the python pickles are stored (i.e., the raw data processed by the algorithms, in order to achieve a fast execution between sessions and avoid recomputations).
 - *./results/pngs*: Folder containing the genetared PNG images (same as PDF, used for presentations, with quality loss on zoom).

## Installation

First, clone this repository in your machine, install python3 (https://realpython.com/installing-python/) and conda (https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

Then, install the osmnx conda environment (https://anaconda.org/conda-forge/osmnx).

Finally, try to execute the notebook, and if some package is missing installation, install it with:

```
pip3 install package_name
```

You are ready to rock!