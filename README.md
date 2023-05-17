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

* Neurons, layers, and activation functions for the neural network model: All hidden layers use the Sigmoid activation function which provided an accuracy score of 72%, which is close to the target model performance of 75%

![image](https://github.com/latoyawenzinger/Deep-Learning-Challenge/assets/115582691/f366a959-c02b-4577-b4d3-8d8f2f957cb5)
![image](https://github.com/latoyawenzinger/Deep-Learning-Challenge/assets/115582691/3e4fc1cc-55d1-4d45-8784-2c4014eb43ad)

* Using 3 optimizing techniques, the model could not reach the target accuracy score of 75% or higher. The optimized model generated a higher accuracy score, although it was miniscule(+0.01%). The number of epochs was reduces from 100 to 60. 2 more hidden layers were added and more neurons were added to the layers from the original model.

![image](https://github.com/latoyawenzinger/Deep-Learning-Challenge/assets/115582691/51084f2f-7604-4e0e-a3c8-507f4f7e8a8e)
![image](https://github.com/latoyawenzinger/Deep-Learning-Challenge/assets/115582691/d78ed617-f454-4e65-9051-2ba0f4897289)


## **Summary**: 

I think that preprocessing the features via encoding would help to optimize the model better. Using an encoder such as OneHotEncoder would convert the categorical features into numerical 'dummy' features. The new numerical features data would allow the training of the model to be more efficient.
