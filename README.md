# udacity-capstone
CLOUD DEVOPS ENGINEER - UDACITY CAPSTONE PROJECT

[![<ORG_NAME>](https://circleci.com/gh/hiepga1233/udacity-capstone.svg?style=svg)](https://circleci.com/gh/hiepga1233/udacity-capstone)

## Project Overview

In this project you will apply the skills and knowledge which were developed throughout the Cloud DevOps Nanodegree program. These include:

- Working in AWS
- Using Jenkins or Circle CI to implement Continuous Integration and Continuous Deployment
- Building pipelines
- Working with Ansible and CloudFormation to deploy clusters
- Building Kubernetes clusters
- Building Docker containers in pipelines


##This app use:
1. Create EKS by CloudFormation (profile attached in infra/cluster.yml)
2. Build and push Docker Image to Docker Hub
3. Using Green/Blue Deployment (Green ver.1, Blue ver.2)
4. Deploy Demo app (Python) to EKS Cluster by kubectl