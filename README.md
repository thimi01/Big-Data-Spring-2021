# Big-Data-Spring-2021
www.politifact.com website data was scrapped to create a data frame that contain the following inforamtion.
Every line represents a different political statement that politifact has put under its microscope. The tab-separated features are the following:
1. Politifact Rating
2. Statement
3. Who made the statement
4. when the statement was made
5. where the statement was made
6. '|'-separated subjects of the statement

Put the data into a list named **statements**. 
- Every element of the list should be a list with the 6 features mentioned above. 
- The 6th element of the list of features should be a list containing the subjects that the corresponding statement is about. 

Use the data to find all possible ratings that politifact might assign to a statement. In other words, all possible values that the first attribute can take. Store them into a set with name **ratings** and print the set.
