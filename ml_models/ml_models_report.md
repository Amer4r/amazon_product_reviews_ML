---
noteId: "f1bcabd0292411ef979569cc5f3bf7c5"
tags: []

---

## Overview of the analysis
The purpose of this analysis is to implement and develop a model for Amazon Products Reviews. The model is to detemine the positive and negitive reviews for products and determine which products is likely to grow sales. Dataset was used from a live API called RapidAPI.

## Result 
- Targeted variable: 'sentiment' that represent positive 1 and negitive 0.

- Features: no_stop_sords_comment. comment was stipped of the stop word and then converted into numeric using CountVectorizer.

## Models
2 models were tested on the dataset RandomForestModel and SVC Model. both model were able to achieve model performance

## Summary nd feature enhancement
- RandomForestModel:
The model was not able to achieve high accuracy rate for prediction with score of 66.07%.
- SVC Model
This model has ahieved the highest accuracy with score of 62.50%

In summary, both models were bad due to the unbalanced data. the posistive reviews were way higher (2631) than the negitive reviews with only 248 (during building model) which caused the model to get a great result for predicting positive review and doing really bad for the negitive.
Gathering more reviews to balance the data would the best option to enhance the models.