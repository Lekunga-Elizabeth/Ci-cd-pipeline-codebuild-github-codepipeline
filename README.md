# order-service

![Capture](https://user-images.githubusercontent.com/25712816/92306201-ef826380-efaa-11ea-9704-5304319e0517.PNG)


# THIS CODE EXPLAIN THE FOLLOWING ABOUT THE INFASTRUCTURE 
# In this example we want to deploy an application call Microservice app

# we are using the AWS CODEPIPELINE AS THE BUILD TOOL 

# we have the buildspec.yml file  where the configuration to be used to build the application and it is syn only with the AWS code build
#  We have Github that have the code and push the code to aws code build 
# we have Elastic Beanstalk where the code is deployed to. 
# 

## To come up with this Artitecture we need to do the following
# Deploy a Beanstalk by :
    * go to the aws console choose AWS Beanstalk

# Creat an AWS Pipeline 
    * Go to AWS Console choose codepipeline
    * create a pipeline 
    * put the service name 
    * click on connect to  Github then put your password