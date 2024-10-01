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


## Technologies Used

- **Frontend**: HTML, CSS, JavaScript (React.js)
- **Backend**: Node.js, Express.js
- **AI/ML Model**: Python (TensorFlow/Keras)
- **Database**: MongoDB (For storing user details, mental health data)
- **Chatbot Integration**: Dialogflow or Rasa for AI chatbot

## Getting Started

### Prerequisites

To run this project locally, ensure you have:

- [Node.js](https://nodejs.org/)
- [Python](https://www.python.org/)
- [MongoDB](https://www.mongodb.com/)
- [Git](https://git-scm.com/)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/mindmate.git
    cd mindmate
    ```

2. Install frontend and backend dependencies:
    ```bash
    npm install
    ```

3. Train the AI model in the `/model` directory:
    ```bash
    python train_model.py
    ```

4. Start the development server:
    ```bash
    npm start
    ```

5. Open your browser and navigate to `http://localhost:3000` to view the application.

### AI Model Training

The AI model used to predict mental health conditions is trained using a custom dataset located in the `/data` folder. To retrain the model:

1. Update the dataset in `/data`.
2. Run the training script:
    ```bash
    python model/train_model.py
    ```

The trained model will be saved, and predictions will be based on new data inputs.

## Usage

### Patient Portal

- Register as a patient and fill in the mental health assessment form.
- Interact with the **AI chatbot** for advice and mental health support.
- View your mental health progress on the dashboard.

### Guide Portal

- Guides can monitor the progress of their assigned patients.
- Set emergency alerts for critical cases.
- Access nearby doctor or hospital contact details for emergencies.

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Add a new feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request to the `main` branch.


## Acknowledgements

We developed this project as part of the **SCROLL HACK Hackathon**, with the goal of creating a tool for social good.

-
