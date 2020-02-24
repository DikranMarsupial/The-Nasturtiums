# The Nasturtiums 

This repository is the home for Dikran Marsupial's unsorted collection of climate related Jupyter notebooks.  Why "The Nasturtiums"?  When Bertie Wooster gets arrested by the police, he generally gives his name and address as "Ephraim Gadsby of The Nasturtiums, Jubilee Road, Streatham Commmon."  I don't know why, it's just a whim [1].

## Projects:

### Replication and Investigation of Loehle and Scafetta (2011)

#### ls11_notebook_001.ipynb 

This notebook provides a basic implementation of the Loehle and Scafetta [2], hereafter LS11, cyclic model of global mean surface temperature.  This notebook just downloads the latest HadCRUT4-gl dataset from CRU and plots the LS11 model using the parameters given by [2], allowing us to see how the model's predctions have fared against the observations (rather badly).

#### ls11_notebook_002.ipynb 

Reproduction of the Loehle and Scafetta cyclic model of global mean surface temperature [2], fitted to the HadCRUT3-gl dataset, just to verify the parameters given by LS11.  


#### ls11_notebook_003.ipynb 

Reproduction of the Loehle and Scafetta cyclic model of global mean surface temperature [2], but this time fitted to the HadCRUT4-gl dataset.  It appears that the LS11 approach is not very robust to the choice of dataset used.  

#### ls11_notebook_004.ipynb 

Reproduction of the Loehle and Scafetta cyclic model of global mean surface temperature [2], fitted to the HadCRUT3-gl dataset, but with the periodicities of the cyclic components made tunable.  

#### ls11_notebook_005.ipynb 

As ls11_notebook_004.ipynb, but using the HadCRUT4-gl dataset instead of the JadCRUT3-gl data used in LS11.

## References

[1] Wodehouse, P. G., "Jeeves and the Feudal Spirit", Herbert and Jenkins, 1954.

[2] Craig Loehle and Nicola Scafetta, "Climate Change Attribution Using Empirical Decomposition of Climate Data", The Open Atmospheric Science Journal, volume 5, pages 74-86, 2011.
