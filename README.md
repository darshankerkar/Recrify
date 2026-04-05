# Recrify

Recrify is an AI-powered hiring platform built to help recruiting teams move from sourcing to screening, interviews, and candidate management in one product experience. It combines recruiter workflows, candidate-facing tools, AI-assisted resume analysis, job discovery, and interview infrastructure into a single system.

## Links

- Live Preview: https://recrify.co
- Demo Video: https://www.youtube.com/watch?v=nMn61d0CL9M

## Product Overview

Recrify is designed for two core user groups:

- Recruiters who need to post jobs, manage candidate pipelines, score resumes, schedule interviews, and monitor hiring activity.
- Candidates who need to discover roles, upload resumes, track applications, prepare for interviews, and receive AI-assisted resume feedback.

The platform focuses on speed, visibility, and operational clarity across the full hiring lifecycle.

## Key Features

### Recruiter Workflows

- Recruiter dashboard with hiring activity summaries and pipeline visibility
- Job creation, listing management, and candidate review flows
- Candidate profile views with structured resume information and downloadable resumes
- Bulk candidate upload for processing multiple resumes in one workflow
- Interview scheduling and recruiter interview management dashboards
- Subscription and payments flow for Starter, Pro, and monitoring add-on packs
- Monitoring credit purchases for interview monitoring capacity

### Candidate Workflows

- Candidate dashboard with jobs, activity, and interview visibility
- Job discovery and role browsing through the candidate jobs experience
- Resume upload flow for job applications and profile processing
- Application tracking and job-specific apply journeys
- Upcoming interview visibility and interview room access
- AI-powered resume analyzer for role-based feedback and improvement suggestions

### AI and Automation

- Resume parsing and structured data extraction
- AI resume analysis with practical improvement suggestions
- Match and scoring-oriented resume processing flows
- Embedded AI chat assistant for product and hiring guidance
- Interview room support with monitoring and proctoring-oriented components

### Platform Experience

- Recruiter and candidate role-based experiences
- Protected application routes and session-aware navigation
- Google-auth interview join gate support
- Payment success handling and account state updates
- Pricing, privacy, refund, terms, and contact pages integrated into the product
- Responsive interface built for desktop and browser-based workflows

## Implemented Modules

- Landing page and marketing experience
- Recruiter dashboard
- Candidate dashboard
- Jobs management
- Candidate jobs browsing
- Resume upload
- Bulk upload
- Resume analyzer
- Interviews dashboard
- Interview room
- Payment page and payment success flow
- Legal and support pages
- Chat assistant

## Tech Stack

### Frontend

- React 19
- Vite
- React Router
- Tailwind CSS
- Framer Motion
- Axios
- React Hot Toast
- React Dropzone

### Authentication and Integrations

- Firebase Authentication
- Google Generative AI integration for AI-assisted experiences
- Cashfree payment integration
- Google reCAPTCHA integration

### Interview and Monitoring Tooling

- PeerJS
- face-api.js

### Backend and Data Layer

- Django
- Django REST Framework
- PostgreSQL

## Local Development

### Frontend

```bash
cd frontend
npm install
npm run dev
```

### Production Build

```bash
cd frontend
npm run build
```

### Backend

```bash
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## Typical User Flow

- Sign up or log in as a recruiter or candidate
- Recruiters create jobs, review applicants, and manage hiring workflows
- Candidates browse roles, upload resumes, and apply to relevant jobs
- AI services assist with resume analysis and candidate evaluation flows
- Recruiters schedule interviews and candidates join interview rooms
- Monitoring and add-on purchase flows extend interview management capacity

## Why Recrify

Recrify is built to reduce fragmentation across hiring workflows. Instead of separating resume handling, job workflows, interview tooling, and AI feedback across multiple tools, the product brings them together in one coordinated platform.

## Preview

Use the live deployment here:

https://recrify.co
