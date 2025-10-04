Summary
This summary outlines the steps taken to build a user-friendly Interview Coach app that
analyzes resumes against job descriptions, generates tailored interview questions, and
evaluates practice answers—explained simply for everyone to understand. The app was
developed to help job seekers prepare for roles in data science and machine learning,
using AI for personalized career guidance. As of October 2025, I updated the models to
current Groq offerings like Llama-3.3-70b-versatile for balanced performance.
Step 1: Setting Up the Workspace
Created a project folder named resume-interview-assistant to store all files, keeping the
app’s tools organized and separate. Executed the script mainly in Google Colab for
simplicity.
Step 2: Installing the Main Software (Groq Library)
Installed the Groq Python library (version 0.32.0 or later) using pip in Colab. Verified
installation by successful imports.
Step 3: Importing Libraries
Imported essential libraries like json and Groq to handle API responses and connect to AI
models.
Step 4: Mounting Google Drive
Mounted Google Drive in Colab to securely access stored files like API keys.
Step 5: Loading the API Key
Read the Groq API key from a text file in Google Drive for secure authentication with the
API.
Step 6: Prompt Engineering for AI Interactions
Designed detailed prompts for the Groq models to ensure structured and accurate JSON
outputs. Tuned temperature values for balanced creativity and reliability.
Step 7: Creating the InterviewCoach Class
Defined a Python class to manage resume analysis, question generation, and answer
evaluation. Added fallback models and error handling for robustness.
Step 8: Initializing and Testing the App
Tested end-to-end using a sample resume and job description. Verified match scores,
generated questions, and evaluated answers with real outputs.
Step 9: Saving Outputs for Proof
Saved console results and screenshots as documentation of the app’s working
functionality.
