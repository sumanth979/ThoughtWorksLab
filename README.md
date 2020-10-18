# ThoughtWorksLab
ThoughtWorks Lab Exercise

## Technologies Used
This Technologies used in this deployment is
* Yaml Scripting
* Python
* Shell Scripting
* Cloud Formation Template
* Ansible Playbooks

## Deployment Templates Available
* Blue-Green Deployment
* Rolling Update Template

## Deployment Steps

### File Details
* blueGreen.yaml                 - Cloud Formation template for blue green deployment.
* rollingUpdate.yaml             - Cloud Formation template for rolling deployment.
* parameters.json                - The parameters file for blue green deployment.
* mediawikiInstallationSteps.txt - Manual steps for mediawiki installation.
* dynamicInventory.py            - To create dynamic Inventory based on the ec2 tags.
* playbook.yaml                  - Ansible playbook for mediaWiki installation.
* seup.sh                        - Setup file for deployment.








## Architecture
### Blue Green Mode
<img src="https://github.com/sumanth979/AWS_BlueGreenDeployment/blob/master/Deploying_EC2_Instances/blue-green.png" alt="blue-green">
### Rolling Update Mode
<img src="https://github.com/sumanth979/AWS_BlueGreenDeployment/blob/master/Deploying_EC2_Instances/rolling.png" alt="rolling">

## Outputs
