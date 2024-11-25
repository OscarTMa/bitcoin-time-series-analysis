# Bitcoin Time Series Analysis and Forecasting

Analyze and forecast Bitcoin prices using ARIMA/SARIMA, LSTM, and XGBoost. Develop a REST API for real-time predictions, containerized with Docker and orchestrated with Kubernetes for scalable cloud deployment. Gain insights into time series modeling, API development, and large-scale deployment workflows.

## Table of Contents
1. [Project Description](#project-description)
2. [Technologies Used](#technologies-used)
3. [Setup and Installation](#setup-and-installation)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [Contributing](#contributing)
7. [License](#license)
8. [Authors](#authors)



**Project Description**
Bitcoin's price exhibits high volatility and fluctuates dramatically over time. This project aims to analyze historical Bitcoin price data and build robust forecasting models to predict future prices. By combining traditional time series models (ARIMA/SARIMA), deep learning (LSTM), and machine learning approaches (XGBoost), the project showcases a comprehensive approach to time series analysis and forecasting.

The goal is not only to generate accurate predictions but also to create a deployable solution in the form of a REST API. The API enables real-time forecasting, making the models accessible for practical applications.

**Key Features**
- Time Series Modeling:
     ARIMA/SARIMA: Utilized for statistical forecasting based on historical trends and seasonality.
     LSTM (Long Short-Term Memory): Captures temporal dependencies and nonlinear patterns in data.
     XGBoost: Incorporates machine learning techniques for robust time series forecasting.
- REST API Development:                                
     Built using Flask or FastAPI, the API serves predictions based on user input (e.g., date range).
- Cloud Deployment:
  The entire solution is containerized using Docker, and Kubernetes is employed for orchestration. This ensures scalability and reliability for cloud-based applications.

**Project Objectives**                                                        
1.Model Bitcoin Price Trends:
- Use ARIMA/SARIMA for baseline predictions.
- Leverage LSTM and XGBoost to enhance prediction accuracy.
  
2.Develop a Forecasting API:
- Provide a user-friendly API for real-time price prediction.

3.Deploy Models on the Cloud:

- Containerize the API and models with Docker.
- Orchestrate deployment using Kubernetes for scalability.

## Technologies Used
- **Statsmodels**: For traditional time series modeling (ARIMA/SARIMA).
- **TensorFlow/Keras**: For LSTM implementation.
- **XGBoost**: For machine learning-based forecasting.
- **Flask/FastAPI**: To build the REST API.
- **Docker**: Containerization of the API and models.
- **Kubernetes**: Orchestration for cloud deployment.
- **Google Colab**: For initial data exploration and modeling.

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/oscarTMa/bitcoin-time-series-analysis.git

## Estructura del Repositorio

bitcoin-time-series-analysis/                                                     
│                                                     
├── api/                                                     
│   ├── main.py                                                     
│   ├── requirements.txt                                                     
│   └── tests/                                                     
│                                                     
├── data/                                                     
│   ├── raw/                                                     
│   ├── processed/                                                     
│   └── README.md                                                     
│                                                     
├── docker/                                                     
│   ├── Dockerfile                                                     
│   └── docker-compose.yml                                                     
│                                                     
├── kubernetes/                                                     
│   ├── deployment.yaml                                                     
│   ├── service.yaml                                                     
│   └── README.md                                                     
│                                                     
├── notebooks/                                                     
│   ├── bitcoin_analysis.ipynb                                                     
│   └── README.md                                                     
│                                                     
├── scripts/                                                     
│   ├── preprocess.py                                                     
│   └── forecast.py                                                     
│                                                     
├── tests/                                                     
│   ├── test_api.py                                                     
│   ├── test_forecast.py                                                     
│   └── README.md                                                     
│                                                     
├── LICENSE                                                     
├── README.md                                                     
└── .gitignore                        

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Authors
Oscar Tibaduiza (oscartibaduiza@hotmail.com)

