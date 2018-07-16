## Gaussian Mixture model 

GMM is a advanced method with each point belonging to all the clusters, each point will have a propability correspoinding to every other cluster.

**Expectation-Maximization Algorithm**:

* Initialize the K Gaussian distributions (K-Means can be used for this) 
* Soft-cluster the data(Expectation step)
* Re-estimate the gaussians(Maximization steps)
* Evaluate log-likelihood to check for convergance
* Repeat from step#2 until converges

[Overview of the GMM](https://www.youtube.com/watch?v=XdQfFnnj5Xo)

[Expectation Maximization part 1](https://www.youtube.com/watch?v=cf-RLKn5ubA)

[Expectation Maximization part 2](https://www.youtube.com/watch?v=B_xXd0mFUm4)

## Cluster validation techniques

* **External indices**: when cluster lables are provided for each point
    * [Adjusted Rand Index](https://www.youtube.com/watch?v=rXZM5X2-5D0)
* **Internal indices**: no lables are provides
    * [Shilouette Cofficients](https://www.youtube.com/watch?v=39JruOTptKI)