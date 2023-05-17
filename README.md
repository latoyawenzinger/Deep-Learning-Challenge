# Deep-Learning-Challenge

A machine learning tool was created for a nonprofit foundation, Alphabet Soup, to determine if future applicants will be successful if funded. 

## **Overview**:

The purpose of this analysis is to take a look at the performance of the deep learning model that was created. It will explain the thought process behind data processing, training, and optimizing techninques used to enhance the model. 

## **Results**

### **Data Preprocessing**:

* Target Variable: 
  * 'IS_SUCCESSFUL' - was the money used successfully (0 or 1)
* Feature Variables: 
  * AFFILIATION — Affiliated sector of industry
  * CLASSIFICATION — Government organization classification
  * USE_CASE — Use case for funding
  * ORGANIZATION — Organization type
  * STATUS — Active status
  * INCOME_AMT — Income classification
  * SPECIAL_CONSIDERATIONS — Special considerations for application
  * ASK_AMT — Funding amount requested
  
* Removed Data:
  * EIN and NAME — Identification columns


## **Compiling, Training, and Evaluating the Model**:

* Neurons, layers, and activation functions for the neural network model. All hidden layers use the Sigmoid activation function because the expected outputs are this model provided an accuracy score of 72%, which is close to the target model performance of 75%
![image](https://github.com/latoyawenzinger/Deep-Learning-Challenge/assets/115582691/f366a959-c02b-4577-b4d3-8d8f2f957cb5)
![image](https://github.com/latoyawenzinger/Deep-Learning-Challenge/assets/115582691/3e4fc1cc-55d1-4d45-8784-2c4014eb43ad)


Were you able to achieve the target model performance?
What steps did you take in your attempts to increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
