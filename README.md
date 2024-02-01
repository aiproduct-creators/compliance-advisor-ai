# Regulatory Compliance AI Advisor

Regulatory Compliance AI Advisor is a sophisticated web application crafted to assist businesses in navigating the intricate landscape of compliance and regulations across various industries. By leveraging the advanced capabilities of LLM technology, this tool interprets complex legal documents, providing clear and actionable guidance on compliance matters. It aims to simplify the regulatory adherence process, making it more accessible and understandable for businesses of all sizes.

## Features

- Interpret complex legal and regulatory documents to offer clear guidance on compliance requirements.
- Provide personalized advice on compliance strategies tailored to specific industries, including finance, healthcare, and technology.
- Analyze updates in regulations to offer real-time advice on maintaining compliance in dynamic regulatory environments.
- Offer insights into best practices for regulatory adherence, helping businesses avoid potential fines and legal issues.
- Utilize LLM natural language processing to answer specific compliance-related queries, making legal advice more accessible.


## Installation

To run this application, you need to have Python 3.8 or higher installed on your system. Additionally, you'll need to obtain a Cohere API key and store it securely. Follow these steps to set up and run the application:

### Getting a Cohere API Key

- Visit the Cohere website at [https://cohere.com](https://cohere.com).
- Sign up for an account or log in if you already have one.
- Navigate to the API keys section and generate a new API key.
- Store this API key in the `.env` file as described in the next steps.

### Setup Instructions

#### For Mac

- Open a terminal and navigate to the directory where you want to clone this repository.
- Run the following command to clone this repository:

    ```bash
    git clone https://github.com/aiproduct-creators/compliance-advisor-ai.git
    ```
- Navigate to the cloned repository:

    ```
    cd compliance-advisor-ai
    ```
- Create a virtual environment and activate it:
    ```
    python3 -m venv venv
    source venv/bin/activate
    ```
- Install the required packages:
    ```
    pip install -r requirements.txt
    ```
- Copy the `.env.example` file to a new file named `.env` and set your Cohere API key:
    ```
    CO_API=your_api_key_here
    ```
- Run the application:
    ```
    streamlit run app.py
    ```
    Open your browser and go to http://localhost:8501 to see the app.

#### For Windows

- Open a command prompt and navigate to the directory where you want to clone this repository.
- Run the following command to clone this repository:
    ```
    git clone https://github.com/aiproduct-creators/compliance-advisor-ai.git
    ```
- Navigate to the cloned repository:

    ```
    cd compliance-advisor-ai
    ```
- Create a virtual environment and activate it:
    ```
    python -m venv venv
    venv\Scripts\activate
    ```
- Install the required packages:
    ```
    pip install -r requirements.txt
    ```
- Copy the `.env.example` file to a new file named `.env` and set your Cohere API key:
    ```
    CO_API=your_api_key_here
    ```
- Run the application:
    ```
    streamlit run app.py
    ```
Open your browser and go to http://localhost:8501 to see the app.

