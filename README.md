## DESCRIPTION
* Unsupervised Machine Learning and Cryptocurrencies.
The goal of this project is to analyze a dataset of cryptocurrencies in any way that would discover trends that could help
convince stakeholders to invest in these new cryptocurrencies, at affordable prices. We dive deeper into machine learning using unsupervised algorithms, which help us explore data when we’re not sure what we’re looking for or without a clear output in mind,
we only use input data. We work primarily with the K-means algorithm, the main unsupervised algorithm that groups similar data into clusters. We build on this by speeding up the process using principal component analysis (PCA), which employs many different features.

### SITUATION/TASK
Use an algorithm that helps us discover patterns or groups. First, process the data for an unsupervised model, 
then use the clustering and K-means algorithm, and finally make the model more efficient by using principle component analysis.

### APPROACH
Prepared data for dimensions reduction with PCA and clustering using K-means. Then, reduced data dimensions using PCA algorithms from sklearn. Next, used the K-means algorithm form sklearn to Predict clusters using cryptocurrencies data. Finally, created some plots
and data tables to present results.

### RESULTS
Created a 3D scatter plot using Plotly Express to plot the clusters using the clustered_df DataFrame.
Also created a scatter plot using hvplot.scatter to present the clustered data about cryptocurrencies having x="TotalCoinsMined"
and y="TotalCoinSupply" to contrast the number of available coins versus the total number of mined coins. Used hvplot to create a data table with all the current tradable cryptocurrencies.


* 3D Scatter Plot

<img align=" center" width="650" src= "/pics/3D_Scatter_Plot.png"><br/><br/><br/>

* Elbow Curve

<img align="center" width="650" src="/pics/Elbow_Curve.png"><br/><br/><br/>

* Clusters with Two Features

<img align="center" width="650" src="/pics/hvplot_Scatter_Clusters.png"><br/><br/><br/>
