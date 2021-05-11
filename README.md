# Introduction

This repository is an assignment from UC Davis's Data Analytics bootcamp. It contains an .ipynb file that analyzes two datasets. The purpose of the excercise is to assess various drug therapies efficacies against cancer. Analysis was conducted using jupyter notebook, and several Python modules to manipulate the data and create various data visualizations from which observations and insights could be derived.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

<b> Project Discription </b>: Generate all of the tables and figures needed to produce a technical report of the study. 

## General Information
The data is from clinical trial data on 250 mice with Squamous cell carcinoma (SCC) growth. The mice were treated with various drug regimens over the course of 45 days. The purpose of the study is determine therapies efficacy in lowering the growth rate. 


## Technologies
```python
# Dependencies & Setup
import matplotlib.pyplot as plt
from matplotlib.pyplot import figure
import pandas as pd
import numpy as np
from scipy.stats import pearsonr
from scipy.stats import linregress
import dataframe_image as dfi
from pandas import DataFrame
```


## Setup
Load and open the Jupyter Notebook file in your computer.
```
git clone https://github.com/speedracer05/Matplotlib-Challenge.git
cd Pymaceuticals 
jupyter notebook 
```

## Built With
* Jupyter notebook Code Version: 6.0.3
Chrome: 87.0.4280.141
Node.js: 12.18.3
OS: Windows_NT x64 10.0.19042
* conda 4.10.0
* Python 3.6.10 Anaconda, Inc.
* Kite Pro Version: 1.2021.310.0

## Author
John Chan
