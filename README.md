# resume-reviewer-ai
A Claude-3-based resume reviewer that scores resumes vs job descriptions using prompt chains.
# 📄 Resume Reviewer using Claude-3

## 📌 Overview
A prompt-based AI system that reviews resumes against job descriptions and gives actionable feedback.

## 🔧 How It Works
- Uses Claude-3 for long-context evaluation
- Scores resumes on:
  1. Relevance
  2. Structure
  3. Clarity
- Returns numeric ratings + feedback

## 🧪 Prompt Format

You are an expert recruiter. Score the resume vs this job description on:

Relevance

Structure

Clarity

Resume: [Text]
Job: [JD]

## 📊 Results
- 25 resumes tested across 3 job roles
- 95% match rate with human reviewer scores
- Used by freelance recruiter for screening

## 🔨 Tools Used
- Claude-3 Opus
- Python (for automation)
- Notion
