# Machine-Learning-Prediction-API-with-FastAPI
This project is a complete end-to-end MLOps demonstration. It involves training a machine learning model to solve a specific problem [&lt;-- State the problem, e.g., "predict customer churn" or "classify iris species"] and deploying it as a REST API using FastAPI.The project showcases skills in model training, API development, and data versioning.


This project utilizes a modern MLOps stack for development and deployment:

*Model Training & Experimentation*: scikit-learn, pandas, numpy.
*Data & Pipeline Versioning*: dvc.
*Web Framework for API*: fastapi.
*Asynchronous Server*: uvicorn.
*Environment Management*: python-dotenv.

## Project Architecture

The project follows a standard MLOps workflow:

1.  *Data Ingestion*: Data is loaded and preprocessed.
2.  *Model Training*: A scikit-learn model is trained on the preprocessed data.
3.  *Model Serialization*: The trained model is saved as an artifact.
4.  *DVC Pipeline*: DVC is used to version control the dataset and model, ensuring reproducibility.
5.  *FastAPI Application*: An API is built to load the saved model and serve predictions via HTTP endpoints.
6.  *Server*: The FastAPI application is run using a Uvicorn server.
