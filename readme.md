## Introduction

1. Switch to the project folder and create a conda environment (note: you must already have Anaconda installed):
```
$ conda env create -f conda.yaml
```

1. Activate the conda environment, then run the jupyter notebook server. (Note: windows users should run `activate hmm-tagger`)
```
$ source activate nlp-course
$ jupyter notebook
```

1. To update conda environment after new dependencies use
```
$ conda env update -f conda.yaml
```
