# Airbnb Prices during Coldplay Concerts 

## Table of contents
[1. Our Project](https://github.com/course-dprep/team-assignment-team-5#1-Our-Project)
- [Description of the research](https://github.com/course-dprep/team-assignment-team-5#1Description-of-the-research)
- [Research questions](https://github.com/course-dprep/team-assignment-team-5#Research-questions)
- [Conceptual model](https://github.com/course-dprep/team-assignment-team-5#Conceptual-model)

2. Method
- Data
- Variables
- Research method

3. Results and Conclusion

4. Repository
- Files
- Structure

## 1. Our Project
### Description of the research
In our research we study the price changes of Airbnb's in different cities in the period of a Coldplay concert. We will look at the prices a period before, the period of the concert, and the period after the concert to study the price differences caused by the Coldplay concerts. Furthermore, we will look at the influence of the type of listing, and the influence of the distance between an Airbnb and the place of the concert on the relationship of the concert on the price of the Airbnb.

Since the tour of Coldplay started in March 2022 and will continue till July 2023, we are not able to study all cities. However, results of our study can help other cities by predicting prices of Airbnb's. The cities we will study are Mexico City, Dallas, and Chicago. 

We will use data about the listings from Airbnb retrieved by "http://insideairbnb.com/get-the-data", and to find the concert dates we will use data from "http://songkick.com".

### Research questions

1. "To what extent do prices of Airbnb's differ during Coldplay concerts in the cities Dallas, Chicago, and Mexico City?"
2. "To what extent does the distance between an Airbnb and the place of the concert influence the relationship between the prices of an Airbnb during a Coldplay concert?"
3. "To what extent does the type of the room influence the relationship between the prices of an Airbnb during a Coldplay concert?

### Conceptual model

## 2. Method

We retrieved the data from http://insideairbnb.com/get-the-data. From there on we first merged for every city the two datasets: listings and reviews. Then, we cleaned the data by filtering out all unnecessary variables in the dataset and added a new variable consisting of the distance between the Airbnb listing and the place of the Coldplay concert. Furthermore, we created a new variable consisting of the data of the dates during the concerts and we filtered observations by one month before and one month after the concerts to reduce the dataset. We found the dates of the concerts via "http://songkick.com". On top of that, we filtered price outliers by removing prices above $9999.00. 

After cleaning and preparing the data, we started to perform the analysis. We have done a regression analysis to obtain the results. On top of that, we created plots to visualize the results.

## 4. Results and Conclusion

## 5. Repository

