# Visualize n-dimensional data from a galaxy catalogue (NIR Spitzer S4G data)

Project work carried out during the SUNDIAL first training school in Groningen 22-26 January 2018.
Visualize tabular data of the [Spitzer Survey of Stellar Structure in Galaxies (S4G)](http://irsa.ipac.caltech.edu/data/SPITZER/S4G/overview.html).
Data are taken [from here.](http://irsa.ipac.caltech.edu/workspace/TMP_nVrSqe_11202/Gator/irsa/22146/tbview.html)

### Dependencies
To install the python dependencies you can use conda:

	conda create -n tsne python=3 jupyter sklearn astropy matplotlib numpy pandas seaborn
	conda activate tsne  # or source activate if conda<4.4

### Run the notebook

	jupyter-notebook tSNE.ipynb

## Usefu Links
* [A nice webpage by Google Brain on how to use t-SNE effectively](https://distill.pub/2016/misread-tsne/): Wattenberg, et al., "How to Use t-SNE Effectively", Distill, 2016. http://doi.org/10.23915/distill.00002
* [Tutorial on Visualizing the data](http://nbviewer.jupyter.org/github/addfor/tutorials/blob/master/machine_learning/ml03v04_visualizing_the_data.ipynb)

### Authors
Michele Mastropietro, Josefina Michea, Crescenzo Tortora
