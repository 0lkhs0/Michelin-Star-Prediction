# SC1015-mini-project
SC1015 Mini Project on Michelin Star Restaurants

### Overview
3 Notebooks

1. Data Preparation and Cleaning - Cleaning and preparing the necessary data
2. EDA - Exploratory Data Analysis 
3. ML - Machine Learning 

2 CSV files
1. michelin_my_maps - initial data set from kaggle
2. CLEANED - cleaned and prepped data set

1 Folder for pictures
1. Picture of Bar Plot of cuisines and number of michelin stars
2. Picture of Bar Plot of countries and number of michelin stars
3. Picture of the confusion matrix from Decision Tree Classification
4. Picture of the confusion matrix from Support Vector Classification


### Problem Definition
The Michelin Star to most restaurant owners is the proof of success.
Is there any factors that a restaurant can adopt increase their chances of obtaining a Michelin Star? 
As a 1 Michelin Star restaurant is there any factors to adopt to rise up in stars?
We want to be able to help restaurant owners reach the pinnacle of running a restaurant. 
Which is why we are analysing the current michelin star restaurants and finding factors that will increase the chances of restaurants obtaining a michelin star or getting more michelin stars.
We will use various factors to predict if a restaurant has one/two/three michelin stars and what sets them apart from other restaurants.


### Contributors
Sean Lim - Data Cleaning and Preparation, Exploratory Data Analysis, Slides, Video, GitHub repository
Jeong Dohyun - Data Cleaning and Preparation, Machine Learning

### Models Used
1. Decision Tree Classification
2. Support Vector Classification

### Conclusion
- There are relatively high accuracy ~85% in predicting and low false postive rates using the Support Vector Classification.

- From our uni-variate analysis on countries, cuisines, there is a higher chance of getting a michelin star if the restaurant is in France, focusing on Modern cuisines. The prices should be set around USD143.78.

- From our bi-variate analysis on countries with award, cuisine with award and price with award, we concluded that generally stationing the restaurant in France will have a higher chance of getting a michelin star.

- Focusing on modern cuisines will have a higher chance of getting a michelin star, however, switching to a Creative cuisine will warrant higher chances of getting two and three michelin stars.

- The price of dining generally increases as the number of michelin star increases.



### What we learnt from this project

Collaborating using GitHub
Pandas functions
Matplotlib functions
How different classification models work and why some work better for our dataset.

### Acknowledgments
Special thanks to our instructors and TA Ju Chuang for teaching us this semster.

### References
https://www.kaggle.com/datasets/ngshiheng/michelin-guide-restaurants-2021
