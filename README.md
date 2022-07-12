# Neural_Network_Charity_Analysis

## Overview of the analysis: 

Beks is a Data Analyst for the non profit organization Alphabet Soup. She will be developing a model that will accuately predict which organizations will be worth donating to and which organizations are too high risk. By designing and training a deep neural network and evaluate all types of input data and produce a clear decision making result. We are here to help Beks do just that with the help of the python tensor flow library.

## Results:

### Data Preprocessing

What variable(s) are considered the target(s) for your model?
* The targeted variable for our model is the "IS_SUCCESSFUL" column.

What variable(s) are considered to be the features for your model?
* The variables that were considered for our features were:
* APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.  
               
What variable(s) are neither targets nor features, and should be removed from the input data?
* The variables removed from the input data was the "EIN" and "NAME" columns as they did not offer any helpful information for the machine learning.

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model?
* I selected 2 hidden layers with 80 and 30 neurons in each hidden layer.
* I used RELU as well as SIGMOID activation functions.

Were you able to achieve the target model performance?
* I was not able to achieve the target model performance as my best accuracy score was 72.9%:
![Screen Shot 2022-07-11 at 8 56 33 PM](https://user-images.githubusercontent.com/98780937/178405594-b6ac2b93-c25d-4176-b35d-45fba41fd34a.png)

What steps did you take to try and increase model performance?
* For my three attempts, i decided to add more hidden layers as well as more neurons to my hidden layers. I also decided to change the activation function from relu to sigmoid on my hidden layers and increased my epoch when i was training my model.
* My original training had an accuracy of 72.8%
![Screen Shot 2022-07-11 at 9 07 52 PM](https://user-images.githubusercontent.com/98780937/178406726-79a14b4a-5639-4fbd-902b-274a44d57080.png)
* My first attempt had the highest at 72.9%, as shown above.
* My second and third attempt was both at 72.6%
![Screen Shot 2022-07-11 at 9 07 34 PM](https://user-images.githubusercontent.com/98780937/178406871-1609f2d1-83f4-477d-88f2-92b51f0f662d.png)
![Screen Shot 2022-07-11 at 9 07 22 PM](https://user-images.githubusercontent.com/98780937/178406893-c208eedc-e14d-47cf-9b9b-00c37b67ae30.png)


## Summary: 
The overall results of my deep learning model was 72.9% accuracy. A recommendation for how a different model could solve this classification problem would be either added more data to the dataset as it adds accuracy, or add more features that would best help determine what "IS_SUCCESSFUL", which will give us a higher chance of getting a better score.

