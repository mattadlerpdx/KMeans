# KMeans
In Machine Learning there is supervised learning (data already with labels) and unsupervised learning (data without labels). KMeans is the latter. 

This algorithm clusters data points based on Euclidean distance between data points and a random centroid in the data. Centroids get updated based on averages of datapoints and within a cluster. That average becomes the new centroid. 

Flow of Algorithm:

Randomize centroids.

For each data point, assign data point to clusters (a centroid represents a cluster) based on Euclidean distance.
(Euclidean Distancerepresents similarities in data).

<img width="531" alt="Screen Shot 2022-08-31 at 11 37 29 AM" src="https://user-images.githubusercontent.com/63027273/187754248-362b97b3-14e3-459f-aaf2-75ced225145f.png">

Update centroids: 

For each cluster, get the average of all datapoints. 

Average = new centroid.


https://www.ibm.com/cloud/blog/supervised-vs-unsupervised-learning




To Run File:

- Install Jupyter Notebook: If you haven't installed Jupyter Notebook on your computer, you can do so by following the instructions on their website: https://jupyter.org/install
- Open Jupyter Notebook: Once you have installed Jupyter Notebook, open it by typing jupyter notebook in your terminal or command prompt.
- Navigate to the directory containing the .ipynb file: In Jupyter Notebook, navigate to the directory where the .ipynb file is located.
- Open the .ipynb file: Click on the .ipynb file to open it in Jupyter Notebook.
- Run the code: You can run the code in the .ipynb file by clicking on the "Run" button or by pressing "Shift + Enter" on your keyboard. You can also run all the code in the notebook by clicking on "Cell" in the menu bar, then "Run All."
