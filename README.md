# data-science-kmeans
Project to give recommendation using given data, to choose which country need the relief funds the most. 
I choose using Kmeans model to clustering the data to help narrow down the candidate countries that will be given relief funds

First step is validating the data, is there any null data, using method .info() In this case there is no null data so you can next to the next step.
Then the next step is check the outliers and replace the outlier data with IQR method.
Third Step check you can start analyzing the data, either its univariate, bivariate, or multivariate data.
After you done with analyzing data you can start clustering the data, in this case i use KMeans from skicit learn library.
To choose how many cluster, i use elbow method.
Anda after get the clustering, then i can choose which cluster that will need the help the most.
After get the cluster then i compare to the original data (before replace the data with IQR)
And after i compare the data, i can easily choose which country that need the relief funds the most.
