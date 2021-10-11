# Lab HMMER

[HMMER](http://hmmer.org/) implements methods using probailistic models (profile Hidden Markov Models, HMMs) to search sequence databases for sequence homologs. HMMER is designed to detect remote homologs as sensitively as possible, relying on the strength of its underlying probability models. HMMER can also work with query sequences, not just profiles, just like BLAST.

HMMER can be run [interactively](https://www.ebi.ac.uk/Tools/hmmer/) or through the command line

## Set up conda environment
```
conda create -n hmmer
conda activate hmmer
conda install -c bioconda hmmer
```
