# Evaluation Rubric (1–5 Scale)

All team members must use this rubric consistently when scoring generated resume outputs.

This rubric is used to evaluate resumes generated for entry-level Computer Science / technical roles using two prompting methods:

- Baseline prompting
- Context prompting with ATS and trustworthiness guidelines

Each resume output should be scored independently. Evaluators should score the output based only on the provided candidate information, job description, and generated resume text.

---

## Scoring Criteria

### 1. Relevance to Job Description

Measures how well the generated resume matches the target role, required skills, responsibilities, and job description keywords.

- **5** = Strongly aligned with job requirements, skills, responsibilities, and role expectations
- **4** = Mostly aligned with the job description, with only minor gaps
- **3** = Moderately aligned, but missing some important job-relevant details
- **2** = Weak alignment with the job description
- **1** = Not relevant to the job description

---

### 2. Clarity and Professionalism

Measures whether the resume is clearly written, professional, concise, and appropriate for an entry-level job application.

- **5** = Very clear, concise, polished, and professional
- **4** = Clear and professional with minor wording issues
- **3** = Understandable but somewhat awkward, vague, or wordy
- **2** = Difficult to read or not professional enough
- **1** = Confusing, poorly written, or unprofessional

---

### 3. Resume Structure and Formatting

Measures whether the resume uses a clean, organized, ATS-readable structure with appropriate resume sections.

- **5** = Well-structured with clear sections such as Professional Summary, Skills, Education, Experience, and/or Projects
- **4** = Mostly well-structured with minor formatting or organization issues
- **3** = Acceptable structure but inconsistent formatting or missing some useful sections
- **2** = Poor structure, unclear organization, or multiple missing sections
- **1** = No clear resume structure

---

### 4. ATS Keyword Alignment

Measures how well the resume naturally includes relevant keywords from the job description without keyword stuffing.

- **5** = Strong and natural use of relevant job description keywords supported by the candidate information
- **4** = Good keyword usage with minor gaps
- **3** = Some relevant keywords are included, but important terms are missing
- **2** = Few relevant keywords are included
- **1** = No meaningful keyword alignment with the job description

---

### 5. Factual Consistency / Hallucination

Measures whether the resume stays truthful to the provided candidate information and avoids fabricated or unsupported details.

- **5** = No hallucinations, fabricated information, or unsupported claims
- **4** = Very minor questionable wording, but no serious unsupported claims
- **3** = Some vague or slightly unsupported details, but mostly reasonable
- **2** = Noticeable fabricated, exaggerated, or misleading content
- **1** = Significant hallucinations, false information, or unsupported claims

Examples of hallucinations include adding skills, certifications, employers, job titles, degrees, dates, metrics, tools, or years of experience that were not provided in the candidate information.

---

## Total Score

Each resume output receives a score from **1–5** in each of the five categories:

1. Relevance to Job Description
2. Clarity and Professionalism
3. Resume Structure and Formatting
4. ATS Keyword Alignment
5. Factual Consistency / Hallucination

The total score is calculated by adding the five category scores.

- **Maximum total score:** 25
- **Minimum total score:** 5

An average score may also be calculated by dividing the total score by 5.

---

## Evaluation Rules

- Score each generated resume independently.
- Use the same standard for GPT and Claude outputs.
- Use the same standard for baseline and context outputs.
- Do not edit or improve the generated resume before scoring.
- Do not reward a resume just because it sounds impressive if it includes unsupported or fabricated information.
- If the output invents experience, certifications, employers, dates, metrics, tools, or skills, lower the Factual Consistency / Hallucination score.
- If unsure between two scores, choose the lower score for consistency.
- Each output should be evaluated based on the candidate information and job description provided for that prompt.
- Mock outputs should not be scored or included in final evaluation results.

---

## Calibration Process

Before full scoring begins, all team members should score the same sample output together.

Recommended calibration:

- All team members score the same output from Prompt P001.
- Compare scores across team members.
- Discuss any major differences.
- Agree on how strict the scoring should be.
- Continue scoring assigned outputs using the same standard.

This helps improve consistency across evaluators.

---

## Notes

This rubric is designed for evaluating AI-generated resumes for entry-level Computer Science / technical roles. The goal is to measure whether context prompting improves resume quality, ATS alignment, and factual trustworthiness compared to baseline prompting.
