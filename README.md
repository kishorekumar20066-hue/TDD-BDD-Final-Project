# ci-cd-final-project

## Project Name
CI/CD Final Project

## Project Description
This project demonstrates Continuous Integration and Continuous Delivery (CI/CD) using GitHub Actions, Tekton Pipelines and OpenShift. It includes automated testing, code quality checks, container image building and application deployment.

## Technologies Used
- Python
- GitHub
- GitHub Actions
- Tekton Pipelines
- OpenShift
- Nose
- Coverage
- Flake8
- Behave
- Docker / Buildah

## Usage
This project demonstrates CI/CD automation using GitHub Actions and OpenShift Tekton Pipelines.

## Setup

After entering the lab environment, run the setup script in the `./bin` folder to install the prerequisite software.

```bash
bash bin/setup.sh
```

Then exit the shell and start a new one for the Python virtual environment to be activated.

```bash
exit
```

## Tasks

The project uses Test Driven Development (TDD) and Behavior Driven Development (BDD) techniques.

The following files are used:

```text
tests/test_models.py
tests/test_routes.py
service/routes.py
features/products.feature
features/steps/load_steps.py
```

## CI/CD Pipeline

The CI/CD pipeline includes the following stages:

1. Cleanup
2. Git Clone
3. Flake8 / ESLint
4. Nose / Jest Tests
5. Buildah
6. OpenShift Deployment

## License

Licensed under the Apache License. See LICENSE.

## Author

John Rofrano, Senior Technical Staff Member, DevOps Champion, IBM Research.

© IBM Corporation 2023. All rights reserved.
