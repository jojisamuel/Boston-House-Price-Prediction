## Boston-House-Price-Prediction

![image](https://user-images.githubusercontent.com/57321948/196933065-4b16c235-f3b9-4391-9cfe-4affcec87c35.png)

## Boston Housing Dataset

The Boston Housing dataset is a classic dataset for evaluating regression algorithms. It contains information on the median value of owner-occupied homes in various neighborhoods in the Boston area, along with other variables such as crime rate, air pollution, and the number of rooms in the house.
Data Description

The dataset consists of 506 samples and 13 features. The features are as follows:

    CRIM: per capita crime rate by town
    ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
    INDUS: proportion of non-retail business acres per town
    CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
    NOX: nitric oxides concentration (parts per 10 million)
    RM: average number of rooms per dwelling
    AGE: proportion of owner-occupied units built prior to 1940
    DIS: weighted distances to five Boston employment centers
    RAD: index of accessibility to radial highways
    TAX: full-value property-tax rate per $10,000
    PTRATIO: pupil-teacher ratio by town
    B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
    LSTAT: % lower status of the population

The target variable is the median value of owner-occupied homes in $1000s.

### Step 1 - Install the requirements

```bash
pip install -r requirements.txt
```

### AWS-CICD-Deployment-with-Github-Actions
```
1. Login to AWS console.
2. Create IAM user for deployment

With specific access

1. EC2 access : It is virtual machine

2. ECR: Elastic Container registry to save your docker image in aws


Description: About the deployment

1. Build docker image of the source code

2. Push your docker image to ECR

3. Launch Your EC2 

4. Pull Your image from ECR in EC2

5. Lauch your docker image in EC2

Policy:

1. AmazonEC2ContainerRegistryFullAccess

2. AmazonEC2FullAccess

3. Create ECR repo to store/save docker image

- Save the URI: 

4. Create EC2 machine (Ubuntu)
5. Open EC2 and Install docker in EC2 Machine:

#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker

6. Configure EC2 as self-hosted runner:

setting>actions>runner>new self hosted runner> choose os> then run command one by one

7. Setup github secrets:

AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = 

ECR_REPOSITORY_NAME = 
