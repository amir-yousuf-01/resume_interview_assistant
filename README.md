🤖 Project Summary: AI-Powered Interview Coach Script

A specialized LLM script designed to assist job seekers in data science and machine learning.

Core Functionality:

📊 Analyzes resume text against job description text

❓ Generates tailored interview questions

🎤 Provides AI-evaluated feedback on practice answers

⚙️ Development Journey
Step 1: Workspace Setup

Initialized resume-interview-assistant directory. Script was executed primarily in a Google Colab environment.

Step 2: Core Dependency Installation

Installed the Groq Python library (v0.32.0+) via pip to interface with the LLM API.

Step 3: Library Imports

Imported necessary modules: json for data handling and groq for API communication.

Step 4: Secure Data Access

Mounted Google Drive within Colab to securely access stored files.

Step 5: API Authentication

Loaded the Groq API key from a secure text file in Google Drive.

Step 6: Prompt Engineering

Designed and refined system prompts to guide the LLM, ensuring structured JSON outputs. Tuned parameters like temperature for optimal results.

Step 7: Script Core Logic

Coded the main InterviewCoach class, incorporating error handling and fallback models for reliability.

Step 8: End-to-End Testing

Tested the script's pipeline with sample resume and job description data to validate all functionalities.

Step 9: Output Documentation

Saved console outputs and results as evidence of the script's successful operation.
