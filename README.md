# About me

I have mixed experience of combining Information technology and supply chain. I am currently a
Microsoft Certified Azure Data Scientist Associate with high domain knowledge on supply chain
activities gained from both work and studies. I have the ability to analyse problems and translate
them into mathematical models and applications, thus predicting future events with machine learning
and with the ability to prescribe solutions with operations research and supply chain techniques.

[contact me](https://www.linkedin.com/in/diego-arinze-uchendu-1970188b/)

# Projects

## [1_Operationalizing Machine Learning (click)](https://github.com/Aduzona/Microsoft-Azure-ML-Projects/blob/master/1_Optimizing_an_ML_Pipeline_in_Azure)

![Creating and Optimizing an ML Pipeline](images/Creating_Optimize_ML_Pipeline.png)
[Image source](udacity.com)

In this project, I built and optimize an Azure ML pipeline using the Python SDK and a provided Scikit-learn model. This model is then compared to an Azure AutoML run.

We seek to create and optimize an ML Pipeline using Bank Marketing dataset by:

* Optimize custom mdel with HyperDrive
* Optimize using Automated machine learning(AutoML)
And Compare the results of the 2 methods

## [2_Machine Learning Operations (MLOps)(click)](https://github.com/Aduzona/Microsoft-Azure-ML-Projects/tree/master/2_Operationalizing_Machine_Learning)

![Architectural Diagram](images/1_Project_Flow.png)
The Architectural Diagram provided above starts from Authentication and ends with Documentation.

[Watch Project Demo](https://youtu.be/7dhdi-XTauE)

This Project aimed at Operationalizing Machine Learning, by applying DevOps principles to Machine Learning, usually known as MLOPs. I will start by creating an ML model from the Bank Marketing dataset, from there I deploy the model, consume endpoint it and pipeline automation. it. 



## [3_Predicting mortality by heart failure using Microsoft Azure (click)](https://github.com/Aduzona/Microsoft-Azure-ML-Projects/tree/master/3_Capstone_Project_Azure_ML_Engineer)

![Project Flow](images/0_capstone-diagram.png)

[Watch_Project_Demo](https://youtu.be/FyO7d5RUqPw)

I will start by getting the Heart failure dataset into Azure datastore, then create 2 models, one using AutoML and the other using HyperDrive,Compare there performance, Deploy Best Model and Test Model End Point.


## [4_Find Donor](https://github.com/Aduzona/Machine_Learning_Projects/tree/master/finding_donors)

### Supervised Learning
#### Project: Finding Donors for CharityML
[code](https://github.com/Aduzona/Machine_Learning_Projects/blob/master/finding_donors/finding_donors.ipynb)
#### Data

The modified census dataset consists of approximately 32,000 data points, with each datapoint having 13 features. This dataset is a modified version of the dataset published in the paper *"Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid",* by Ron Kohavi. You may find this paper [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf), with the original dataset hosted on [UCI](https://archive.ics.uci.edu/ml/datasets/Census+Income).

**Features**
- `age`: Age
- `workclass`: Working Class (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
- `education_level`: Level of Education (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
- `education-num`: Number of educational years completed
- `marital-status`: Marital status (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
- `occupation`: Work Occupation (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
- `relationship`: Relationship Status (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
- `race`: Race (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
- `sex`: Sex (Female, Male)
- `capital-gain`: Monetary Capital Gains
- `capital-loss`: Monetary Capital Losses
- `hours-per-week`: Average Hours Per Week Worked
- `native-country`: Native Country (United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands)

**Target Variable**
- `income`: Income Class (<=50K, >50K)


## [5_image_classifier_with_tensorflow](https://github.com/Aduzona/image_classifier_with_tensorflow)

In this udacity project, I developed code for an image classifier built with TensorFlow, then you will convert it into a command line application.

In order to complete this project, you will need to use the GPU enabled workspaces within the classroom. The files are all available here for your convenience, but running on your local CPU will likely not work well.

You should also only enable the GPU when you need it. If you are not using the GPU, please disable it so you do not run out of time!

[code](https://github.com/Aduzona/image_classifier_with_tensorflow/blob/master/Project_Image_Classifier_Project.ipynb)

### Data

The data for this project is quite large - in fact, it is so large you cannot upload it onto Github. If you would like the data for this project, you will want download it from the workspace in the classroom. Though actually completing the project is likely not possible on your local unless you have a GPU. You will be training using 102 different types of flowers, where there ~20 images per flower to train on. Then you will use your trained classifier to see if you can predict the type for new images of the flowers.
