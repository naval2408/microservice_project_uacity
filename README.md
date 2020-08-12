[![<CircleCI>](https://circleci.com/gh/naval2408/microservice_project_uacity.svg?style=svg)](<LINK>)

## Project Overview
In this project, we have deployed a containerized Python service that predicts the housing prices in Boston using a trained prediction model.

### Project Procedure
* Static analysis of code via linting
* Created a Dockerfile to containerize the service
* Deployed the Docker Container to make a prediction
* Configured and created Kubernetes cluster
* Deployed the Kubernetes Container to make a prediction
* Did integration with CircleCI for running build pipeline



---
## Getting Started
### Setup the Environment

* Create a virtualenv and activate it
```
python3 -m venv <your_venv>
source <your_venv>/bin/activate
```
* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
