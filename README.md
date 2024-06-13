## Amazon Product Review - ML

## Overview
The purpose of this analysis is to develop and implement a model on Amazon Products Review to have a better understanding of customer’s sentiments on different electronic devices.
Use the model to determine the viability of the product (positive, neutral, negative) and which products are likely to increase sales.

Our Analysis also include analysing different factors such as Product Price, Product Star Rating, Number of Product Ratings, Sales Volume, Total Revenue.
We also Built a dashboard for better understanding of our data: https://public.tableau.com/app/profile/charu.arora1569/viz/Book2AmazonDashboard-2/Dashboard1

Dataset was used from a live API called RapidAPI.

![image](https://github.com/Amer4r/amazon_product_reviews_ML/assets/149630812/07404cee-57f1-4a14-87f7-b0a25c2c7488)

## Getting Started
- Clone The repository using:  Amer4r/amazon_product_reviews_ML (github.com)

- Install all the packages withing requirements.txt
```bash
pip install -r requirements.txt
```

### Prerequisites
-  Installation - Python 3.x
- Hosting/Cloud - Amazon Web Services

## Models
2 models were tested on the dataset RandomForestModel and SVC Model. both model were able to achieve model performance

## Result 
- Targeted variable: 'sentiment' that represent positive 1 and negitive 0.

- Features: no_stop_sords_comment. comment was stipped of the stop word and then converted into numeric using CountVectorizer.

## Summary and feature enhancement
- RandomForestModel:
The model was not able to achieve high accuracy rate for prediction with score of 66.07%.
- SVC Model
This model has ahieved the highest accuracy with score of 62.50%

In summary, both models were bad due to the unbalanced data. the posistive reviews were way higher (2631) than the negitive reviews with only 248 (during building model) which caused the model to get a great result for predicting positive review and doing really bad for the negitive.
Gathering more reviews to balance the data would the best option to enhance the models.


### References
Used to view different types of markers to use for visualizations
https://matplotlib.org/stable/api/markers_api.html

Used to install Seaborn
https://seaborn.pydata.org/

Used as a reference to see the different types of visualization that can be made with Seaborn
https://seaborn.pydata.org/examples/index.html

Used as a reference to see the different types of visualization that can be made with Matplotlib
https://matplotlib.org/stable/plot_types/index.html

Used to review how a paired t-test works as well as code sample
https://www.statisticssolutions.com/free-resources/directory-of-statistical-analyses/paired-sample-t-test/

Used to save figures
https://www.atlassian.com/data/notebook/how-to-save-a-plot-to-a-file-using-matplotlib

Used to assist with coding issues when problems came up
chatgpt.com

### Our Team
- Amer Banaweer
- Charu Arora
- Edward Chac

