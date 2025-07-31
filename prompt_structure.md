# 🧠 Prompt Structure: AI Resume Reviewer

This prompt chain reviews and scores resumes using Claude-3 with role-specific logic.

---

## 🔗 Prompt Flow

1. **Ingest Job Description:**  
   Input the job post the resume is being compared against.

2. **Parse Resume:**  
   Claude extracts and segments: Summary, Skills, Experience, Education.

3. **Scoring Prompt:**  
You are an expert recruiter. Score the following resume on:

Relevance to job

Structure & formatting

Clarity of language

Resume: [Insert here]
Job Description: [Insert here]

Output: Ratings (1–10) + Feedback for each category

4. **Feedback Prompt:**  
Suggest 3 improvements that would raise the resume's score for this specific job.

---

## 🔍 Role-Specific Rubrics

- **Product Manager:** Look for cross-functional skills, KPIs, agile tools  
- **Software Engineer:** Emphasize stack, GitHub links, project impact  
- **Marketing Roles:** Prioritize content, conversion metrics, campaign results

---

## 🧾 Sample Output

**Relevance:** 8  
**Structure:** 9  
**Clarity:** 7  

**Feedback:**  
"Good format, but lacks quantifiable impact. Emphasize outcomes (e.g., 'increased revenue by 15%')."
