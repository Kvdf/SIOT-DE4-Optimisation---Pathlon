# DE4-SIOT-Pathlon Coach
Serverless architecture service system comprised of Alexa, AWS, Meteor weathere API, Fitbit API - actuated through Amazon Alexa. 


Authors:K. vd Fluit 



## The Study 

Currently IoT is opening up new avenues for design and engineering, allowing us to create novel services that can allow the user to access a vast amount of data in form of actionable feedback . Personalised Healthcare, wearables, smart homes and personalised assistants are all topics driving the conversation . We are now seeing the personal tracking industry explore new ways to enhance health and wellbeing. This project aims to use your triathlon wearable data to inform best time of day to train → tracking sleep, amount of calories burnt, weight married with environmental data to determine in a given day what the best time of day is best to workout with the aim to prototype a commercially scalable service solution.

Key Words: Machine Learning, Fitness, IoT, Wearble




## Prerequisites

--Knowledge on building an Alexa Skill
--Knowledge on setting up AWS Lambda and working with AWS ML, AWS DynamoDB, AWS S3 


## Service 
Flow-Diagram of end-to-end service:
![pathlon - demo](https://github.com/Kvdf/Pathlon/blob/master/SystemGrey.png)




## Data Collected

Data that was collected from Fitbit Flex 2 device and Weerlive METEORSERVER API and used to create and train AWS ML model [fitbit.numbers](https://github.com/Kvdf/Pathlon/blob/master/fitbit.numbers)

## Additional Notes 

Additional files s3_transfer.py [s3_transfer](https://github.com/Kvdf/Optimisation---Pathlon/blob/master/s3_transfer.py); soley testing elements of transfering files to s3 as well as putting data in a DynamoDB table)-- can be run on Pycharm or any python environment. 
