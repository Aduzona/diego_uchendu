# About me

I am a versatile software engineer with strong skills in data science, DevOps, cloud management, and data science. I specialize in
 building Predictive web applications and microservices using Flask, Spring Boot, and JavaScript, adhering to SCRUM
 and CI/CD principles. Experienced in infrastructure automation, I utilize tools like Docker, Kubernetes and Gitlab CI, to
 streamline development workflows and manage AWS resources. Additionally, I have contributed to
 data-driven solutions, creating dashboards and extracting data using Python and SQL. My expertise includes
 monitoring assets and sensors and developing data visualization applications. I have a strong educational
 background with master's degrees in Operations Research and Analytics, paired with a passion for machine learning
 and predictive analytics.

[contact me](https://www.linkedin.com/in/diego-arinze-uchendu-1970188b/)

# Projects

## [1_Build the Backend System for a Car Website(click)](https://github.com/Aduzona/nd035-C2-Web-Services-and-APIs-Exercises-and-Project-Starter)

In this project, I used my skills with Spring Boot, APIs, documentation, and testing to implement a Vehicles API that serves as an endpoint to track vehicle inventory. While the primary Vehicles API will perform CRUD operations (Create, Read, Update and Delete) related to vehicle details like make, model, color, etc., it will need to consume data from other APIs as well regarding location and pricing data. You will implement a RESTful API for the Vehicles API, as well as converting a Pricing Service API to a microservice.

By the end of this project, you'll have an application that can communicate with other services and be able to be viewed and used through Swagger-based API documentation.

I used Intellij, and I prefare that each of the microservice are opened in separate intellij IDE.

Microservices

* Location Service Code
* Price Service Code
* Vehicles API Code

For more details, visit [Build the Backend System for a Car Website] (https://github.com/Aduzona/nd035-C2-Web-Services-and-APIs-Exercises-and-Project-Starter)

## [2_CI_CD_ML_Model_Deployment_using_Flask_and_Docker(click)](https://github.com/Aduzona/CI_CD_ML_Model_Deployment_using_Flask_and_Docker/tree/master)



![images/Model_Deployment Flow](images/Model_Deployment.png)

After model training, model should be saved.

But in production environment this processes should occur,

* Live Data
* Feature Engineering
* Feature Selection
* Model Prediction: No model building here, we will use same model we built to make predicition.
* Prediction

We will be using joblib library to save the model, then we will be using the saved model to deploy it using flask. We will create an API then we will deploy it using Docker.


## [3_Operationalizing an AWS Machine Learning(click)](https://github.com/Aduzona/AWS_Operationalize_ML_Project)

![Operationalize AWL ML](images/0_0_introduction-to-operationalizing-machine-learning-on-sagemaker.png)

[source Udacity](https://www.udacity.com/course/aws-machine-learning-engineer-nanodegree--nd189)

In this project, I completed the following steps:

1. Train and deploy a model on Sagemaker, using the most appropriate instances. Set up multi-instance training in Sagemaker notebook.
2. Adjusted Sagemaker notebooks to perform training and deployment on EC2.
3. Set up a Lambda function for deployed model. Set up auto-scaling for my deployed endpoint as well as concurrency for my Lambda function.
4. Ensured that the security on my ML pipeline is set up properly.

[click her for more](https://github.com/Aduzona/AWS_Operationalize_ML_Project)



## [4_Build_Deploy and Monitor a Machine Learning workflow for Image Classification(click)](https://github.com/Aduzona/AWS-Machine-Learning-Workflow-Project)

In this project, you'll be building an image classification model that can automatically detect which kind of vehicle delivery drivers have, in order to route them to the correct loading bay and orders. Assigning delivery professionals who have a bicycle to nearby orders and giving motorcyclists orders that are farther can help Scones Unlimited optimize their operations.

As an MLE, your goal is to ship a scalable and safe model. Once your model becomes available to other teams on-demand, it’s important that your model can scale to meet demand, and that safeguards are in place to monitor and control for drift or degraded performance.

In this project, you’ll use AWS Sagemaker to build an image classification model that can tell bicycles apart from motorcycles. You'll deploy your model, use AWS Lambda functions to build supporting services, and AWS Step Functions to compose your model and services into an event-driven application. At the end of this project, you will have created a portfolio-ready demo that showcases your ability to build and compose scalable, ML-enabled, AWS applications.

**Project Steps Overview**

<ol>
    <li>Step 1: Data staging</li>
    <li> Step 2: Model training and deployment</li>
    <li> Step 3: Lambdas and step function workflow</li>
    <li> Step 4: Testing and evaluation</li>
    <li> Step 5: Optional challenge</li>
    <li> Step 6: Cleanup cloud resources</li>
</ol>

## [5_Operationalizing Machine Learning (click)](https://github.com/Aduzona/Microsoft-Azure-ML-Projects/blob/master/1_Optimizing_an_ML_Pipeline_in_Azure)

![Creating and Optimizing an ML Pipeline](images/Creating_Optimize_ML_Pipeline.png)
[Image source](udacity.com)

In this project, I built and optimize an Azure ML pipeline using the Python SDK and a provided Scikit-learn model. This model is then compared to an Azure AutoML run.

We seek to create and optimize an ML Pipeline using Bank Marketing dataset by:

* Optimize custom mdel with HyperDrive
* Optimize using Automated machine learning(AutoML)
And Compare the results of the 2 methods

## [Machine Learning Operations (MLOps)(click)](https://github.com/Aduzona/Microsoft-Azure-ML-Projects/tree/master/2_Operationalizing_Machine_Learning)

![Architectural Diagram](images/1_Project_Flow.png)
The Architectural Diagram provided above starts from Authentication and ends with Documentation.

[Watch Project Demo](https://youtu.be/7dhdi-XTauE)

This Project aimed at Operationalizing Machine Learning, by applying DevOps principles to Machine Learning, usually known as MLOPs. I will start by creating an ML model from the Bank Marketing dataset, from there I deploy the model, consume endpoint it and pipeline automation. it. 



## [Predicting mortality by heart failure using Microsoft Azure (click)](https://github.com/Aduzona/Microsoft-Azure-ML-Projects/tree/master/3_Capstone_Project_Azure_ML_Engineer)

![Project Flow](images/0_capstone-diagram.png)

[Watch_Project_Demo](https://youtu.be/FyO7d5RUqPw)

I will start by getting the Heart failure dataset into Azure datastore, then create 2 models, one using AutoML and the other using HyperDrive,Compare there performance, Deploy Best Model and Test Model End Point.


## [Find Donor](https://github.com/Aduzona/Machine_Learning_Projects/tree/master/finding_donors)

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


## [image_classifier_with_tensorflow](https://github.com/Aduzona/image_classifier_with_tensorflow)

In this udacity project, I developed code for an image classifier built with TensorFlow, then you will convert it into a command line application.

In order to complete this project, you will need to use the GPU enabled workspaces within the classroom. The files are all available here for your convenience, but running on your local CPU will likely not work well.

You should also only enable the GPU when you need it. If you are not using the GPU, please disable it so you do not run out of time!

[code](https://github.com/Aduzona/image_classifier_with_tensorflow/blob/master/Project_Image_Classifier_Project.ipynb)

### Data

The data for this project is quite large - in fact, it is so large you cannot upload it onto Github. If you would like the data for this project, you will want download it from the workspace in the classroom. Though actually completing the project is likely not possible on your local unless you have a GPU. You will be training using 102 different types of flowers, where there ~20 images per flower to train on. Then you will use your trained classifier to see if you can predict the type for new images of the flowers.
