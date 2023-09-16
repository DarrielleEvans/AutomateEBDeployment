# Automate Elastic Beanstalk Deployment

## Purpose
* This repository aims to automate the URL Shortener Application's build, test, and elastic Beanstalk Deployment stages.

## Steps

### First Steps
* Upload code and Jenkins instructions file to a newly created repository
* Launch an EC2 instance with the correct security groups
* Install dependencies and Jenkins on the server
* Access Jenkins on port 8080
  

### Next Steps
* Connect your Github to Jenkins
* Add a deployment stage to Jenkins file on Github
* Run the build and test stage
* Pipeline ran successfully
<img width="819" alt="Screen Shot 2023-09-16 at 2 24 33 AM" src="https://github.com/DarrielleEvans/AutomateEBDeployment/assets/89504317/aa67058e-8074-42ab-9cd1-99de951ab897">

## Next Steps
* I Set IAM Roles
* Install EB CLI on EC2 Instance
* Run Pipeline in Jenkins
* This pipeline has an additional stage, which results in a build, test, and Deployment stage
  <img width="819" alt="Screen Shot 2023-09-16 at 2 24 33 AM" src="https://github.com/DarrielleEvans/AutomateEBDeployment/assets/89504317/3ee2988f-3c48-48f0-9abf-8e64cbf45770">

## Final Steps
* Create a webhook in Github to send information in the form of JSON every time code is pushed to the repository

## System Design
![Deployment3 drawio](https://github.com/DarrielleEvans/AutomateEBDeployment/assets/89504317/d1cbb979-3e7d-4aaf-943b-878fe7ee661e)

## Issues
* 2nd Build failed after adding the deployment stage to the Jenkins file. I incorrectly structured the code but was able to easily fix it.





## Technologies Used
* AWS Beanstalk
* Jenkins Server
* Github
* AWS CLI EB
* AWS EC2
* Github WebHooks
