# Sparkify - Data Science Nanodegree Capstone Project
## Libraries used
* pyspark
## Motivation for the project
Acquiring new customers is typically far more cost intensive than retaining existing customers. Especially for fast growing businesses with a strong focus on acquiring new customers it is crutial to put equal effort into retaining the existing customers ([Forbes][1]).
To prevent customers to turn their back to your company, the first critical step is to identify customers who have the potential to churn. Having identified potential churn customers one can take action to retain the customers. 

Today's online businesses have a vast data pool to use to predict churn. To be able to predict churn one needs adequate knowledge about adequate machine learning models in order to make the prediction as well as adequate knowledge about big data tools to handle the tremendous amount of data in these businesses. 

In my capstone project I therefore want to use a big data dataset to predict churn. I am using the Sparkify-dataset, a dataset of a hypothetical music streaming service such as Spotify, to early-detect churn.
## Files in the repository
| Filename                 | Explanation                                                                                                |
| ------------------------ |:-----------------------------------------------------------------------------------------------------------|
| README.md                | contains technical informations and elaborations on the project.                                           |
| Sparkify_Workspace.ipynb | contains project code for most of the analysis except for grid search and cross validation.                |
| Sparkify_Workspace.html  | contains project code for most of the analysis, except for grid search and cross validation as .html.      |
| Sparkify_AWS.ipynb       | contains project code for for grid search and cross validation.                                            |
| Sparkify_AWS.html        | contains project code for for grid search and cross validation as.html.                                    |

## Summary of the analysis results
The project defined a churn metric, features and a model to predict churn based on features. The final model was a random forest model with a maximum depth of 8. The model had a f1-score of 0.86695 and an accuracy of 0.88235. The good prediction results are a solid foundation for installing automatic measures to significantly reduce user churn as a next step. 

For a more detailed elaboration on the project please refer to my [blogpost][2] on the topic.

[1]: https://www.forbes.com/sites/larrymyler/2016/06/08/acquiring-new-customers-is-important-but-retaining-them-accelerates-profitable-growth/#4314b907667
[2]: https://medium.com/@eichler_wolfgang/how-to-predict-churn-in-an-online-streaming-business-2a1ddd5461e5
