To do this project, I have used the Github web API as https://api.guthub.com.
The queries used to fetch data were : 
1. https://api.github.com/search/repositories?q=java
2. https://api.github.com/search/repositories?q=javascript

The data returend was in JSON format. This was converted into a dataframe.
The total number of repositories for each language i.e. Java and Javascript was calculated and then a dataframe was created with
language as 1st column and their numbers in 2nd column.

The dataframe was then plotted using ggplot2 and the results were then analysed.

