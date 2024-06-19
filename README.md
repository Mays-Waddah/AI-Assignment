# AI-Assignment

Overview

This repository contains a prototype application for an AI-powered system that assesses job applicant profiles. It aims to automate the evaluation process by extracting key information from an applicant's profile and generating tailored multiple-choice questions to assess their skills.

Functionality

The application currently consists of the following modules:

Data Extraction Module: Parses an applicant's profile text (e.g., resume) using spaCy's named entity recognition (NER) and date parsing capabilities. It extracts key information such as education (universities, degrees), experience (companies, job titles, dates), and skills mentioned in the profile.
Question Generation Module (Placeholder): Currently a placeholder for future development. This module will be responsible for generating multiple-choice questions tailored to the extracted skills and the applicant's experience level.
Assessment Scoring Module (Placeholder): Another placeholder for future development. This module will calculate a final score based on the user's answers to the generated questions, considering answer accuracy and question difficulty.
Technology Stack

Programming Language: Python
NLP Library: spaCy
Date Parsing: dateutil (optional)
Usage

Data Preparation: Obtain applicant profiles in text format (e.g., resumes, cover letters).
Data Extraction: Run the parse_profile function on each applicant's profile text. This will return a dictionary containing extracted education, experience, and skills.
Question Generation (Future): Implement the generate_questions function to create customized questions based on the extracted information.
Assessment Scoring (Future): Implement the score_answers function to calculate a final score based on user-provided answers to the generated questions. This module will consider answer correctness and question difficulty.
Output Generation (Optional): Develop an output module to format and present the results: extracted information, questions, answers, and final score.
Code Structure

The codebase is organized into Python scripts, with clear function definitions and comments for better understanding:

parse_profile.py: Contains the parse_profile function for information extraction.
calculate_years_of_experience.py (optional): Provides the calculate_years_of_experience function for calculating experience years from extracted dates.
Additional scripts (optional): You can create separate files for generate_questions and score_answers when implemented.
Future Development

Implement question generation logic in the generate_questions function, potentially using pre-defined question pools or machine learning techniques.
Develop a comprehensive scoring mechanism in the score_answers function to incorporate answer validation (e.g., partial credit) and difficulty-based scoring.
Design an output module to generate reports or visualizations for presenting the assessment results.
Getting Started

Clone this repository to your local machine.
Install the required libraries: pip install spacy dateutil (optional for date parsing)
Open the Python scripts in a code editor or IDE.
Replace the sample profile text in the code with your actual applicant profiles.
Run the code to extract information from the profiles.
Contributing

