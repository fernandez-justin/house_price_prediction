# House Price Prediction

**Authors**: Justin Fernandez

## Overview
This project seeks to answer the question of what characteristics of a house are indicators as to if the price will go up and down. Identifying those key characteristics and how they affect the price of house can be then used to predict the exact price a house will be sold for. The data used is a list of house sales in Kings County CA. with information on each individual house and then the price it was sold for. The methods used in this research will focus on exporation of the data, feature engineering, statistical testing, feature seleciton, and model interpretation. The results of this research show...


## Business Problem



Microsoft wants to join in on the other big companies starting to make video content like Netflix, Hulu, and many others. Without much experience in the field, they need our help with getting an insight into what kind of content they should be creating to be successful. The question we seek to answer are:

1. What genre of movie is the most successful domestically / worldwide?
2. Who should be hired to give the highest chance of a highly rated movie?
3. What genre of movies are people most excited about voting on ?
4. Are movie ratings affected by movie runtimes ?


## Data
The data used in this project comes straing from the sales of these houses. The location for all these houses are Kings County in California. The data set provides information on these houses such as square footage, number of stories, condition, number of bedrooms and bathrooms, and 15 more characterics of the house at time of sale.


## Methods
This project focuses on identifying and engineering features to be used in a linear regression model. This will allow us to identify how each feautre of the house will impact the price of the house when it is to be sold. 
An initial exploratory data analysis was completed in order to determine what was being represented with each original feature. Feature engineering was then completed to possibly create feautres that provide more information then was originaly able to be derived. Statistical tests were then performed in order to answer questions about each feature and its affect to the price. Feature selection was then performed in order to identify the features that had the most influence on the price of the home. Finally the model was interpreted in order to identify the outcomes of the entire process.

## Results

Following are the analysis results by question:

#### Question 1 (a)
The results of this inquiry shows that the American populations favorite genres of movies are adventure, animated, sci-fi, fantasy, action, and family.
![Box Office Domestic](./images/Genre_vs_boxoffice.png)


## Conclusions

In conclusion, our analysis leads to the following recommendations to Microsoft:

1. Movies in the genres of adventure, animated, sci-fi, fantasy, action, and family have grossed the highest at the American box office. In terms of earnings these are the genres that Microsoft should explore.
2. Microsoft should hire movie crew members who have historically worked on successful movies.
3. Exploring movies in the drama, thriller, horror and documentary genre may also be fruitful for Microsoft when deciding on what kinds of movie to make
4. When movie viewers rate movies, the length of the movie does not affect whether they vote on a movie or not and how well they vote. Microsoft should not be too concerned about the length of a movie being a putoff.


## Limitations and Next Steps

Limitations of this dataset was that it was constrained to movies in the the four source sites, that are very similar in what they offer. The dataset also was much lacking with missing values and/or null values for several observations. Further steps must be taken to seek out better data that assess the success of a movie.
To be with the times of our current situation, the next steps would be to look at data from movies released in the last year to assess how the COVID pandemic affected the movie industry. Getting a dataset with less null values to improve the findings that we have made with the current dataset


## For More Information

Please review our full analysis in [our Jupyter Notebook](./movie-data-analysis.ipynb) or our [presentation](./Movie-Data-Analysis-Presentation.pdf).

For any additional questions, please contact **Justin Fernandez justin.miguel.fernandez@gmail.com**

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── movie-data-analysis.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── Movie-Data-Analysis-Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
