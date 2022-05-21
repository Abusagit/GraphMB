# GraphMB: Assembly Graph Metagenomic Binner (_modified by F.Velikonivtsev as a part of Bioinformatics Institute spring 2022 project_)

# Introduction

GraphMB is a Metagenomic Binner developed for long-read assemblies, that takes advantage of graph machine learning 
algorithms and the assembly graph generated during assembly. It has been tested on (meta)flye assemblies.
Our preprint: 
> Lamurias, A., Sereika, M., Albertsen, M., Hose, K., & Nielsen, T. D. (2022). Metagenomic binning with assembly graph embeddings. BioRxiv, 2022.02.25.481923. https://doi.org/10.1101/2022.02.25.481923

## Dependencies

GraphMB was developed with Python 3.7, Pytorch and DGL.
It depends on VAMB to generate initial embeddings and  clustering, and CheckM to guide the training process and evaluate the output.
VAMB, Pytorch and DGL are installed automatically. 

## Installation
Easiest way to install it is the following:

Clone this repository, and then:
```bash
cd GraphMB
conda activate graphmb
pip install .
```

# For Full documentation please follow original [page](https://github.com/MicrobialDarkMatter/GraphMB) (it was removed to leave core installation aspect emphasized) 
