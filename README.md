# Clustering_Crypto

this is a Jupyter notebook that clusters cryptocurrencies by their performance in different time periods. and plot the results so that you can visually see the performance 

---

## Technologies

This project leverages python 3.7 with the following packages:

* [tqdm](https://tqdm.github.io/) 
* [hvplot](https://hvplot.holoviz.org/index.html#) 
* [scikit](https://scikit-learn.org/stable/)
* [pathlib](https://docs.python.org/3/library/pathlib.html)
* [pandas](https://pandas.pydata.org/docs/index.html)


---

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install pandas 
  pip install scikit
  pip install hvplot
  
```
import pandas as pd
import hvplot.pandas
from path import Path
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler

---

## Usage

Upon launching the Clustering Crypto application you will be greeted with the following prompts.

![clustering cryptos prompts](images/pic1.png)
![clustering cryptos_Prompts](images/pic2.png)


---


## Contributors

Israel Fernandez

---
