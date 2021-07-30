# Facebook-Friend-recommendation-using-Graph-Mining

# DATA:
   The above project describes ,how to predict missing links to recommend users,given a social graph.
    The above problem statement is  Facebook Prediction Challenge hosted by Facebook on Kaggle in 2015.
# LINK TO THE DATA :  https://www.kaggle.com/c/FacebookRecruiting

# EXPLORATORY DATA ANALYSIS AND SPLITTING DATA:

     -> As this is a graph based problem ,I used networkx library for manipulation of graphs.
     ->In this part of the project ,I analysed the data using libraries like pandas,numpy,matplotlib,seaborn.
     ->Analysed the no.of followers for each person and the number of persons they follow ,where i ended concluding very few no of people have large followers.(used concept of            indegree and outdegree for the calculation ).
     ->As the data given ,only depicts the case where there is an edge between two persons,it becomes imbalanced.So I formed edges form the given data where they dont have                connection between them to make it balanced(to perform classification).
     ->Then divided the data into train and test and now are ready for featurization and modelling.
       
      






