## Overview

This repository includes the Pytorch implementation of the paper "Ensembles of Deep LSTM Learners for Activity Recognition using Wearables" by Yu Guan and Thomas Plötz, which is available at: https://doi.org/10.1145/3090076

You can find the authors' original implementation in tensorflow at: https://github.com/tploetz/LSTMEnsemble4HAR

To run the code, open up "1.0-dsp-LSTMsEnsemble.ipynb" jupyter notebook under notebooks folder and follow the step by step instructions.

## Dependencies

- Python 3 <br/>
- Pytorch

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data     
    │   └── processed      <- The final, canonical data sets for modeling.
    │
    ├── models             <- Trained models
    │
    ├── notebooks          <- Jupyter notebooks. 
    │    └── 1.0-dsp-LSTMsEnsemble.ipynb  <-- Full Pipeline in a step by step manner                   
    │                       
    └── src                <- Source code for use in this project.
        ├── __init__.py    <- Makes src a Python module
        │
        └── data           <- Scripts to download or generate data
            └── dataset.py      
   
--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
