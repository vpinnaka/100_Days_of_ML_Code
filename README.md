# 100_Days_of_ML_Code
This is the repository to showcase my work for accomplishing 100DaysofMLCode

### Day 1: July 5, 2018 

**Today's Progress**: I've created repository for exploring titanic data set.

**Thoughts** Earlier I was using MOOCS for learning ML, while doing assignments they have provided the sample codes which never gave me a chance to code completly from scratch. But now I came to know that I have to work on basic pandas syntax and need lot of understanding to code from scratch

**Link(s) to work**
[Titanic dataset exploration](https://github.com/vpinnaka/100_Days_of_ML_Code/blob/master/Day1/Titanic%20Dataset%20Exploration.ipynb)

### Day2: July 7, 2018 

**Today's Progress**: I've analyzed the dataset for categorical, continious features.

**Thoughts** Analaysing each attributes is time taking if we have more number of features

**Link(s) to work**
[Titanic dataset exploration](https://github.com/vpinnaka/100_Days_of_ML_Code/blob/master/Day2/Titanic%20Dataset%20Exploration.ipynb)

### Day3: July 8, 2018 

**Today's Progress**: Completed K-Means clustering videos in Udacity ML Nanodegree .

**Thoughts** K-Means clustering have limitations, the major one local minima. When the centeroids are inteitalies to local minima while picking randomly will cause failure of K-Means clustering. One way is to run K-Means algorithem multiple times and get the ensemble of all the phases. If more number of clusters are assigned the more local minimas exists.

**Link(s) to work**
[K-Means Visulization](http://www.naftaliharris.com/blog/visualizing-k-means-clustering/)
[sklean K-Means](http://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)


### Day4: July 9, 2018 

**Today's Progress**: Started working on K-Means clustering mini project in Udacity ML Nanodegree .

**Thoughts** K-Means clustering have limitations, the major one local minima. When the centeroids are inteitalies to local minima while picking randomly will cause failure of K-Means clustering. One way is to run K-Means algorithem multiple times and get the ensemble of all the phases. If more number of clusters are assigned the more local minimas exists.

**Link(s) to work**
[k-means Clustering of Movie Ratings](https://view5c8205b9.udacity-student-workspaces.com/notebooks/k-means%20Clustering%20of%20Movie%20Ratings.ipynb)

### Day5: July 10, 2018 

**Today's Progress**: completed K-Means clustering mini project in Udacity ML Nanodegree .

**Thoughts** Recommendation engine that is coded in this project can be extended to other datasets such as item recommendation for Amazon or restauerent recommendation engine etc. In this mini-project Ihave graspd the overview of recommendation engines but coding a recommendation engine from scratch will defnitly help me to learn better and utilizing other algorithems for clustering will be a better approach. 

**Some Improvement**
* Colloborative filtering is performed here, but need to investigate other approaches
* Convert this to a flask api so that I can develop a freontend on top this

**Link(s) to work**
* [siraj raval AWS DSSTNE](https://www.youtube.com/watch?v=eKmIVU8EUbw) this video includes a paper about recommendation engines read this
* [siraj raval recommendation system](https://www.youtube.com/watch?v=9gBC9R-msAk)

### Day6: July 12, 2018 

**Today's Progress**: Worked on Titanic dataset project and analysed the impoertant features that contribute to the Survival.

**Thoughts** Makeing data assumptions and verifying them by anylizing the data is the first step to understand data. Any data science project requires this phase. 

**Link(s) to work**
[Titanic dataset exploration](https://github.com/vpinnaka/100_Days_of_ML_Code/blob/master/Day6/Titanic%20Dataset%20Exploration.ipynb) 

### Day7: July 14, 2018 

**Today's Progress**: Completed Hirachical clustering techniques and DBSCAN.

**Thoughts** Hierarchical clustering techniques are useful to get more info about dataset by the dendogram it creates. Dendogram will visulize the capability to cluster the points. DBSCAN on the other hand is efficient for data with noise and can beat any other algorithem in this case

**Link(s) to work**
[Hierachical clustering](https://github.com/vpinnaka/100_Days_of_ML_Code/blob/master/Day7/Hierarchical_clustering/Hierarchical%20Clustering%20Lab.ipynb) 
[DBSCAN](https://github.com/vpinnaka/100_Days_of_ML_Code/blob/master/Day7/DBSCAN/DBSCAN%20Notebook.ipynb)

### Day8: July 15, 2018 

**Today's Progress**: Completed Gaussian mixture model.

**Thoughts** GMM is a propabilistic algorithm where every point will have propabilities of each cluster. Expectation maximization algorithm is ued to find GMM. Also studied cluster validation techniques such as Adjusted Rand Index, Shilouette Cofficients

**Link(s) to work**
[Gaussian mixture model](https://github.com/vpinnaka/100_Days_of_ML_Code/blob/master/Day8/GMM_Clustering/GMM%20Clustering%20and%20Cluster%20Validation%20Lab.ipynb) 

### Day9: July 16, 2018 

**Today's Progress**: Worked on Titanic dataset project and visualized the features with pandas that contribute to the Survival.

**Thoughts** Pandas provides a simple Univariate plotting visualization tools such as bar graph(nominal categorical data), line graph(ordinal categorical data) and histograms(interval data). The important features of titanic data are visualized with pandas with Survivals as single variable.

**Link(s) to work**
[Titanic dataset exploration](https://github.com/vpinnaka/100_Days_of_ML_Code/blob/master/Day9/Titanic%20Dataset%20Exploration.ipynb) 
, [Univariate Pandas visualization](https://www.kaggle.com/residentmario/univariate-plotting-with-pandas)

### Day10: July 17, 2018 

**Today's Progress**: Completed videos on Principal component Analysis(PCA)

**Thoughts** PCA is mainly used to visualize high-dimentional data, to transform more number of features into fewer significant ones which helps other algorithms run better. Also PCA reduces noise by selecting only the top principal components. The main intension the PCA is to find the patterns in data which can Maximize varinace and minimize information loss.

**Link(s) to work**
[When to use PCA](https://www.youtube.com/watch?v=hJZHcmJBk1o)

### Day11: July 18, 2018 

**Today's Progress**: Completed videos on Random projection, Independent component analysis(ICA)

**Thoughts** I got the importantance of dimintinality reduction techniques, how Random projection is better than PCA when we have higher dimentions. I am exited about the application of ICA in audio seperation and its use in Health data, Time series data. 

**Link(s) to work**
[ICA](https://github.com/vpinnaka/100_Days_of_ML_Code/blob/master/Day11/IndependentComponentAnalysis/Independent%20Component%20Analysis%20Lab.ipynb)

### Day12: July 19, 2018 

**Today's Progress**: AWS Sagemaker demo

**Thoughts** Watched AWS innovative conferance, got some insights how AWS is providing machine learning services. AWS SageMaker is one of the kind end-to-end machine learning service that provide on the spot instance for training and deployes the model on a EC2 instance so that we can write a client to test the endpoint. Also found some intreasting projects with ML on AWS

**Link(s) to work**
[AWS SageMaker](https://github.com/awslabs/amazon-sagemaker-examples)
[Twitter Bot](https://github.com/aws-samples/aws-rekognition-workshop-twitter-bot)
[Hot Dog App](https://github.com/aws-samples/serverless-hotdog-detector)

### Day13: August 19, 2018 

**Today's Progress**: Microsoft Azure Machine Learning studio

**Thoughts** Created and deployed a car price prediction model with zero coding with azure machine learning studio. In my thoughts azure machine learning studio is more easire to use than AWS sagemaker both are of similar tools except in Sagemaker is competly based on codeing where as azure ML studion has drag and drop option also we can create notebooks similar to sagemaker. 
**Link(s) to work**
[Azure ML studio](https://studio.azureml.net/Home/ViewWorkspaceCached/4ab26ab7e57c4363910c2e2683a5f333#Workspaces/Experiments/Experiment/4ab26ab7e57c4363910c2e2683a5f333.f-id.146d29580ad340eda0dc4bf31cddcc9a/ViewExperiment)
[Siraj Ravel Video](https://www.youtube.com/watch?v=LQEyK4POowk)
