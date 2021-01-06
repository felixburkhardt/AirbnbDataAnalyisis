
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installationguide <a name="installation"></a>

The code should run with no issues using Python versions 3.*. The following libraries are necessary:

1. numpy
2. pandas
3. matplotlib.pyplot
4. from vaderSentiment.vaderSentiment import SentimentIntensityAnalyzer
5. from collections import Counter
6. from sklearn.linear_model import LinearRegression
7. from sklearn.model_selection import train_test_split
8. from sklearn.metrics import r2_score, mean_squared_error

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using Airbnb data from 2017 to better understand:

Pricing:
- What is the cheapest time to travel? How do prices fluctuate? When are prices above or below average?
- What properties are most expensive?
- Do prices differ by neighbourhood? If so, how much?
- What is the busiest time to visit Seattle?

Listings:
- Is there a connection between reviews and neighbourhood?
- Which neighbourhood has the most offers?
- How long is the host response time?
- What property types are offered?
- Is there a general upward trend of both new Airbnb listings and total Airbnb visitors to Seattle?
- Can we predict prices based on the given data?


General Business Questions:
- Which neighbourhood is the most attractive one?
- What time is best to travel to Seattle if you want to make a bargain (prices and availiability of properties)?
- What property is the cheapest to live in and where do I get the biggest location for little money?

The data was downloaded from: https://www.kaggle.com/airbnb/seattle/data


## File Descriptions <a name="files"></a>

The following Airbnb activity is included in this Seattle dataset:

Listings, including full descriptions and average review score
Reviews, including unique id for each reviewer and detailed comments
Calendar, including listing id and the price and availability for that day

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here]().

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit to AirBnB and Kaggle for hosting the data
Code for satisfaction Score was taken from:
https://github.com/cjhutto/vaderSentiment
https://medium.com/analytics-vidhya/simplifying-social-media-sentiment-analysis-using-vader-in-python-f9e6ec6fc52f
Evaluation of Regression Model taken from:
https://stackoverflow.com/questions/26951880/scikit-learn-linear-regression-how-to-get-coefficients-respective-features
