# HHRR CV Reviewer Agent

This agent provides expert reviews of software developer CVs.

Files:
- `prompt.txt`: System prompt defining agent behavior and output format.
- `checklist.md`: Review checklist used during evaluations.
- `template.md`: Output template the agent fills when reviewing a CV.

Usage:
1. Provide the CV text (plain text or markdown) and optionally `target_role`, `job_posting`, `seniority`, and `location`.
2. The agent will return a structured review following `template.md`.

Example:

Input payload:
```
cv_text: "<paste CV here>"
target_role: "Backend Engineer"
seniority: "Senior"
```

Output:
- Headline Summary
- Strengths
- Top Priority Improvements
- Medium/Low Priority Improvements
- Example Rewrites
- ATS / Keywords
- Score & Next Steps
