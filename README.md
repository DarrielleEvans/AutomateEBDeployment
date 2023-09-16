# AutomateEBDeployment
# Deployment 1.1

## Purpose
* This repository aims to automate the URL Shortener Application's build, test, and elastic Beanstalk Deployment stages.

## Steps
### Step 1
* Provided the Github URL in the Jenkins pipeline setup and built the Pipeline.
  <img width="715" alt="Screen Shot 2023-09-16 at 2 20 08 AM" src="https://github.com/DarrielleEvans/AutomateEBDeployment/assets/89504317/215c7425-28a9-4775-84e9-25f7c6a287fb">
* The stage and test were successful.

## Step 2
* Setup the appropriate Roles in IAM on AWS to deploy the application in Elastic Beanstalk.
<img width="1287" alt="Deployment 1 1 Degraded" src="https://github.com/DarrielleEvans/AWS-Deployment-1.1/assets/89504317/af2b6f46-8c98-4f78-a87f-b3e81c925dbd">
* The deloyment received a degraded health check.
* In order to assess the errors, I downloaded the last 100 logs.
* After placing the error in Chatgpt, I realized the app.py file was named incorrectly and throwing an error.


## Step 3
* I navigated to Github and changed the app.py file to application.py.
* I uploaded the new zip file to AWS Beanstalk.
* I received an ok health check.
<img width="1322" alt="Deployment 1 1 Success" src="https://github.com/DarrielleEvans/AWS-Deployment-1.1/assets/89504317/323aed7e-8625-4a2a-a62e-8b0df6516b3a">
<img width="1323" alt="Screenshot 2023-08-17 at 4 28 39 PM" src="https://github.com/DarrielleEvans/AWS-Deployment-1.1/assets/89504317/9dc39822-ff71-44ad-9b1a-17989b0991b8">

## Technologies Used
* AWS Beanstalk
* Jenkins Server
* Github
* AWS CLI EB
* AWS EC2
* Github WebHooks
