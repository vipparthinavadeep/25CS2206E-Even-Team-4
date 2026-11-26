# Smart Cold-Chain Assurance for Vaccines using Predictive Excursion Modelling

## Team Number: 4

## 👥 Team Members

| Roll Number | Team Member |
|---|---|
| 2520030019 | V. Navadeep |
| 2520030146 | K. Srinivas |
| 2520030148 | K. Shashwath |

## 📌 Project Overview

**Smart Cold-Chain Assurance for Vaccines using Predictive Excursion Modelling** is a cloud-based intelligent monitoring system designed to monitor vaccine storage temperatures and predict potential temperature excursions.

Vaccines require specific temperature conditions during storage and transportation to maintain their quality and effectiveness. However, manual temperature monitoring and delayed detection of temperature variations can increase the risk of vaccine damage.

Our project aims to address this problem by combining **Machine Learning and AWS Cloud Services** to monitor temperature readings, analyse temperature patterns, predict possible excursions, and generate early alerts.

Initially, the system will use simulated temperature data. Physical temperature sensor integration can be explored in future development.

## 🎯 Problem Statement

Maintaining the correct temperature throughout vaccine storage and transportation is essential. Traditional monitoring methods may depend on manual checking, which can lead to delayed detection of temperature fluctuations.

Unexpected temperature changes caused by equipment failures, power interruptions, or transportation delays may affect vaccine quality.

There is a need for an intelligent system that can continuously monitor temperature conditions and predict potential temperature excursions before they become critical.

## 💡 Proposed Solution

We propose a cloud-based monitoring and prediction system that:

- Collects and monitors vaccine storage temperature readings.
- Stores current and historical temperature data.
- Uses Machine Learning to identify temperature patterns.
- Predicts potential temperature excursions.
- Generates alerts when abnormal temperature conditions are detected or predicted.
- Provides a dashboard to visualise temperature readings, predictions, and alerts.

## ⚙️ Key Features

- **Temperature Monitoring:** Tracks vaccine storage temperature readings.
- **Predictive Analysis:** Uses Machine Learning to estimate possible future temperature changes.
- **Early Warning System:** Generates alerts for potential temperature excursions.
- **Cloud Data Storage:** Stores temperature readings and historical datasets.
- **Interactive Dashboard:** Displays temperature information, predictions, and alerts.
- **Cloud Monitoring:** Uses AWS monitoring services to track application activity.

## 🏗️ System Architecture

The proposed system follows this workflow:

1. **Data Collection:** Python generates simulated temperature readings initially.
2. **Data Storage:** Amazon DynamoDB stores temperature readings and alert records, while Amazon S3 stores historical datasets.
3. **Data Processing:** AWS Lambda processes incoming readings and performs temperature checks.
4. **Predictive Modelling:** Python and Scikit-learn analyse temperature patterns and predict possible excursions.
5. **Alert Generation:** Amazon SNS sends notifications when potential temperature problems are identified.
6. **Dashboard:** A Flask-based web application displays temperature readings, predictions, and alerts.
7. **Application Monitoring:** Amazon CloudWatch monitors application logs and activity.

AWS IoT Core can be integrated in a future phase to receive readings from physical temperature sensors.

## 🛠️ Technologies Used

### Programming Languages
- Python
- HTML
- CSS
- JavaScript

### Backend and Machine Learning
- Flask
- Pandas
- NumPy
- Scikit-learn

### AWS Cloud Services
- Amazon EC2
- Amazon S3
- Amazon DynamoDB
- AWS Lambda
- Amazon SNS
- Amazon CloudWatch
- AWS IAM
- AWS IoT Core (future integration)

### Development Tools
- Visual Studio Code
- Git
- GitHub
- AWS CLI
- Linux Terminal

## 📊 Expected Outcome

The expected outcome is a cloud-based intelligent vaccine temperature monitoring system that provides:

- Real-time or simulated temperature monitoring.
- Historical temperature data management.
- Prediction of potential temperature excursions.
- Early warning notifications.
- A dashboard for monitoring temperature conditions and system activity.

The system aims to support better temperature monitoring and help responsible staff take timely action to protect vaccine quality.


**Smart Cold-Chain Assurance for Vaccines using Predictive Excursion Modelling**

*Combining Cloud Computing and Machine Learning for smarter vaccine temperature monitoring.*
