# Data Analytics/Science Portfolio by Jeremy Jhee

This portfolio is a compilation of notebooks which I created for data analysis or for exploration of machine learning algorithms. A separate category is for separate projects.


## Kaggle kernels.

### Avito Demand Prediction Challenge

Avito challenge is about predicting demand for an online advertisement based on its full description (title, description, images, etc.), its context (geographically where it was posted, similar ads already posted) and historical demand for similar ads in similar contexts. The competition is interesting due to many types of data in it which allows to build various models. Here is my [kernel](https://www.kaggle.com/artgor/eda-features-engineering-and-lightgbm) with EDA, creating features and building models.

### Home Credit Default Risk

Home Credit Bank offers a challenge of credit scoring. There is a lot of data about applicants and their previous behavior. Here is my [kernel](https://www.kaggle.com/artgor/eda-in-progress).

### Movie Review Sentiment Analysis

Some time ago Kaggle has launched several "remakes" of old competitions. It means that datasets are the same, but now we are offered an opportunity to simply explore the data and create kernels with new methods. One of these competitions is sentiment analysis of Rotten Tomatoes dataset with 5 classes (negative, somewhat negative, neutral, somewhat positive, positive). I have created a [kernel](https://www.kaggle.com/artgor/movie-review-sentiment-analysis-eda-and-models/notebook) with EDA and modern NN architecture: LSTM-CNN. Currently this kernel shows the 5th result of leaderboard.

### Two Sigma: Using News to Predict Stock Movements

In this competition Reuters provide unique data, which can't be obtained outside of this competition. We can see a 10 years worth of news and market data on many companies. This competition is kernel-only, which means that everyone has the same amount of computational power for this competition. In my [kernel](https://www.kaggle.com/artgor/eda-feature-engineering-and-everything) I have analysed the data and showed trends of market data.

### Santander Value Prediction Challenge

In this competition we got an anonymized dataset, later it was found that it had a certain structure. In my [kernel](https://www.kaggle.com/artgor/satander-eda-nn-features-lgb) I tried to analyze the data and created new features using NN model.

### Google Analytics Customer Revenue Prediction

RStudio hosted this competition to prove that machine learning algorithms can impact business and help marketing. In my [kernel](https://www.kaggle.com/artgor/eda-on-basic-data-and-lgb-in-progress) I did an extensive EDA and build an interesting LGB model.

## Classification problems.

### Bank card activations

[Github](https://github.com/Erlemar/Erlemar.github.io/blob/master/Notebooks/Card_activation.ipynb) [nbviewer](http://nbviewer.jupyter.org/github/Erlemar/Erlemar.github.io/blob/master/Notebooks/Card_activation.ipynb)

Banks strive to increase the efficiency of their contacts with customers. One of the areas which require this is offering new products to existing clients (cross-selling). Instead of offering new products to all clients, it is a good idea to predict the probability of a positive response. Then the offers could be sent to those clients, for whom the probability of response is higher than some threshold value.
In this notebook I try to solve this problem.

## Regression problems.

### House Prices: Advanced Regression Techniques

[Github](https://github.com/Erlemar/Erlemar.github.io/blob/master/Notebooks/House_Prices.ipynb) [nbviewer](http://nbviewer.jupyter.org/github/Erlemar/Erlemar.github.io/blob/master/Notebooks/House_Prices.ipynb)

House Prices: Advanced Regression Techniques is a knowledge competition on Kaggle. This is a regression problem: based on information about houses we predict their prices. General description and data are available on [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).
The dataset has a lot of features and many missing values. This gives interesting possibilities for feature transformation and data visualization.

### Loan Prediction

[Github](https://github.com/Erlemar/Erlemar.github.io/blob/master/Notebooks/Loan_Prediction.ipynb) [nbviewer](http://nbviewer.jupyter.org/github/Erlemar/Erlemar.github.io/blob/master/Notebooks/Loan_Prediction.ipynb)

Loan Prediction is a knowledge and learning hackathon on Analyticsvidhya. Dream Housing Finance company deals in home loans. Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. Based on customer's information we predict whether they should receive a loan or not. General description and data are available on [Analyticsvidhya](https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/).


## Data exploration and analysis

### Telematic data

[Github](https://github.com/Erlemar/Erlemar.github.io/blob/master/Notebooks/Devices_analysis.ipynb) [nbviewer](http://nbviewer.jupyter.org/github/Erlemar/Erlemar.github.io/blob/master/Notebooks/Devices_analysis.ipynb)

I have a dataset with telematic information about 10 cars driving during one day. I visualise data, search for insights and analyse the behavior of each driver. I can't share the data, but here is the notebook. I want to notice that folium map can't be rendered by native github, but nbviewer.jupyter can do it.
