# SOC-2022-Personality-Detection

Assignment 1 .txt, Assignment 2 .txt and assignment 3 .pdf files are the week 1, week 2 and week 3 assignments respectively.

Assignment-1,2,3 zip files are the solutions to assignment 1,2 and 3.

The text file Personalities conatains the list of questions in the questionnaire.

The text file test-personality-detection contains the sample response which is classified as per the different methods explored in the main submission.

The python file Personality Detection is the final submission file.


# Week-1

I learnt about the Python libraries like Numpy, Scipy and Pandas. I wrote some small codes to understand the various methods. Since the libraries are very vast with a large number of methods available, so it is not possible to remember all of them. So I keep revising time to time and consult the resources in case of any doubt. I have also done the week-1 assignment.
# Week-2

I learnt about the concept of linear regression in machine learning and how to obtain a solution using gradient descent. I also solved the week-2 assignment and got clarity about the concept.

# Week-3
I learnt about the K-means algorithm and how to implement it. I also understood its drawbacks and that it may not provide the required grouping of data always but it is useful in many cases to group the data into clusters.

# Week-1 ()
The assignment file contains some questions regarding application of python libraries like numpy and pandas.

The solution file contains the solutions to the problems which we obtained.

# Week-2 ()
The assignnment file contains a problem where linear regression is to be used to come up with a model which can predict the number of cases of a disease on a future day given the numbers over several days. Although linear regression is not suitable for all kinds of data but some tricks can be used, like plotting the logarithm of nnumber of cases versus days, if the data varies exponentially. So the program does this and the best fit line is plotted using linear regression and based on this the predictions are made.

# Week-3 ()
In the assignment we have to use k-means clustering to group the data points given. This is a centroid based clustering where the centroids corresponding to each cluster are randomly initialised on the plane where the data points are plotted. Then distances of all the points from each centroid are calculated. Each point is assigned to the cluster corresponding to that centroid from which its distance is minimum. The centroid locations are updated by taking the centroid of all the points assigned to the corresponding cluster. The process continues until the centroid locations become constant , that is the clusters are well defined. There is no clear way of deciding the number of clusters beforehandwithout looking at the data itself. The clustering has been done for the datav given. But sometimes if the clusters are based on some patterns then k-means clustering may not yield the desired grouping as it is only based on the locations of the various points and not on some patterns in data which we may be wanting.

# Week-4 ()
This is the final implementation of the project. There is a questionnaire with 10 questions each related to 5 different personality aspects: openness, conscientiousness, extroversion, agreableness and neuroticism. Answers have to range from 1-5, where 1 means strongly disagree, 3 means neutral and 5 means strongly agree. Over 1 million responses are collected. Task is to come up withm a model which can classify people based on their responses, into various groups. Since no training examples are available, we have to go for unsupervised learning. In this project, k-means algorithm has been used. So first the data is explored and null responses are dropped. Then sklearn library is used to create a k means clustering model and group the data. 5 clusters have been chosen as an optimal number. Then a visualisation of the mean of the response values corresponding to each personality is done to see the characteristics of each cluster. Finally I have filled in my responses to the questions and determined my personality based on the model. Another scheme of classifying the personality of a person has been explored. Since there are no correct or incorrect answers for classification, any reasonable scheme works. In my scheme, I am calculating the score of a person from 1-5 for each of the 5 aspects. It is based on the weighted average of the responses to the 10 questions for each aspects. I am considering the weights to be proportional to the variance of the responses to each question. The assumption is that if a question shows more variation in responses, it has more bearing on the personality and hence a higher weight. This assumption is reasonable as a huge number of responses are available so all types of personalities may be assumed to be represented. I have calculated the scores this way and it is not much different from the normal average of responses, indicating that all questions have similar variances.

