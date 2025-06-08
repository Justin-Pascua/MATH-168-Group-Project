# Data
The full data set is stored in `full_opensecrets_data.csv`. As described in the project report, this was constructed using by merging the 100 csv's obtained from opensecrets.com as outlined in the `Preprocessing.ipynb` notebook. 

# The Notebooks
One does not need to download `full_opensecrets_data.csv` in order to run the notebooks. 

The `Centralities.ipynb` notebook was used to calculate the multiple centrality measures for each of the three networks.

The `Community_Detection.ipynb` notebook was used to perform community detection, plot heatmaps, and create Figure S1 in the report (which plots the distribution of edge weights in the bipartite graph).

The `Graph_Construction.ipynb` notebook was used to create the bipartite graph and the two projections as networkx objects. Note that this does not need to be imported by any of the other notebooks as the two notebooks above contain similar code for constructing the graphs. This notebook also contains some of the code used to create the basic graph visualizations.

The `Preprocessing.ipynb` notebook was used to create `full_opensecrets_data.csv`. 
