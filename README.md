# Finding-Donors-for-a-CharityML
In this project, you will apply supervised learning techniques and an analytical mind on data collected for the U.S. census to help CharityML (a fictitious charity organization) identify people most likely to donate to their cause.

You will first explore the data to learn how the census data is recorded. Next, you will apply a series of transformations and preprocessing techniques to manipulate the data into a workable format. You will then evaluate several supervised learners of your choice on the data, and consider which is best suited for the solution. Afterwards, you will optimize the model you've selected and present it as your solution to CharityML. Finally, you will explore the chosen model and its predictions under the hood, to see just how well it's performing when considering the data it's given.

This project is designed to get you acquainted with the many supervised learning algorithms available in sklearn, and to also provide for a method of evaluating just how each model works and performs on a certain type of data. It is important in machine learning to understand exactly when and where a certain algorithm should be used, and when one should be avoided.

Things you will learn by completing this project:

  1.How to identify when preprocessing is needed, and how to apply it.
  
  2.How to establish a benchmark for a solution to the problem.
  
  3.What each of several supervised learning algorithms accomplishes given a specific dataset.
  
  4.How to investigate whether a candidate solution model is adequate for the problem.
  
The success of your model will be determined based on your models AUC or area under the curve associated with ROC curves.


The training data for this competition is the same as what you used to complete the project (census.csv). However, the test data has a few more data cleaning issues. The 1 values in the test dataset indicate those with incomes greater than 50K, while 0 values indicate that is not the case. Your job is to find a model that performs best on the test data! Use your model to make predictions on the test_census.csv data, then provide the index and predicted income as either a 1 (if more than 50K) or 0 (if less than 50K).

You can use the example_submission.csv file as a template of what your submission should look like. However, you will need to change some of the appropriate rows to 0 to improve your score!
