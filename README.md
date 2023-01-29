# Python Correlation with Movies Data

Python project for finding correlations between variables. <br>
The findings are based on the correlation between gross revenue of movies and other variables such as the budget of the movies and the votes received by them.
The dataset available on [link](https://www.kaggle.com/datasets/danielgrijalvas/movies).

### Built with

* Jupyter notebook

### Libraries used 
* Pandas
* Matplotlib
* Seaborn

### Highlights
* Scatter Plot
* Regression Plot
* Heatmap
* Python regex
* Python Categorical data


### What is being done?
1)	Preliminary tasks   <br>
1.1.	Importing libraries <br>
1.2.	Create a dataframe movies from CSV <br>
1.3.	Checking for missing data <br>
1.4.	Checking the datatypes of the columns <br>
1.5.	Altering the datatypes of few columns <br>
1.6.	Adding new column for correctness and data consistency <br>
1.7.	Dropping duplicate rows  <br>
2)	Task: Finding if there is a correlation in two particular columns: budget and gross <br>
2.1	   Scatterplot of budget and gross <br>
2.2	   Regression plot of budget and gross <br>
2.3	   Finding pairwise correlation of numeric columns <br>
2.4	   Heatmap of the correlation values <br>
3)	Task: Trying to find general correlation among different columns of the data as a whole <br>
3.1	Representing the non-numeric values into numeric values using categorical datatype <br>
3.2	 Finding pairwise correlation of numeric columns <br>
3.3	 Heatmap of the correlation values <br>
3.4	 Displaying the correlation values linearly <br>
3.5	 Sorting the linearly displayed correlation values <br>
3.6	 Finding the pairs with higher correlation <br>
4)	Observation and Conclusion <br>
4.1	There is a high correlation in budget and gross. This says that as the high budget movies are observed to have achieved high gross revenues. <br>
4.2	Also, there is a fairly high correlation in votes and gross as well.  So, this also says that the movies with high gross revenues have received large number of votes. <br>

