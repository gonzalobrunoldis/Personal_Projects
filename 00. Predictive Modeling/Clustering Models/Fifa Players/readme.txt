# Fifa Players Supervised Clustering 

## Quick Intro

This was my first Clustering project, guided by notebooks uploaded on Kaggle. Even though clustering is a technique that is usually used for unsupervised learning projects to detect hidden patterns in data, I decided that, being my first clustering project, it made sense using it in a supervised learning scenario to be able to see if the clustering had performed up to standard.

## Problem statement

In this analysis, we used data of the players from the game Fifa 2020, and tried to see if the players that play in the same positions had similar physical attributes. After performing some data preprocessing techniques, we used a clustering model to see if we could see the similarities visually. 
 
## Approach

The dataset contained several pieces of information of the player stats: Dribbling, shooting, defending, running speed, stamina, goalkeeping, age, market value, etc. On the same page, it also had thousand of players (observations).

First, we chose the top 65 players with the highest ratings for visualization's sake. Afterwards, as we had a dataset with high dimensionality, we applied PCA to reduce the dimensionality of the data, and see if we have some features that are more relevant than others. After that, we moved forward to the clustering algorithm.

The clustering algorithms applied were: Kmeans and DBSCAN. As I pointed out at the introduction, the players of different positions were used as hue, to be able to tell how they were distributed on the graph.  

## PCA quick overview


## Result

The players picked were quite accurately clustered by position, which means that they had some distinguishable attributes that allowed our clustering algorithm to perform astoundingly good. 

Thank you for reading!

### Contact Me

| Contact Method |  |
| --- | --- |
| Professional Email | gonzalobrunoldis@gmail.com |
| LinkedIn | https://www.linkedin.com/in/gonzalobrunoldi/ |
