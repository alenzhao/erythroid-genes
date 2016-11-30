[![DOI](https://zenodo.org/badge/75213475.svg)](https://zenodo.org/badge/latestdoi/75213475)


This [Jupyter](http://jupyter.org/) notebook documents the process of creating
sets of mouse erythroid genes based on published papers and the human orthologs
of these genes.

See the [notebook](erythroid-gene-lists.ipynb) for details, and the [gene lists
directory](gene-lists) for the gene lists themselves.

If you would like to reproduce these results, you will need to install
prerequisites. The easiest way is to use
[bioconda](https://bioconda.github.io/). Install conda and set up bioconda,
then install the prerequisites into a new environment with:

```bash
conda create -n erythroid-gene-lists --file requirements.txt
```

Then change to that environment and run the jupyter notebook, which will open
the interactive notebook in your browser:

```bash
source activate erythroid-gene-lists
jupyter notebook erythroid-gene-lists.ipynb
```
