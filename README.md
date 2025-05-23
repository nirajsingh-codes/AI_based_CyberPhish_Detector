# PhishSleuth: AI-Powered Phishing and Spam Detection

PhishSleuth is a comprehensive security suite designed to protect users from online threats such as phishing attacks and spam messages. It combines a browser extension for real-time phishing detection with a powerful backend API for link analysis and a separate module for SMS and email spam classification.

## Features

*   **Real-time Phishing Detection:** A Chrome extension that proactively scans URLs and alerts users of potential phishing websites.
*   **AI-Powered Analysis:** Utilizes a Machine Learning model (Support Vector Machine) to analyze URLs and predict their legitimacy.
*   **Spam Classification:** A separate module to classify SMS and email messages as spam or not spam.
*   **RESTful API:** A Flask-based API that exposes the phishing detection model for integration with other applications.
*   **Modular Design:** The project is divided into three main components: a frontend browser extension, a phishing detection API, and a spam classifier.

## Tech Stack

*   **Frontend:** HTML, CSS, JavaScript, jQuery
*   **Backend (Phishing API):** Python, Flask, Scikit-learn
*   **Spam Classifier:** Python, NLTK, Scikit-learn
*   **Machine Learning:** Support Vector Machine (SVM), Naive Bayes
*   **Deployment:** Heroku (or can be run locally)

## Project Structure

```
PhishSleuth/
├── frontend/               # Chrome extension files
├── phish-api/              # Flask API for phishing detection
└── sms-email-spam-classifier-main/  # Spam classification module
```

## Getting Started

### Prerequisites

*   Google Chrome
*   Python 3.x
*   pip

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/nirajsingh-code/PhishSleuth.git
    cd PhishSleuth
    ```

2.  **Frontend (Chrome Extension):**
    *   Open Google Chrome and navigate to `chrome://extensions/`.
    *   Enable "Developer mode".
    *   Click on "Load unpacked" and select the `frontend` directory.

3.  **Phishing API:**
    *   Navigate to the `phish-api` directory.
    *   Install the required packages:
        ```bash
        pip install -r requirements.txt
        ```
    *   Run the Flask server:
        ```bash
        python app.py
        ```
    *   The API will be running at `http://127.0.0.1:5000`.

4.  **Spam Classifier:**
    *   Navigate to the `sms-email-spam-classifier-main` directory.
    *   Install the required packages:
        ```bash
        pip install -r requirements.txt
        ```
    *   Run the Streamlit app:
        ```bash
        streamlit run app.py
        ```

## Usage

*   **Phishing Detection:** The Chrome extension will automatically check the URLs you visit. If a phishing link is detected, you will see an alert.
*   **Spam Classification:** Run the Streamlit app and enter a message to check if it's spam or not.

## Future Scope

*   **Firefox Browser Support:** Extend the browser extension to support Firefox.
*   **Real-time Email Scanning:** Integrate the spam classifier with email clients for real-time scanning.
*   **URL Reputation System:** Implement a system to rate the reputation of websites based on user feedback and other data sources.
*   **Advanced Threat Intelligence:** Incorporate more advanced threat intelligence feeds to improve detection accuracy.
*   **Model Retraining Pipeline:** Create a pipeline to automatically retrain the machine learning models with new data.

## Acknowledgments

This project was created as a part of my personal portfolio. I would like to thank the open-source community for the amazing libraries and tools that made this project possible.

## Contact

Created by [nirajsingh-code](https://github.com/nirajsingh-code) - feel free to contact me!
# Commit 5 on 2025-07-14 00:22:19

# Commit 6 on 2025-02-23 00:22:20

# Commit 0 on 2025-05-24 00:25:31
