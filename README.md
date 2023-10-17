# Applied-Stats-Problem-Set-2

# General Overview
This problem set contains two unique problems. Problem 1 looks to predict home prices based on a variety of explanatory variables and Problem 2 looks to develop a model predicting patients' number of doctor visits over a 3-month period. I use R to answer both problems. 

# Use Case
Problem 1 is a great exercise for anyone trying to do a comparison of various models, with a particular focus on changes they can make to improve their modeling (e.g., removal of outliers, removal of terms, multicollinearity, etc.). In this case, I specifically look for outliers, multicollinearity and run Mallows CP in an effort to improve my model. After each change, I re-estimate the model and do a final comparison of all models using AIC and BIC, and perform five-fold cross validation on the selected model. As you can tell, this exercise exposes you to many important concepts for model estimation and selection. Problem 2 is less ivolved but will expose you to important concepts such as hypothesis testing and difference in differences.

# Important Notes
1. Detailed instructions for each problem can be found in "Question_Set.pdf". All answers and supporting code can be found in "Final_Answers.Rmd" and "Final_Answers.pdf".
2. Supporting data for the first problem can be found in the "Problem1_Supporting_Data" folder. In that folder you will find a file named "Problem1_Supporting_Data_Description.txt" describing the data I used.
3. Supporting data for the second problem can be found in the "Problem2_Supporting_Data" folder. The data desription for that file can be found on pages 2 and 3 of "Question_Set.pdf".
