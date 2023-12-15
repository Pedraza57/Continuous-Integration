
# ☁️ AWS Continuous Integration Project ☁️

Overview

This project demonstrates setting up a continuous integration (CI) pipeline for a Python application using AWS services. The CI process is automated through AWS CodePipeline and AWS CodeBuild, enabling seamless integration of changes from a GitHub repository to deployment.


## 

![App Screenshot](https://ecsworkshop.com/images/cd-pipeline.svg)


## CI Process ⏩

The CI process is triggered automatically upon changes to the GitHub repository. CodePipeline fetches these changes, initiating CodeBuild to build and package the Python application. The automated flow ensures a consistent and reliable deployment.


## Key Components

- GitHub Repository: The Python application source code is hosted on GitHub, acting as the central repository for version control.

- AWS CodePipeline: CodePipeline orchestrates the flow of changes, automating the CI/CD process from the GitHub repository to deployment.

- AWS CodeBuild: CodeBuild is responsible for building and packaging the Python application based on the specifications defined in the buildspec.yml file.
