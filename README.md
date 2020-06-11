# Clustering-of-Countries
Categorize the countries using some socio-economic and health factors that determine the overall development of the country. Further suggest the countries which are in dire need of financial aide.

#### Problem Statement

HELP International is an international humanitarian NGO that is committed to fighting poverty
and providing the people of backward countries with basic amenities and relief during the time
of disasters and natural calamities. After the recent funding programmes, they have been able
to raise around $ 10 million. Now the CEO of the NGO needs to decide how to use this money
strategically and effectively. The significant issues that come while making this decision are
mostly related to choosing the countries that are in the direst need of aid.
You need to categorise the countries using some socio-economic and health factors that
determine the overall development of the country. Then you need to suggest the countries
which the CEO needs to focus on the most.

#### Solution: 

The following steps were taken to arrive at the final countries.
- Step 1: Read and understand the data:
- Step 2: Clean and visualize the data:
- Step 3: Prepare the data for modeling
  - Step 3.1: Standardizing data: The data was scaled using standardScaler.
  - Step 3.2: Perform PCA and select the number of components:
- Step 4: Modelling with kMeans clustering
  - Step 4.1 Checking data compatibility with KMeans:
  - Step 4.2 Find out what should be the optimal number of clusters using SSD and
silhouette score:
  - Step 4.3 Performing KMeans with chosen number of clusters
- Step 5: Cluster Profiling
  - Step 5.1 Analysis based on the cluster ids
  - Step 5.2 Analysis of a particular cluster:
- Step 6: Modeling with Hierarchical Clustering
- Step 7: Final Analysis:

Though the clusters are formed differently with KMeans and Hierarchical Clustering, the top 9
countries which seems to be in direst need of aid are the same. The CEO needs to focus on the
following 9 countries
1. Liberia
2. Burundi
3. Congo, Dem. Rep.
4. Niger
5. Sierra Leone
6. Madagascar
7. Mozambique
8. Central African Republic
9. Malawi
