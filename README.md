# Neural Network Model

### Overview 

The objective of this work is to analyse past funding results by Alphabet Soup to determine which organizations should be funded and also use deep learning neural network to interpret large complex datasets. We use Machine learning and Neural networks on Tensor Flow Keras to create a binary classifier that can predict the success of being funded by Alphabet Soup.

### Results

* *Data Preprocessing*
  * What variable(s) are considered the target(s) for your model?

The target variable is **IS_SUCCESSFUL**

  * What variable(s) are considered to be the features for your
model?

Features: **APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, STATUS**

* What variable(s) are neither targets nor features, and should
be removed from the input data?

I removed **EIN** and **NAME**

* *Compiling, Training, and Evaluating the Model*
  * How many neurons, layers, and activation functions did you
select for your neural network model, and why?

Screenshot of training:
![screenshot](Screenshot%20from%202021-09-21%2010-41-47.png)

I used 3 layers, with 80, 30 and 1 neurons.

* Were you able to achieve the target model performance?

No, I got 73% out of 75%.

* What steps did you take to try and increase model
performance?

I tried using the name as feature, this increased memory needed for training, and also more epochs, but it barely increased the accuracy to almost 74%. 

### Summary

After several attempts I could not achieve the target accuracy level of 75%. The selected model consisted of 3 hidden layers with 80, 30 and 1 neurons each. An alternative method would be to use random forest classifiers model.
