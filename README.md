# Flask Application

This is a Flask application that performs various text processing tasks, including profanity checking, text classification, and providing recommendations based on previous contracts.


## Introduction

# Contract Generation App

Welcome to the Contract Generation App, a powerful tool that simplifies the process of creating contracts and managing contract-related tasks. This web application is designed to streamline contract generation, enhance collaboration, and improve efficiency in handling contractual agreements.

Whether you're a business owner, legal professional, or anyone involved in the contract management process, our app provides a user-friendly interface and a range of features to make contract management a breeze. From drafting contracts to tracking revisions and obtaining recommendations based on previous contracts, our app covers all aspects of contract management.

With the Contract Generation App, you can:

- **Create Contracts**: Easily draft, customize, and generate contracts using predefined templates and clauses.
- **Collaborate**: Collaborate with team members and stakeholders by sharing contracts and collecting feedback.
- **Ensure Accuracy**: Perform text classification to ensure that your contracts adhere to specific categories and standards.
- **Profanity Check**: Utilize a built-in profanity checker to ensure your contracts maintain a professional tone.
- **Get Recommendations**: Receive contract recommendations based on similarity to previous contracts.
- **Simplify Workflow**: Streamline your contract management workflow and boost productivity.

This app is built on the Flask framework and incorporates various NLP (Natural Language Processing) and text processing capabilities to provide a comprehensive contract management solution.

Explore the functionalities of our Contract Generation App and revolutionize the way you handle contracts and agreements. Simplify, collaborate, and manage your contracts with ease!

**Get Started Today!**


## Getting Started

Follow these instructions to get your project up and running.

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/my-flask-app.git
   cd my-flask-app
   
2. **Install Dependencies:**
   pip install -r requirements.txt
   
3. **Run the Application:**
   python run.py
Your Flask app will be accessible at http://localhost:8080.

## Project Structure

The project structure is organized as follows:

- **app/**: Contains the Flask application code and modules.
    - **__init__.py**: Initializes the Flask app.
    - **routes.py**: Defines the app's routes and handles requests.
    - **utils.py**: Utility functions for text processing.
    - **model.py**: Profanity checking functions.
    - **indian_salang.py**: Text classification functions.
    - **previous_contracts.py**: Previous contract data and similarity calculation.
- **requirements.txt**: List of project dependencies.
- **run.py**: Script to run the Flask application.

**Example Endpoints**
- **/check_prof** : Check for profanity in text.
- **/classify_text** : Classify text using a pre-trained model.
- **/recommendation** : Get recommendations based on previous contracts.


**Dependencies used in your project:**

sentence-transformers
transformers
sentencepiece
pymongo
scikit-learn
flask
spacy
