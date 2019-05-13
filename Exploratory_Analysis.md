# cebd1120_team_project
CEBD 1260 - Spring 2019 - Team Project

| Name | Date |
|:-------|:---------------|
|Ricardo Rocha| May 11, 2019|
|Frank So| 
 

## Explain the dataset

We chose to analyze the Black Friday dataset hosted in the Kaggle competition available [here](https://www.kaggle.com/mehdidag/black-friday/kernels)

The following descriptions are given by Kaggle:

“The dataset is a sample of the transactions made in the store that wants to know better the customer purchase behavior against different products. Specifically, it is a regression problem where they are trying to predict the dependent variable (the amount of purchase) with the help of the information contained in the other variables.”

“Classification problem can also be settled in this dataset since several variables are categorical”.

"This dataset is also particularly convenient for clustering and maybe find different clusters of consumers within it.”


### Exploratory Analysis 1 - Demographic Analysis

Our demographic data analysis for the Black Friday dataset considers the following customers' information: gender, age, occupation, the city where they bought products, how many years they have lived in the city and their marital status.

We will analyze each feature separately according to Figure 1 below:

![Exploratory_Demograph_Analysis](./figures/Exploratory_Demograph_Analysis.png)

As demonstrated in the first count plot regarding Gender x Purchases, more than 75% of the transactions were made by men. While women were responsible for less than 25%.
The second count plot (regarding Age x Purchases) shows that customers between 26 and 35 years of age are the primary buyers of the retail store (40% of the transactions), while teenagers, up to 17 years of age, make less purchases (3% of the transactions).
The third count plot (Occupation x Purchases) shows that the customers who make more purchases have 4, 0, 7, 17 and 20 occupations in life.
The fourth count plot (City_Category x Purchases) shows the majority of transactions are concentrated in city B for the retail store. But, this doesn't necessarily mean that the greatest purchase amounts are made there.
The fifth count plot (Total of years living in the city x Purchases) shows that the main clients for the retail store usually buy more after having lived in the city for one year and before completing two years or more.
The sixth count plot (Marital status x Purchases) shows that single customers are the main buyers in the retail store considering all the transactions.


### Exploratory Analysis 2 - Business Analysis

As there is no information about the types of occupations and cities, we could only consider marketing strategies to offer promotions for Black Friday for the categories presented. From the retailers' perspective, one question that we could try to answer with the available information is: "Which city and professions are potential targets to receive Black Friday promotions and should have more products in stock?"

Exploring our dataset information, we plot the chart in Figure 2 as follows:

![Exploratory_Demograph_Analysis](./figures/Exploratory_Demograph_Analysis.png)

This figure accounts for the occupation of our customers across different cities in terms of purchase. Let's first address the spike for Occupation 8 in City A, it showed in the earlier count plot that occupation 8 made up only a tiny number of purchases, the vertical std bar helps explain this spike, probably by a few large transactions. However, we can see that apart from occupations 8 and 9, the graph shows that purchases are highest in City C.  Therefore, we can make assumptions about the purchasing power of customers in City C. Answering the question, City C and the clients in occupations 5, 11 and 17 would be our potential targets because they have bought more than 10,000 dollars in the store at this location accordingly to our diagnostic analysis of the dataset.
