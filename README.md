
#  Titanic data analysis to predict whether someone survived or did not survive.
## The best prediction score is 0.85 (SVC,RBF kernel)
1.	Load the data from the csv file - https://github.com/Ifaats/HW4/blob/master/titanic.csv
2.	Clean the data:
> * Drop Na, and verify no Na,verify data size after droping Na
> * Drop irrelevant features that will not help analyze the data (ticket, cabin, home.dest, body, name, boat)
4.	Play with data
> * Age mean
> * Age histogram
5.	Graphs to check assumptions and correlations
> * Check correlation of survival by sex (graph shows that female has better chance to survive)
> * Check correlation between the survival and the age variable.
> * Check correlation between the ticket fare and the survival
> * Scatter graph of the age, the ticket fare and the survival (Indeed who ever paid more had better chance to survive)
> * Correlation of parch and the survival
> * Correlation of pclass and the survival
> * Is fare ticket indicator for survival? (graph indeed shows that there were more survivals in 1st class)
6.	Prediction models and accuracy
> * Create and fit a nearest-neighbor classifier - KNN, classifier 3 (root of number of features)
> * SVC  - 3 different kernels - linear, Poly and RBF
7. The best prediction score is 0.85 (SVC,RBF kernel)
