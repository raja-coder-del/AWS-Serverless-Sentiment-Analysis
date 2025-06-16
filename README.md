# 🚀 AWS Project: [AWS Serverless Sentiment Analysis](https://github.com/22MH1A42G1/AWS-Serverless-Sentiment-Analysis)

## 📌 Project Description

A lightweight serverless API that performs sentiment analysis on user-provided text using **AWS Comprehend**. The API is exposed via **API Gateway**, powered by **AWS Lambda**, and can be accessed via a simple frontend. A **serverless sentiment analysis** web app using ```AWS Lambda, API Gateway, S3, and Comprehend```. Users can submit text through a frontend page, and the backend returns the sentiment analysis result.

---

## 🏗️ Architecture Overview

#### Architecture Diagram

![Architecture](https://github.com/22MH1A42G1/AWS-Serverless-Sentiment-Analysis/blob/main/imgs/Architecture.jpg?raw=true)

## 📦 Features

* 🔍 Analyze text sentiment (Positive, Negative, Neutral, Mixed)
* ⚡ Fast response 
* 🌐 Exposed via AWS API Gateway
* 🖥️ Simple frontend for user input
* ☁️ 100% serverless on AWS

---

## ⚙️ Technologies Used

* AWS Lambda (Python Script ```boto3```)
* AWS Comprehend (Detect Sentiment)
* AWS API Gateway (REST API)
* AWS S3 ```HTML, JS (Frontend)```
* PostMan API ```(Testing)```
* AWS IAM

---

## 🚀 Setup Instructions

### 1. AWS Lambda (Python)

Lambda Function (`lambda_function.py`):


---

### 2. API Gateway

* Method: **POST**
* Resource: `/analyze`
* Integration Type: **Lambda Proxy Integration**
* CORS: Enabled (`*`)

---

### 3. Frontend Example (HTML)




---

## ❗ Troubleshooting

* **502 Internal Server Error?**
  Make sure Lambda parses `event['body']` correctly.

* **CORS Errors?**
  Ensure CORS is enabled in API Gateway settings.

* **Lambda Permissions?**
  Attach `ComprehendFullAccess` policy to the Lambda IAM role.


---

## 🧑‍💻 Author

**Indana Aditya**
[LinkedIn](https://www.linkedin.com/in/aditya-indana-899734216) • [GitHub](https://github.com/22MH1A42G1)

---
