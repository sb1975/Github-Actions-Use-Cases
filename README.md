Automate Software Deployment using Github Actions
Objective :
    This repository aims to provide steps, guidelines to use Github Actions to build and deploy resources on Azure Cloud.


![alt text](https://github.com/sb1975/Github-Actions-Use-Cases/blob/main/Overview.JPG){:height="50%" width="50%"}

Pre-requisite :

1. Active Azure account or Trial Account
2. Github account

Use Case :
 1. Automate Creation of an AKS Cluster and ACR using Github Actions
 2. Automate Creation of a Cloudnative Application on AKS(using helm), this includes the build and push of the image using Dockerfile.
 3. Any change on the code of the Application will trigger auto build and deploy
 
Limitations :
1. Before pipeline-platform.yaml is run again, the existing AKS and ssh-keys,associated SP,etc needs to be cleaned, the complete reason and resolution is unknown, Please refer known issue - https://github.com/Azure/azure-quickstart-templates/issues/5442 


Note : The purpose of this repository is purely educational, hence any suggestions,contributions are welcome.
