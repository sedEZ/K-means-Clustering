# K-means-Clustering
Implment K-means clustering by my own , and compare the performance to sklearn.cluster.KMeans().

I write it as an object that you can easily use it.

## Useage
Open k_means.ipynb with jupyter notebook.

numpy,pandas,sklearn are required.

## Settings
-Number of clusterings(K) : Max value of labels + 1 -> Range from [0,np.amax(data_y)]
 
-Number of dimentions(DIM) : Number of features

-Method of initializing the K centroids: Randomly picked K points of data in data_x as centroids

## Datasets used in this code
-Abalone dataset  

-sklearn iris dataset

## Data Preprocessing
 I need your help for another 3 settings:
 
 - data_x : The table consists of all the feature that to be train.
            It's format should be "pandas.DataFrame".   
         
 - data_y : The table consists of all the feature that to be train.
            It's format should be "numpy.array".        
         
 - Simulate_time : The # of times you want to run for. 
 
 Note: Sorry but only numbers available:(

## Performance
print(result.acc) for checking average accuracy!

## Compate with sklearn.cluster.k_means_sklearn
At the end of the code, I run sklearn.cluster.KMeans and checks its accuracy.

The functions used on it are the same with functions used in class "our_k_means".

(To postprocess the clustering, like calculate mass & relabel)

## Reference

http://edisonx.pixnet.net/blog/post/84122954-%5Bai%5D-c-%E8%AA%9E%E8%A8%80-kmean-%E6%BC%94%E7%AE%97%E6%B3%95
