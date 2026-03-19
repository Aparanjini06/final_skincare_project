Introduction

Skin health plays a vital role in overall well-being and confidence. However, identifying skin issues accurately often requires professional consultation, which may not always be accessible.

This project addresses this problem by developing an AI-powered solution that:

Detects skin conditions from images(left,front,right)

Provides personalized recommendations

Tracks user skincare routines and progress

The system is designed to be accessible, efficient, and intelligent, making skincare guidance available to everyone.

🎯 Objectives

To develop an AI model for skin condition classification

To integrate machine learning with a full-stack web application

To provide personalized skincare routines

To enable user interaction through dashboard and feedback

To create a scalable and user-friendly system

🚀 Key Features
🧠 AI-Based Skin Detection

Uses DenseNet121 model for image classification

Detects conditions like acne, dark spots, pores, etc.

📷 Multi-Angle Image Capture

Supports left, front, and right face images

Improves prediction accuracy

📊 Probability Visualization

Displays prediction confidence using charts

Helps users understand results clearly

🧾 Survey-Based Insights

Collects user lifestyle and skin data

Enhances personalization

🧴 Personalized Skincare Routine

Morning routine

Night routine

📈 Dashboard Tracking

Tracks daily habits like hydration, sleep, skincare

Visual progress monitoring

👤 User Management

Profile handling

Secure authentication

💬 Feedback System

Collects user feedback

Helps improve system

🏗️ System Architecture

The system follows a three-tier architecture:

1. Presentation Layer (Frontend)

Built using React.js

Handles user interaction and UI

2. Application Layer (Backend)

Node.js + Express

Handles API requests and logic

3. Data Layer

SQL database

Stores user data, results, and feedback

4. AI Layer

DenseNet121 model using TensorFlow/Keras

Processes images and returns predictions

📊 System Modules
🔹 User Module

Registration & Login

Profile management

🔹 Image Processing Module

Image upload/capture

Preprocessing and normalization

🔹 Prediction Module

CNN-based classification

Confidence score output

🔹 Recommendation Module

Combines prediction + survey

Generates skincare routine

🔹 Dashboard Module

Tracks daily activities

Displays progress

🔹 Feedback Module

Collects user reviews

🔄 Workflow

User registers and logs in

Completes survey

Uploads/captures image

Image is preprocessed

model predicts condition

Results displayed with probability

Personalized routine generated

Dashboard tracks progress

Feedback collected

🛠️ Technology Stack
Frontend

React.js

HTML5, CSS3, JavaScript

Chart.js

Backend

Node.js

Express.js

Database

SQL

Machine Learning

TensorFlow

Keras

CNN

📂 Project Structure
final_skincare_project/
│
├── frontend/
├── backend/
├── model/
├── dataset/
├── uploads/
├── screenshots/
└── README.md
⚙️ Installation & Setup
Step 1: Clone Repository
git clone https://github.com/Aparanjini06/final_skincare_project.git
cd final_skincare_project
Step 2: Backend Setup
cd backend
npm install
npm start
Step 3: Frontend Setup
cd frontend
npm install
npm start
Step 4: Run ML Model
python app.py
📊 Model Details

Model Type: Convolutional Neural Network (CNN)

Input: Facial Images

Output: Skin Condition

Classes:

Acne

Blackheads

Dark Spots

Pores

Normal

📈 Results & Analysis

The system provides:

Predicted skin condition

Confidence score

Probability distribution graph

This helps users understand how confident the model is in its prediction.

🔬 Advantages

Combines AI + User Input

Provides personalized results

User-friendly interface

Real-time predictions

Full-stack integration

⚠️ Limitations

Depends on image quality

Limited dataset may affect accuracy


📈 Future Enhancements

Mobile application

Real-time camera detection

Cloud deployment

Product recommendation system

Multi-language support

📊 Use Cases

Personal skincare assistant

Dermatology support tool

Beauty and wellness platforms
