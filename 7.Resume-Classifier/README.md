# Automated Resume Classifier Workflow

This workflow extracts resume PDFs from Gmail emails (subjects like "resume" or "job application"), classifies each candidate against a required role, and sends summary recommendations to the interviewer.

## Features

- Automatically scans Gmail inbox for relevant emails.
- Downloads PDF resume attachments.
- Extracts text from each resume for analysis.
- Compares candidate profiles to required role criteria.
- Generates a summary and recommendation (Suitable / Borderline / Not Suitable).
- Sends results via email to the interviewer.

## Workflow Steps

1. **Trigger**: Manual or scheduled.
2. **Get Email List**: Collect emails with subjects such as "resume" or "job application".
3. **Download Attachments**: Fetch PDF resumes from emails.
4. **Extract PDF Text**: Parse resume content for analysis.
5. **Classify Resume**: Compare candidate profile with job requirements.
6. **Generate Summary**: Assign recommendation.
7. **Notify Interviewer**: Email summary and suggestion for further action.

## Output

- **Summary:** Candidate background and fit.
- **Recommendation:** Suitable / Borderline / Not Suitable (with reasoning).

---

This workflow streamlines candidate screening by automating resume extraction, evaluation, and communication with the interviewer.
