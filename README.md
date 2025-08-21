# Java Web App Deployment with AWS CI/CD

Welcome to this project containing Java web app development and AWS CI/CS tools!

<br>

## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Setup](#setup)
- [Conclusion](#conclusion)

<br>

## Introduction
This project is used for an introduction to creating and deploying a Java-based web app using AWS especially their CI/CD tools.

The deployment pipeline I'm building around the Java web app in this repository is invisible to the end-user, but makes a big impact by automating the software release processes.

- I'm doing this project to learn more about CI/Cd and get hands on experience in automating the flow from developing code to deployed web app.

<br>

## Technologies
Here's what I'm using for this project -
- **Amazon EC2**: I'm developing my web app on Amazon EC2 virtual servers, so that software development and deployment happens entirely on cloud.
- **VSCode**: IDE for writing and managing the Java web application code.
- **AWS CodeArtifact**:  CodeArtifact will store artifacts and dependencies, which is great for high availability and speeding up my project's build process.
- **AWS CodeBuild**:  CodeBuild will take over the build process. It'll compile the source code, run tests, and produce ready-to-deploy software packages automatically.
- **AWS CodeDeploy**:  CodeDeploy will automate the deployment process across EC2 instances.
- **AWS CodePipeline**:  CodePipeline will automate the entire process from GitHub to CodeDeploy, integrating build, test, and deployment steps into one efficient workflow.


