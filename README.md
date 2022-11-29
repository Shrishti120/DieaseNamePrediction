# DiseaseNamePrediction
It is a model which will predict the name of the dieaeas on the basis of the list of symptoms given .

If you see the model very carefully you will understand that whole prediction is done mainly on the basis of 3 main Machine Learning models and one combined mode which is the combination of all the 3 models .
## Steps done during the model building 
Step 1 - Import Libraries 
Step 2 - Reading the data
Step 3 - Getting Information about the data(exploring data)/Encoding data
Step 4 - Definig scoring metric for k fold cross validation and Initialising Models(3 models used are *GAUSSIAN NB* , *SVC* , *RANDOM FOREST*
Step 5 - Crucial Method which is Trainig the models and getting the accuracy on train and test data 
Step 6 - Trainig the combined model and getting the accuracy on the test and train data 
Step 7 - Exploring the test data and using it for the accuracy 
Step 8 - Definig a function which will be used for the prediction 
Step 9 - Giving list of Symptoms as an input 
Step 10 - Getting the most commen diease for that list of symptoms as the output 


## If we look at the Result or the accuracies of the model , we see
While training the models :
Naive Bayes gives an average accuracy of 98.77% on Train Data and 77.32% on test data 
Svm gives 89.45 % on train data and 48.01% on test data 
Random Forest gives 98.90% on Train Data and 82.095% on test data 
which shows that randomforest gives the most accurate result as per its accuracy values 
ALSO THE COMBINED MODEL GIVES AN ACCURACY OF 98.56 % ON TEST DATA 

## THE RESULT CAN BE CROSS VERIFIED WHILE PREDICTING THE DIEASE , WE SEE THAT MOST OF THE PREDICTIONS DONE BY RANDOM FOREST ARE CORRECT 

## Dataset 
Dataset used with the Implementation is uploaded in my kaggle 
link for the same is pinned here : https://www.kaggle.com/datasets/shrishtipandey/diseaseprediction



