# CO2-Emission-Prediction-with-Machine-Learning-Jupyter-Notebook-Docker-
CO2 Emission Prediction with Machine Learning (Jupyter Notebook &amp; Docker)

ntroduction
Climate change is a pressing issue, with human CO2 emissions playing a significant role. This project aims to provide more comprehensive country-wise CO2 predictions by analyzing a time series dataset and applying various machine learning algorithms.

Setting Up the Development Environment
This guide covers two independent options:

Jupyter Notebook:

Clone the repository using git clone https://github.com/iTorongo/CS4020-ML-CO2-Emission-Prediction.
Navigate to the project directory.
Create a virtual environment (instructions specific to your operating system are provided).
Install project dependencies using pip install -r requirements.txt (adjust for your OS).
Run Jupyter Lab with jupyter lab.
API Server and Dashboard:

Requires Docker (https://www.docker.com/) installed.
Run docker-compose build && docker-compose up -d to launch the development environment in Docker containers.
Access the dashboard at http://localhost:3000 after the setup finishes.
Stop the containers with docker-compose down when finished.
