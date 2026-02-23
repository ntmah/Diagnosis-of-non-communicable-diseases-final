# AI-BASED NON-COMMUNICABLE DISEASE DIAGNOSIS SYSTEM

## Overview
This project implements a neural network built from scratch for multi-class
classification of three non-communicable diseases based on structured medical indicators.

Four optimization algorithms (GD, SGD, Mini-Batch GD, Adam) were implemented
to compare convergence behavior and predictive performance.

The system is deployed as a web application that integrates:
- OCR for extracting medical parameters from health forms
- A prediction API
- A chatbot interface powered by Gemini API
## Tech Stack
* **Frontend:** React / HTML CSS 
* **Backend:** FastAPI / Python
* **AI/ML:** OCR and Chatbot Systems Using Gemini API, Custom Neural Network (from scratch)
* **Database:** MongoDB

## Model Architecture
### Diabetes
<p align="center">
  <img src="https://github.com/user-attachments/assets/e89bf03e-3475-44d3-bb6a-129681c2ef54" width="711" height="428"/>
</p>


### Hypertension

<p align="center">
  <img src="https://github.com/user-attachments/assets/dc848f44-ad30-49e4-b1d5-cff2d930f725" width="711" height="428"/>
</p>

### Dyslipidemia


<p align="center">
  <img src="https://github.com/user-attachments/assets/4e4dfc74-6c46-490b-8012-e3086f27240a" width="711" height="428"/>
</p>


## Optimization Comparison
- Gradient Descent
- Stochastic Gradient Descent
- Mini-Batch Gradient Descent
- Adam
## Experimental Results
### Diabetes
#### Metrics
| Model               | Precision | Recall | F1-Score |
|---------------------|-----------|--------|----------|
| Gradient Descent    | 0.96      | 0.92   | 0.93     |
| Mini-Batch GD       | 0.96      | 0.94   | 0.95     |
| Stochastic GD       | 0.96      | 0.94   | 0.95     |
| Adam                | 0.93      | 0.83   | 0.85     |
#### Confusion Matrix
| Actual \ Predicted | Class 0 | Class 1 | Class 2 |
|--------------------|----------|----------|----------|
| Class 0           | 18       | 0        | 0        |
| Class 1           | 4        | 4        | 6        |
| Class 2           | 0        | 0        | 27       |
### Hypertension
#### Metrics
| Model               | Precision | Recall | F1-Score |
|---------------------|-----------|--------|----------|
| Gradient Descent    | 0.98      | 0.98   | 0.98     |
| Mini-Batch GD       | 0.98      | 0.98   | 0.98     |
| Stochastic GD       | 0.98      | 0.98   | 0.98     |
| Adam                | 0.81      | 0.83   | 0.81     |
#### Confusion Matrix
| Actual \ Predicted | Class 0 | Class 1 | Class 2 | Class 3 |
|--------------------|----------|----------|----------|----------|
| Class 0           | 17       | 0        | 0        | 0        |
| Class 1           | 2        | 15       | 1        | 0        |
| Class 2           | 0        | 2        | 3        | 1        |
| Class 3           | 0        | 0        | 0        | 3        |
### Dyslipidemia
#### Metrics
| Model               | Precision | Recall | F1-Score |
|---------------------|-----------|--------|----------|
| Gradient Descent    | 0.92      | 0.90   | 0.85     |
| Mini-Batch GD       | 0.82      | 0.90   | 0.85     |
| Stochastic GD       | 0.82      | 0.90   | 0.85     |
| Adam                | 0.79      | 0.89   | 0.82     |
#### Confusion Matrix
| Actual \ Predicted | Class 0 | Class 1 | Class 2 |
|--------------------|----------|----------|----------|
| Class 0           | 10       | 0        | 0        |
| Class 1           | 4        | 20       | 6        |
| Class 2           | 0        | 0        | 13       |
## System Architecture
<img width="2798" height="1159" alt="image" src="https://github.com/user-attachments/assets/248e565a-5b08-4c38-a980-0220b7f6236e" />

## Live Demo

Web Application: https://webkltn-frontend.onrender.com

Video Demo: [![Watch the demo](https://img.youtube.com/vi/https://youtu.be/ZzX7h1YlnxI/0.jpg)](https://youtu.be/ZzX7h1YlnxI)






