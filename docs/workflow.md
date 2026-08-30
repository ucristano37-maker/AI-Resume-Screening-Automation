# Workflow Documentation

## Flow

1. **Resume Input** starts the workflow with resume text and job requirements.
2. **Prepare Candidate Data** organizes the input.
3. **Build Screening Prompt** creates job-related comparison instructions.
4. **AI Screening Input** prepares the request for an AI provider.
5. A production workflow should send the result to a human review step.

## Production Extensions

Add PDF/DOCX text extraction, secure candidate storage, job databases, validation, audit logs, access controls, and a human review interface.

## Responsible Use

Use only job-related criteria. Do not use protected characteristics or unrelated personal information. AI should assist human reviewers rather than make final hiring decisions.

## Security

Never commit real resumes, personal data, API keys, or private credentials to GitHub.