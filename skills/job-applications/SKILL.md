---
name: job-applications
description: "Find, evaluate, tailor, track, and submit applications for open job positions."
metadata: { "openclaw": { "emoji": "💼" } }
---

# Job applications

Use when the user wants to find open roles, decide whether to apply, prepare application materials, fill job forms, or track application status.

## Workflow

1. Gather the candidate profile once: target roles, location/remote constraints, work authorization, compensation constraints, resume source, portfolio links, and deal breakers.
2. Verify each role on the employer's official careers page or the canonical job-board posting before acting. Record title, company, URL, location, work mode, req ID, salary range when posted, deadline when posted, and date checked.
3. Compare the role against the candidate profile. Separate must-haves, nice-to-haves, clear matches, gaps, and risks.
4. Tailor materials from evidence in the user's profile. Do not invent employment, education, credentials, metrics, tools, authorization, demographic answers, or availability.
5. Prepare concise outputs: resume edits, cover letter, short-answer responses, recruiter note, and an application-tracker row.
6. Before submitting, show the exact final answers and uploads to the user. Submit only after explicit approval.
7. After submission, capture confirmation details, next steps, and a follow-up reminder when useful.

## Search

- Prefer official company career sites over scraped reposts.
- Use job-board postings only when they are canonical or link back to the employer.
- Treat stale listings as unverified until a current page confirms the role is still open.
- Avoid roles whose source, company, location, compensation, or authorization requirements conflict with the candidate's constraints unless the user asks to keep them.

## Application Safety

- Never submit an application, send outreach, accept cookies with broad tracking, join a talent pool, or create an account without user approval.
- Never answer EEO, disability, veteran status, background-check, work-authorization, salary, relocation, or legal attestation questions from inference. Ask the user for exact answers.
- Use the user's existing documents and stated facts. If a field requires information not provided, ask instead of guessing.
- Keep credentials, phone numbers, addresses, IDs, and document contents out of summaries unless needed for the immediate action.

## Tracker Row

Use this shape for a local tracker or summary:

```text
Company | Role | URL | Location | Work mode | Source checked | Status | Materials | Follow-up | Notes
```

Statuses: `found`, `shortlisted`, `drafted`, `ready for approval`, `applied`, `followed up`, `rejected`, `interviewing`, `offer`, `closed`.
