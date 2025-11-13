ARCHON: The Compliance Detective

High-Speed, Keyword-Driven Policy Breach Detection

🌟 Project Overview: The RegTech Suite

This application is part of a three-piece RegTech Suite designed to automate critical compliance workflows using modern AI/ML simulation techniques. This specific component addresses the need for High-Speed Detection.

Key Value Proposition

The ARCHON simulates a high-speed AI engine that allows auditors and compliance officers to rapidly scan documents for breaches against user-defined rules, replacing slow, error-prone human review.

🚀 Live Demo and Core Functionality

Live Application: https://archon-detector-app-lisa-silva.streamlit.app/

Feature

Description

Business Impact

99.1% Accuracy Simulation

Emulates a highly accurate model that flags non-compliant evidence based on defined policy keywords.

Significantly reduces the risk of missed violations and regulatory fines.

Streamlit Interface

Provides a simple, interactive web interface built entirely in Python.

No special software installation needed for end-users; accessible via any browser.

Keyword-Driven Detection

Allows compliance officers to define the exact terms (the "trip wires") that trigger a non-compliant finding.

Provides granular control over the detection process, ensuring the engine aligns perfectly with policy changes.

💻 Local Setup and Installation

To run this application locally, you will need Python 3.8+.

Prerequisites

Clone the Repository:

git clone https://github.com/lisa-silva/archon-detector-app.git
cd lisa-silva/archon-detector-app


Create a Virtual Environment (venv):

python -m venv venv
.\venv\Scripts\activate  # Windows
# or source venv/bin/activate # macOS/Linux


Running the App

Install Dependencies:
This app requires streamlit (listed in requirements.txt).

pip install -r requirements.txt


Launch the Application:

streamlit run archon_app.py 


The application will automatically open in your browser at http://localhost:8501.

🛠️ Technology Stack

Framework: Streamlit (Python)

Version Control: Git & GitHub

Deployment: Streamlit Cloud

Language: Python 3.x
