# Vehicle-Insurance-Purchase-Prediction-
🚗 Vehicle Insurance MLOps Pipeline
📌 Project Overview

This project demonstrates an end-to-end MLOps pipeline for managing, processing, training, deploying, and automating machine learning workflows using vehicle insurance data.
It is designed to showcase practical, industry-style implementation for data engineering, model lifecycle management, deployment, and CI/CD automation.

🧰 Tools & Technologies Used
✅ Programming & Frameworks

Python

FastAPI (for prediction API)

Jupyter Notebooks

✅ Data & Storage

MongoDB Atlas (data ingestion and storage)

AWS S3 (model storage)

✅ Machine Learning Pipeline Components

Data Ingestion

Data Validation

Data Transformation

Feature Engineering

Model Training & Evaluation

Model Deployment

✅ DevOps / MLOps Stack

Docker

GitHub Actions

AWS EC2

AWS ECR

Environment variables & secrets management

🛠️ Steps Followed to Build the Project
1. Project Initialization

Generated folder structure and scaffold using template.py

Configured local package imports via setup.py and pyproject.toml

Created virtual environment and installed dependencies

2. Data Handling & MongoDB Integration

Configured MongoDB Atlas cluster

Created notebook to upload dataset to MongoDB

Verified records in database

3. Logging, Exceptions & EDA

Implemented logging and exception modules

Performed exploratory data analysis and feature engineering

4. Data Pipeline Development

Implemented ingestion components to fetch data from MongoDB

Defined schema and performed data validation

Applied data transformation and feature preprocessing

5. Model Training & Evaluation

Built training module and estimator logic

Implemented evaluation and comparison

Stored and retrieved models using AWS S3

6. Deployment & API Integration

Created prediction pipeline

Developed FastAPI app with templates and static assets

7. CI/CD and Cloud Deployment

Built Docker image and configuration

Set up GitHub Actions for automated deployment

Configured AWS EC2 and ECR

Exposed application and accessed via public IP