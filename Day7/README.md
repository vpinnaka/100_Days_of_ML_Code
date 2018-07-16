## Clustering Algorithms

### Hirarchical Clustering
* **Single-link clustering**: Start with the assumption that every point is a single cluster and in next step the two closest points are grouped into clusters, a dendogram is drawn for all the clusted points, in futher steps merging two clusters based on minimum distance from the point in the clusters. This process is continued until one single cluster is left.
* **Complete-link clustering**: Similar to single link clsutering except for, while merging clusters it will takes into consideration of fartest distance beteen the poits in the cluster.
* **Average-link clustering**: Here, distance beteween every other point of the cluster in another cluster is considered and the average of these distances is distance from the clusters
* **Ward clustering**: In this method the center of two clsuters is caluculated and the square of the distance from each point in the cluster is added and the varaince(distance from each point to center of that cluster) is subtracted. Those clusters that have minimum values is merged

[Single-link clustering](https://www.youtube.com/watch?v=foLcmCOLDos)
[Agglomarative clustering techniques](https://www.youtube.com/watch?v=dWGQVcZ95d0)


### DBSCAN
* A density based clustering algorithm which can saperate noise form the clusters

[Density based spatial clustering Applications with Noise(DBSCAN)](https://www.youtube.com/watch?v=-dqyFkfnctI)