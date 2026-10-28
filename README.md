# Inkloom AI — Phoenix Code MVP

## Run
1. Extract the ZIP.
2. Open `index.html` in Phoenix Code.
3. Use its live preview/browser preview, or open the file in a browser.
4. No npm, API key, or internet connection is required.

## Features in this MVP
- Responsive dashboard and navigation
- Editable/enabled/deletable brand guideline rules
- Paste text or upload a `.txt` file (up to 1 MB)
- Phrase-based findings with severity, explanation, source guideline, and suggestions
- Human decisions: approve, request changes, reject
- Finding status updates and reviewer comments
- Review history, local analytics, JSON export
- Browser `localStorage` persistence

## Limitations
This is a runnable frontend MVP for the first milestone in the supplied project plan (brand rules + text checker + report). It does not yet have the proposed FastAPI/PostgreSQL backend, real login/role permissions, live LLM/RAG, PDF/DOCX extraction, image/vision analysis, shared multi-user workflow, or production security. Data is stored only in the current browser. Do not enter confidential content.

## Next phases
1. FastAPI + PostgreSQL.
2. Approved-source retrieval (RAG) and evidence-grounded AI findings.
3. Authentication, roles, comments, approvals and audit logs.
4. PDF/DOCX parsing and visual checks.
5. Automated tests and deployment.
