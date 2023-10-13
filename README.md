# Assignment-9 Deploying the Model on AWS
This repository contains screenshots and a link to the Working model.

## Amazon Web Services (AWS)
Amazon Web Services (AWS) is a cloud computing platform that offers a wide range of services for hosting and managing applications and resources. We chose AWS for its scalability, reliability, and the vast ecosystem of tools and services it provides for deploying and managing machine learning models.

## WinSCP
WinSCP is an open-source SFTP, FTP, WebDAV, and SCP client for Windows. It allows us to securely transfer files between our local machine and remote servers. We'll use WinSCP to upload model files and data to our AWS instance.

## PuTTY
PuTTY is a popular open-source terminal emulator and SSH client for Windows. It will be used to access and control our AWS instance remotely.

## Deploying the Model
Once we have set up WinSCP and PuTTY, we can start deploying our machine-learning model on AWS. Here are the general steps to follow:

Upload Model Files: We will use WinSCP to transfer our model files, code, and any necessary data to our AWS instance.

SSH Access: We will use PuTTY to SSH into our AWS instance. This will give us terminal access to the server.

Install Dependencies: We will install any required libraries and dependencies on our AWS instance if they are not already present.

Run the Model: Now we will execute our machine learning model code on the AWS instance. Monitor the process and ensure it is functioning correctly.

Testing: Test our deployed model to ensure it works as expected.

## Screenshots of Deployed model
![Screenshot (100)](https://github.com/SatyamVis/Assignment-9-Deployement-of-House-prediction-model/assets/135328316/a8f00b37-41ef-40cc-8059-687dbcac9783)
![Screenshot (101)](https://github.com/SatyamVis/Assignment-9-Deployement-of-House-prediction-model/assets/135328316/ab4b05a1-9020-45d3-a8a6-a3348790ffbb)
![Screenshot (102)](https://github.com/SatyamVis/Assignment-9-Deployement-of-House-prediction-model/assets/135328316/f8522a1c-9464-4adc-8881-44dff2c440be)

## Working model link
http://ec2-18-224-25-108.us-east-2.compute.amazonaws.com:8080

## Link to all the files of the working model.
https://github.com/SatyamVis/House-Price-Prediction-
