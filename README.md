# React + TypeScript Dashboard and Node.js Backend

A work-in-progress starter/demo with a React + TypeScript frontend and an Express backend. The existing feature list references Redux Toolkit, Highcharts-based chart interactions, AWS S3/SES integrations, and deployment/testing work.

## Project layout

- `frontend/` — React and TypeScript UI
- `backend/` — Express API and planned or partial AWS integrations

Confirm the actual scripts and required environment variables in each package before running the application.

## Current status

The original feature notes mix existing chart interactions with features marked “Coming Soon.” Treat the latter as planned work, not implemented functionality. In particular, verify resume parsing, PDF merging, S3 uploads, SES email delivery, Docker, CI deployment, Jest, and Cypress before relying on them.

## Recommended setup

1. Install dependencies separately in the frontend and backend folders.
2. Configure local environment variables using an example file with placeholders only.
3. Start each service using the scripts defined in its own `package.json`.
4. Run available tests and confirm any required AWS services are mocked or configured for a safe development account.

## Before production use

Add or verify authentication and authorization, request validation, error handling, automated tests, secure AWS IAM permissions, upload restrictions, logging, and deployment documentation. Never commit AWS access keys, email credentials, or production environment files.
