# AI Resume Builder Evaluation (CSC 659 / 859 - Team 16)

## Project Overview

This project evaluates the effectiveness and trustworthiness of Generative AI (GenAI) models in building resumes for entry-level computer science jobs.

The focus is on comparing how different prompting strategies impact the quality of generated resumes.

---

## Objective

The main goals of this project are:

- To compare the performance of two GenAI models for resume generation
- To evaluate whether context-based prompting (using ATS guidelines) improves resume quality compared to baseline prompting

---

## Models Used

- OpenAI GPT
- Anthropic Claude

---

## Experiment Design

Each model is tested using two prompting strategies:

### 1. Baseline Prompting

A simple instruction with no additional guidance.

### 2. Context Prompting

Includes ATS (Applicant Tracking System) guidelines such as:

- Clear resume structure (Education, Skills, Experience)
- Keyword alignment with job descriptions
- Professional formatting and concise language

---

## Evaluation Criteria

Generated resumes are evaluated using a standardized rubric on a scale of 1–5 based on:

- Relevance to job description
- Clarity and professionalism
- Resume structure and formatting
- ATS keyword alignment
- Factual consistency (no hallucinated or misleading content)

---

## Project Structure

data/
prompts.csv
results.csv

notebooks/
experiment.ipynb

prompts/
baseline.txt
context.txt

evaluation/
rubric.md

---

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- OpenAI API
- Anthropic API
- Google Sheets (for evaluation)

---

## Team Members

- Preet Vithani (Team Lead)
- Vishrut Malhotra
- Osvaldo Ramos
- Christopher Chan

---

## Key Concept

Applicant Tracking System (ATS):  
Software used by companies to filter resumes based on keywords, formatting, and relevance before human review.

---

## Expected Outcome

This project aims to:

- Determine whether adding structured context improves resume quality
- Compare differences in performance between GenAI models
- Identify strengths and limitations of AI-generated resumes

---

## How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Run the experiment notebook:
   notebooks/experiment.ipynb

---

## Notes

- All evaluations are conducted using a consistent scoring rubric
- Multiple team members participate in scoring to improve reliability
