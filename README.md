# Clustering-College-Majors-in-Python
* This data draws on a dataset from the data journalism website fivethirtyeight. The data includes an exhaustive list of college majors, associated demographic data, and their economic outcomes, e.g., income, employment, etc. While a few different datasets were available, this project looks at recent BA/BS graduates to get an up-to-date view of current economic outcomes.
* I begin this analysis by using several methods to find patterns in the data, including correlations, visualizations, and multiple linear regressions. To better conduct this analysis, I construct several new variables, including share of graduates. For example, `SharePT` was constructed by taking the number of graduates in part-time work as a share of the total number of graduates.
* Then, I use two algorithms to build clusters of majors, using loops with various validation methods to find the optimal number of clusters. The first algorithm is most successful, K-Means clustering. With k = 4, clusters were generating that included all individual majors based on 5 measures of income and employment.
