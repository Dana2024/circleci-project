# CircleCI Project for AWS S3 Deployment

This repository demonstrates the integration of CircleCI to automate the deployment of an application to an S3 bucket on AWS. 
The project was initially cloned from another repository for the purpose of learning and experimentation.

## Prerequisites

Before I started the project, I ensured that I have the following set up:

- A functioning AWS account.
- An S3 bucket created to store the deployed application.
- An IAM user with full access rights, specifically for this project's deployment. Ensure you securely store the user's Access Key ID and Secret Access Key.

- Configure CircleCI:
  - In the CircleCI dashboard, navigate to your project's settings.
  - Under "Environment Variables," add the following variables:
    - `AWS_ACCESS_KEY_ID`: Your AWS Access Key ID.
    - `AWS_SECRET_ACCESS_KEY`: Your AWS Secret Access Key.
    - `AWS_REGION`: your region.
- These environment variables will allow CircleCI to authenticate and deploy to your S3 bucket.


## Project Setup

Follow these steps to set up the project and enable automatic deployment:

1. **Clone the Repository:**
   
   Clone this repository to your local machine:
   
     git clone <repository_url>

## Deployment

Once you have set up the project and configured CircleCI, any changes pushed to the repository's main branch will trigger an automated deployment to the specified S3 bucket.


This project was created for educational purposes, inspired by the need to automate deployments using CircleCI and AWS S3. 
