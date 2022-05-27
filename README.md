# Self Assessment

The majority of the time I was a worked in python to create the models for the group project. I also helped the team members tie their work to mine. 

# Teamwork Assessment

Overall the team did a great job coming together and getting the work done.

# Summary

For this project we aim to assess wine quality, and whether it is possible to classify a wine based on its chemical properties. 
# Conclusion

## **Question 1**:
Is a "Good" wine able to be predicted via the analysis of a wine's physicochemical properties? 

- Moderately so, an algorithm can predict a good wine.
  - Logistic Regression was able to output an accuracy score of 71%
  - Random Forest scored an F1 of 69%
    - Recall: 69%
    - Precision: 72%

## **Question 2**:
What physicochemical features are most responsible for determining wine quality?

- Based on Random Forest feature importance rankings, the following three provided the most value:
  - Alcohol (0.17)
  - Volatile Acidity (0.11)
  - Density (.11)

## **Question 3**: 
Can a 'good' wine be predicted using a chemical analysis agnostic of wine type (red or white)?

- Yes - interestingly, wine type was the least important feature by a large amount.
