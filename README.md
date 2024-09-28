# US Visa MLOps Prediction System

This project is an end-to-end machine learning system designed to predict the approval status of US Visa applications. It uses powerful algorithms like **XGBoost** and **Decision Trees**, integrated within a robust **MLOps pipeline** for continuous integration, model training, and deployment.

## Features
- **Modeling with XGBoost and Decision Trees**: Predictive models built using advanced algorithms to classify Visa approvals.
- **Data Exploration**: Comprehensive data cleaning, feature engineering, and exploratory data analysis (EDA) to derive insights and optimize model performance.
- **Hyperparameter Tuning**: Implemented GridSearchCV for hyperparameter tuning of models, ensuring the best possible accuracy and performance.
- **CI/CD Pipeline**: Automated testing and deployment using **GitHub Actions** and **Docker** for continuous integration.
- **AWS Deployment**: Models are deployed on **AWS S3** and **EC2**, ensuring scalable and reliable predictions.

## Tech Stack
- **Languages**: Python
- **Machine Learning**: XGBoost, Decision Trees, Random Forest
- **MLOps**: GitHub Actions, Docker
- **Cloud Services**: AWS S3, EC2
- **Data Exploration**: pandas, numpy, scikit-learn
- **Version Control**: Git, GitHub

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/utkarsh-iitbhu/USA-visa-mlops.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python app.py
   ```

## Data
The data used for this project includes features such as employee education, job experience, company size, region of employment, and wages to predict the likelihood of US visa approval.

## Deployment
The model is deployed on AWS, using S3 for storage and EC2 for hosting the application. CI/CD integration via GitHub Actions ensures the deployment process is automated and seamless.

## Contributing
Feel free to fork this repository, submit issues, or make pull requests.

## License
This project is licensed under the MIT License.

[GitHub Repo Link](https://github.com/utkarsh-iitbhu/USA-visa-mlops)

## Steps to take for creating a pipeline of your code

1. Created monogodb_demo and research folder notebooks
2. For pipelinse we will be implementing
    - Data Ingestion | Data Drift with Evidently
    - Data Validation
    - Data Transformation
    - Model Training 
    - Model Evaluation
    - Model Pusher

3. Workflows: Append changes in this format
    - constants | Keep all the constants and variables for the project
    - entity
    - components
    - pipeline
    - Main file

Flowchart: https://whimsical.com/
MLOPs Tool: https://www.evidentlyai.com/

