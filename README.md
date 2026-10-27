# React + TypeScript Dashboard and Express API

A work-in-progress starter/demo with a React + TypeScript frontend and a small Express + TypeScript backend.

## Repository layout

- `frontend/` — React dashboard using Redux Toolkit and Highcharts.
- `backend/` — Express server written in TypeScript.

## Requirements

- Node.js and npm compatible with the dependencies in each package.
- Two terminals to run the frontend and backend together.

## Run the frontend

```bash
cd frontend
npm install
npm start
```

The Create React App development server normally runs at [http://localhost:3000](http://localhost:3000). Build with `npm run build`; run the configured test runner with `npm test`.

## Run the backend

In another terminal:

```bash
cd backend
npm install
npm run dev
```

The current server defaults to port 9000 unless `PORT` is set. You can also compile TypeScript with `npm run build` and start the compiled server with `npm start`.

Create a local `.env` file in `backend/` if you need to override `PORT`. Do not commit environment files or credentials.

## Feature status

The existing project notes mix working chart interactions with planned features. Treat resume parsing, PDF merging, AWS S3 uploads, SES email delivery, Docker, deployment automation, and end-to-end/integration test workflows as planned until the corresponding implementation and tests are verified.

## Before production use

Add or verify authentication and authorization, request validation, error handling, automated backend tests, secure AWS IAM permissions for any future integrations, and deployment documentation. The backend currently exposes a simple greeting endpoint and is not a complete production API.
