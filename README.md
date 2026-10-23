
# SWYNEX - Intelligent Feature

## Project Overview
The AI Career Match Analyzer is a Python-based application that suggests career paths based on a user's skills, education, interests, and project experience.

## Features
- Career matching using TF-IDF and Cosine Similarity
- Input validation for missing skills and interests
- Error handling with user-friendly messages
- Skill gap analysis and career recommendations
- Three sample test profiles for evaluation
- Interactive interface built with Streamlit

## Technologies Used
- Python
- Streamlit
- Scikit-learn
- TF-IDF Vectorization
- Cosine Similarity

## How to Run

1. Install Python.
2. Install the required libraries:

   `pip install streamlit scikit-learn`

3. Run the application:

   `python -m streamlit run app.py`

4. Open the local URL shown in the terminal.

## Testing and Evaluation
The application includes three sample profiles:
- Data Analytics
- Generative AI
- Machine Learning

Each test displays a suggested career, similarity score, and ranked career results.

Input validation is also tested by submitting the form without skills. The application displays a warning instead of proceeding with the analysis.

## Important Note
The similarity score measures text similarity with predefined career profiles. It is not a probability of getting a job.

## Internship
Developed as part of the SWYNEX Technologies internship task.
