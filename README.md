Jenkins CI/CD Pipeline for Automated Application Deployment

About the Project

I built this project to understand how Jenkins can be used to automate the build, testing, and deployment of a web application.

I used Jenkins to create a CI/CD pipeline, Docker to build and run the application in a container, and AWS EC2 to deploy the application.

This project helped me gain hands-on experience with Jenkins pipeline configuration, Docker, GitHub integration, automated testing, and cloud deployment.

Project Flow

GitHub → Jenkins → Docker Image Build → Application Testing → AWS EC2 Deployment → Live Website

Architecture & Deployment Workflow

The application source code was maintained in GitHub, and Jenkins was configured to run the pipeline using a Jenkinsfile.

Deployment Flow

Application Source Code
↓
GitHub Repository
↓
Jenkins Pipeline
↓
Docker Image Build
↓
Application Testing
↓
AWS EC2 Deployment
↓
Live Web Application

Deployment Process

I stored the application source code and Jenkinsfile in a GitHub repository.

I configured a Jenkins pipeline to automate the application build and testing process.

I used a Dockerfile to build a Docker image for the web application.

I configured the pipeline to run the application in a temporary Docker container for testing.

I used PowerShell to verify the application's HTTP response and check whether it returned status code 200.

I troubleshot issues encountered during the pipeline execution and fixed them to achieve a successful build and test.

I deployed the application on an AWS EC2 instance using Docker.

I accessed the deployed application through a web browser to verify that it was working.

Technologies Used

Jenkins

Docker

AWS EC2

Git

GitHub

Nginx

PowerShell

Linux

HTML

CSS

JavaScript

What I Practiced

Through this project, I practiced:

Configuring a Jenkins pipeline using a Jenkinsfile

Integrating GitHub with Jenkins

Automating Docker image builds

Running Docker containers for application testing

Checking HTTP responses using PowerShell

Troubleshooting Jenkins pipeline failures

Deploying a Dockerized application on AWS EC2

Verifying the deployed application through a web browser

Jenkins Pipeline Implementation

I used a Jenkinsfile to define the pipeline stages and automate the application workflow.

The pipeline was configured to build the Docker image and test the application before proceeding with deployment.

This helped me understand how Jenkins can automate different stages of the application delivery process.

Docker Implementation

I created a Dockerfile to package the web application with Nginx.

Jenkins used the Dockerfile to build the application image, which was then used to run the application in a container.

Docker helped me run the application in a consistent environment during testing and deployment.

Automated Testing

I configured a testing stage in Jenkins to run the application in a temporary Docker container.

I used PowerShell's Invoke-WebRequest to check the application's HTTP response. The test passed when the application returned status code 200.

After testing, the temporary container was stopped and removed.

AWS EC2 Deployment

I deployed the Dockerized web application on an AWS EC2 instance.

The application was made accessible through the EC2 instance's public IP address, and I verified the deployment by opening the website in a web browser.

Troubleshooting

During the project, I encountered issues while configuring and running the Jenkins pipeline.

I checked the pipeline console output, corrected configuration issues, and verified the Docker image and container status to resolve the problems.

This helped me improve my troubleshooting skills and understand how to identify and fix issues during a CI/CD workflow.

What I Learned

This project helped me understand how Jenkins, Docker, GitHub, and AWS EC2 work together in a CI/CD workflow.

I gained practical experience in pipeline configuration, automated application testing, Docker-based deployment, and troubleshooting.

It also helped me understand how to reduce manual work by automating application build, testing, and deployment steps.

Project Outcome

Successfully implemented a Jenkins CI/CD pipeline to automate the build, testing, and deployment of a web application.

The pipeline built the Docker image, tested the application, and deployed it to an AWS EC2 instance. I verified that the deployed application was accessible through a web browser.

This project gave me practical experience in CI/CD automation, Docker containerization, AWS deployment, and troubleshooting pipeline issues.
