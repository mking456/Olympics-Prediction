# Olympic Medal Prediction
# Goal
### The goal of this project is to make a prediction model which will predict whether an athlete will win medal or not.

## DATASET
The dataset which is used in this project, is collected from Kaggle. Here is the link of the dataset :[Datset](https://www.kaggle.com/datasets/piterfm/paris-2024-olympic-summer-games)

## LIBRARIES NEEDED
* Pandas
* Numpy
* Sklearn
* Matplotlib
### WHAT I HAD DONE
### Importing all the required libraries. Check requirements.txt
### Upload the dataset and the Jupyter Notebook file.
Loading and Cleaning the dataset.
Encoding textual columns.
Select best 10 features and make a new dataframe using them
Split dataframe into train and test data along with scaling.
Apply different classification models and calculate their accuracy.
Choose best model for our prediction which has highest accuracy.
## Make the final prediction using best model.
## Model Comparison
* We have deployed 6 machine learning algorithms and every algorithm is deployed successfully without any hesitation. We have checked the efficiency of the models based on the accuracy of each of the models. Now let's take a look at model with their accuracy.

## Name of the Model	Accuracy
* Logistic Regression	85.357825
* MultinomialNB	85.367968
* Decision Tree	84.095457
* Random Forest	88.779773
* Gradient Boosting	88.514205
* Neural Network	87.904691
## Conclusion
* Comparing all those scores scored by the machine learning algorithms, it is clear that Random Forest Classifier Model gives highest accuracy and will provide best prediction.



