# LLM Science Exam - Kaggle

Find more details [here](https://www.kaggle.com/competitions/kaggle-llm-science-exam/overview)

# Description
This project is a part of MLOps Zoomcamp course. The ultimate goal is to build an end-to-end ML project which cover the whole machine learning lifecycle. It starts from defining problem statement, experiment, deployment, workflow orchestration, metrics monitoring, and best practice in building high-quality software. There is nothing relevant to model tuning to improve accuracy from 0.95 to 0.96...
# Tech stacks
This project leverages the following tech stacks:
- AWS
- MLFlow
- Prefect
- Evidently
  

# Checklist for grading
- Problem description
  - describe in README.md file
- Cloud
  - AWS with Terraform to provision
- Experiment tracking and model registry
  - MLFlow to track experiments and store in registry
- Workflow orchestration
  - Deploy workflow via Prefect
- Model deployment
  - Containerize model for deployment
- Model monitoring
  - Evidently to monitor the model
- Reproducibility
  - Code instruction is included
- Best practice
  - unit test
  - integration test
  - linter
  - Makefile
  - pre-commit hooks
  - CI/CD

# Prototyping part
- build prototype code in notebook
- see what work, what not
# Experimenting part
- identify params and metrics to experiment
- log experiments in MLFlow
  
# Deployment part
- create FastAPI for REST API Endpoint

