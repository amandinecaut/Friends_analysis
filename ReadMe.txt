How to run the code?

1) Install requirements.txt
2) Run make_dataset.ipynb in order to create a dataset.
The code will take a .csv file, transform the sentences into embeddings. The output will be a pickle file.
The code could create a dataset with a pickle file with directly 20PCA.
3) For PCA analysis:

- Run PCA2: 
* bar plot of explained variance depending on the differents PCAs
* graph of the PCA2 vs PCA1 with the cloud points of the targets (aka friend's names)

- Run clusters_all_episodes:
* Plot of all 20 clusters with their centers and the corresponding sentences
* Plot for each characters the percentage of each cluster
* Plot of the cloud point of the 50% points near the center of each and the plot of the convex hull
* start of the study of a unique charcter: Is it possible to define one character from his sentences?

