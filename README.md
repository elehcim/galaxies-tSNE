# Visualize n-dimensional data from a galaxy catalogue (NIR Spitzer S4G data)

Jupyter notebook with the project work carried out during the first SUNDIAL training school in Groningen 22-26 January 2018.
We used PCA and t-SNE to visualize tabular data of the [Spitzer Survey of Stellar Structure in Galaxies (S4G)](http://irsa.ipac.caltech.edu/data/SPITZER/S4G/overview.html).
Data are taken [from here.](http://irsa.ipac.caltech.edu/workspace/TMP_nVrSqe_11202/Gator/irsa/22146/tbview.html)

To view the notebook go [here](https://github.com/elehcim/galaxies-tSNE/blob/master/Visualizing%20tabular%20data%20of%20S4G%20galaxies%20in%20infrared%20with%20PCA%20and%20t-SNE.ipynb).

If you want to run it locally see the following instructions.

### Dependencies
To install the python dependencies you can use conda:

	conda create -n tsne python=3 jupyter sklearn astropy matplotlib numpy pandas seaborn
	conda activate tsne  # or source activate if conda<4.4

### Run the notebook

	jupyter-notebook "Visualizing tabular data of S4G galaxies in infrared with PCA and t-SNE.ipynb"

## Useful Links
* [A nice webpage on how to use t-SNE effectively](https://distill.pub/2016/misread-tsne/): Wattenberg, et al., "How to Use t-SNE Effectively", Distill, 2016. http://doi.org/10.23915/distill.00002
* [Tutorial on Visualizing the data](http://nbviewer.jupyter.org/github/addfor/tutorials/blob/master/machine_learning/ml03v04_visualizing_the_data.ipynb)

### Authors
Michele Mastropietro, Josefina Michea, Crescenzo Tortora
