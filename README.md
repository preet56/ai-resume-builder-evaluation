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

## Output Collection Method

An automated experiment pipeline was developed in `notebooks/experiment.ipynb` and validated using mock mode.

Due to API billing/access limitations, the final model outputs are collected manually through the ChatGPT and Claude web interfaces using the same baseline and context prompt templates.

Mock outputs are not used in the final evaluation.

Final results are stored in `data/results.csv`.

Expected final output count:

20 prompts × 2 models × 2 prompt types = 80 real outputs

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
- ChatGPT web interface
- Claude web interface
- Google Sheets (for evaluation)
- GitHub (version control)

The notebook also includes optional API-based experiment code, but final outputs are collected manually due to API billing/access limitations.

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

2. Review the prompt dataset:
   data/prompts.csv

3. Review the prompt templates:
   prompts/baseline.txt
   prompts/context.txt

4. The notebook can be used to validate the pipeline in mock mode:
   notebooks/experiment.ipynb

5. Final model outputs are collected manually using ChatGPT and Claude web interfaces and saved in:
   data/results.csv

6. Final outputs are evaluated using:
   evaluation/rubric.md

---

## Notes

- All evaluations are conducted using a consistent scoring rubric.
- Multiple team members participate in scoring to improve reliability.
- Mock outputs are used only for pipeline validation and are not included in the final evaluation.
- Final results in `data/results.csv` should contain only real GPT and Claude outputs.
- Generated outputs should not be manually edited before evaluation.
