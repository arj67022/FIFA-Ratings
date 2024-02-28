# Overview

This work was completed as a final project for CIS 545: Big Data Analytics at the University of Pennsylvania. The goal of this project was to predict FIFA ratings for individual soccer players using actual player and team data.

 The first part of the project involved data acquisition. Raw player and team data were scraped from a soccer database and datasets with player and team FIFA ratings for five different versions of the FIFA soccer video game were acquired from public repositories. The datasets were cleaned and processed using a variety of Pandas dataframe operations. 
 
 The next phase of the project involved exploratory data analysis. A variety of plots and visualizations were used to investigate trends in the data, extract relevant features, and engineer new features. 
 
 The final portion of the project involved modeling the data. Player and match statistics were used to predict FIFA ratings. A variety of regression techniques were used and then feature importance was analyzed. Based on these initial findings the models were further improved using a variety of techniques including reducing the feature set via PCA and data stratification. Ultimately, the models created were able to predict the FIFA ratings of players with accuracies of >95%. 
 
Although the model accuracies were very high, it is suspected that there were many correlations between the features used in most models. To extend on this project, I would love to further explore and understand these correlations to improve the model.