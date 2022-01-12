# Facebook_Friend_Recommendation_using_graph_mining

### PROBLEM STATEMENT:
This project is based on social media link prediction whether two users are going to be friend in future or not.

### DATA OVERVIEW

Taken data from facebook's recruting challenge on kaggle https://www.kaggle.com/c/FacebookRecruiting data contains two columns source and destination eac edge in graph

Data columns (total 2 columns):

source_node int64

destination_node int64

### MAPPING THE PROBLEM INTO SUPERVISED LEARNING PROBLEM: 
Generated training samples of good and bad links from given directed graph and for each link got some features like no of followers, is he followed back, page rank, katz score, adar index, some svd fetures of adj matrix, some weight features etc. and trained ml model based on these features to predict link.

### BUSINESS OBJECTIVE AND CONSTRAINTS:
1.No low-latency requirement.
2.Probability of prediction is useful to recommend Highest probability links.

### PERFORMANCE METRIC FOR SUPERVISED LEARNING:
Both precision and recall is important so F1 score is good choice Confusion matrix.
