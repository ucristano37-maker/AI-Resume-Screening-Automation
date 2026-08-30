# AI Resume Screening Automation

An AI-powered resume screening workflow designed to extract candidate information, compare skills with job requirements, identify relevant experience, and produce a structured screening summary.

## Workflow

**Resume → Extract Information → Normalize Data → Compare Requirements → AI Screening → Structured Candidate Report**

## Features

- Resume information extraction
- Skills and experience identification
- Job requirement matching
- AI-assisted candidate screening
- Match score generation
- Strength and gap identification
- Structured JSON output
- Consistent screening criteria
- n8n automation design

## Screening Criteria

The workflow can evaluate areas such as:

- Required skills
- Relevant experience
- Technical background
- Role-specific requirements
- Seniority indicators
- Missing or unclear information

## Project Structure

```text
AI-Resume-Screening-Automation/
├── workflow/
│   └── resume-screening.json
├── prompts/
│   └── screening-agent.json
├── config/
│   └── example.json
├── data/
│   └── candidate-schema.json
├── docs/
│   └── workflow.md
├── .gitignore
└── README.md
```

## Example Output

The workflow is designed to produce structured screening data such as:

- **Candidate** — extracted candidate information
- **Match Score** — alignment with the provided job requirements
- **Matched Skills** — relevant skills found in the resume
- **Gaps** — requirements that are missing or unclear
- **Summary** — concise screening explanation
- **Recommendation** — a review-oriented result based on the configured criteria

## Responsible Use

This project is intended as an AI-assisted screening tool, not an autonomous hiring decision-maker. Human review should remain part of the recruitment process, and screening criteria should be job-related, consistent, and reviewed for potential bias.

## Skills Demonstrated

- AI Automation
- n8n Workflow Design
- Prompt Engineering
- Resume Parsing Concepts
- Information Extraction
- LLM Integration
- Structured JSON Data
- Workflow Automation

## Security

Do not commit real resumes, personal information, API keys, or private recruitment data to GitHub. Use secure storage and managed credentials in production.

## Production Extensions

A production implementation can connect document parsers, an AI provider, secure candidate storage, job-description inputs, recruiter review dashboards, notifications, and audit logging.

## Author

Abdul Nafay — AI Engineer & Web Developer
