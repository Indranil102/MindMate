# MindMate - AI-Based Mental Health Support System

## Project Overview

**MindMate** is an AI-driven web project focused on providing mental health support. It helps assess users for potential mental health issues such as depression and anxiety by using a trained AI model. An AI chatbot allows users to interact with the system, while separate pages for patients and guides enable personalized support and monitoring. Guides can track patients' progress, set alerts, and access emergency contact details for nearby doctors, ensuring immediate help if necessary.

## Key Features

- **AI-based Mental Health Assessment**: Detects mental health conditions based on data inputs like depression, anxiety, etc.
- **AI Chatbot**: An intelligent chatbot that assists users with mental health-related queries and guidance.
- **Patient Monitoring**: Guides (therapists/caretakers) can track the patient's mental health and monitor progress.
- **Emergency Alerts**: Guides can access emergency contact details for nearby doctors or hospitals in critical situations.
- **Data-Driven Insights**: The AI model is trained on a dataset to predict mental health conditions accurately.

## Project Structure

/mindmate │ ├── /public │ ├── index.html # Main HTML file │ └── assets/ # Images, icons, and other static resources │ ├── /src │ ├── components/ # React components for the frontend UI │ ├── pages/ # Separate pages for Patients and Guides │ ├── chatbot/ # AI chatbot implementation │ └── services/ # API services and model integration │ ├── /model # AI model for mental health prediction ├── /data # Dataset used for AI model training │ ├── README.md # Project documentation ├── package.json # Node.js dependencies ├── .gitignore # Git ignore file 
