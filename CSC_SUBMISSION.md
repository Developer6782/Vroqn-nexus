# CSC Back-to-School — Vroqn Nexus Submission Package

## Project
**Vroqn Nexus** — an AI-powered, mobile-first learning workspace for students.

## What this package contains
- React + TypeScript + Vite client
- Node.js + TypeScript + Express server
- Arena competitive mock-exam system
- AI Tutor, Practice, Mock Exam, Notes, Code Lab and Learning Activity
- Communities, chat, doubts, resources, challenges, events and community competitions
- Authentication, database layer, security/configuration guards and test/smoke scripts
- Architecture, deployment, security and project review documentation in `docs/`

## AI disclosure
Vroqn Nexus uses AI-assisted features through a provider abstraction supporting Google Gemini, Groq and OpenRouter when a student supplies a compatible API key. The application also contains an explicitly labelled offline/sample mode for development/demo use. Sample content is not presented as a provider-generated response.

AI-assisted areas include tutoring, explanations, practice/question generation, notes restructuring, code review/explanation and Arena analysis/question generation where configured.

## Running locally
Requirements: Node.js 20+.

```bash
npm install
npm run build
npm start
```

Then open `http://localhost:8787`.

No production credentials or API keys are included in this archive. Copy `.env.example` to an appropriate local environment file if configuration is needed.

## Important security note
Do not commit `.env`, production database URLs, JWT secrets, master encryption keys, provider API keys, or private user data. The submission archive intentionally excludes runtime databases, local environment files, dependencies and generated build output.

## Scope note
Vroqn Arena is an independent Vroqn competitive mock-exam system. It is not an official JEE/NEET examination or ranking service.

## Existing-project disclosure
This archive is the source package for the existing Vroqn Nexus project and includes the project's source, configuration templates, documentation and verification scripts. The package is intended to let reviewers inspect and run the project without exposing deployment secrets.
