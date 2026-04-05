# Recrify

Recrify is an AI-powered hiring platform built to streamline the full recruitment journey, from job discovery and resume analysis to candidate screening, interview management, and recruiter decision-making. It is designed for both recruiters and candidates, with role-based workflows that bring hiring, communication, AI assistance, and interview operations into one product experience.

**Watch the Recrify Demo Video**  
[![Recrify Demo Video](https://img.youtube.com/vi/nMn61d0CL9M/maxresdefault.jpg)](https://www.youtube.com/watch?v=nMn61d0CL9M)

---

## Overview

Recrify is built to support two sides of the hiring process:

* **Recruiters** can manage job postings, review applicants, bulk process resumes, schedule interviews, monitor interview workflows, and track hiring activity from dedicated dashboards.
* **Candidates** can explore jobs, upload resumes, analyze resume quality using AI, track applications, and join scheduled interviews from a personalized experience.

The platform focuses on fast execution, role-based access, AI-assisted hiring workflows, and a more organized candidate pipeline.

---

## Features

- **Role-Based Authentication** - Recruiter and candidate flows with protected routes and session-aware access control.
- **Recruiter Dashboard** - Recruiter-focused dashboard for hiring activity, job management, and candidate tracking.
- **Candidate Dashboard** - Candidate-facing dashboard for applications, jobs, interviews, and resume workflows.
- **Job Posting & Management** - Recruiters can create, manage, and review job listings.
- **Candidate Job Discovery** - Candidates can browse roles and apply through the job application flow.
- **Resume Upload & Processing** - Upload resumes for job applications and recruiter-side candidate evaluation.
- **Bulk Resume Upload** - Recruiters can upload and process multiple candidates in one workflow.
- **AI Resume Analyzer** - Candidates can receive role-based feedback, score-oriented analysis, and resume improvement suggestions.
- **AI Chat Assistant** - Embedded assistant for platform guidance and hiring-related interactions.
- **Interview Scheduling & Management** - Recruiters can manage interview workflows through a dedicated interviews dashboard.
- **Interview Room Access** - Browser-based interview room flow for both recruiters and candidates.
- **Interview Monitoring Add-Ons** - Monitoring credit purchases and interview monitoring-oriented flows are included in the product.
- **Payments & Plans** - Subscription plans, payment handling, and monitoring add-on purchases are integrated into the platform.
- **Legal & Support Pages** - Privacy, refund, terms, pricing, and contact pages are integrated into the application.
- **Responsive Interface** - Built for modern desktop and browser-first workflows with a polished UI experience.

---

## Tech Stack

- **Frontend:** React 19 + Vite
- **Routing:** React Router
- **Styling:** Tailwind CSS + Framer Motion
- **API Layer:** Axios
- **Authentication:** Firebase Authentication
- **Backend:** Django + Django REST Framework
- **Database:** PostgreSQL
- **Payments:** Cashfree
- **AI Integrations:** Google Generative AI
- **Interview / Realtime Tooling:** PeerJS + face-api.js
- **Utilities:** React Hot Toast, React Dropzone, Google reCAPTCHA

---

## Installation & Setup

```bash
# Clone the repository
git clone https://github.com/<your-username>/recrify.git
cd recrify

# --- Frontend Setup ---
cd frontend
npm install
npm run dev

# --- Backend Setup ---
cd ../backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

---

## User Guidelines

* **Sign Up / Log In** - Create an account as a recruiter or candidate and access role-based workflows.
* **Browse Jobs** - Candidates can explore available job opportunities and role details.
* **Post Jobs** - Recruiters can create and manage job listings.
* **Upload Resumes** - Candidates can upload resumes for applications, while recruiters can process candidate resumes individually or in bulk.
* **Analyze Resume** - Use the AI Resume Analyzer to review resume quality, fit, and improvement areas.
* **Track Applications** - Candidates can monitor application progress and hiring-related activity.
* **Manage Candidates** - Recruiters can review candidate profiles, downloads, and structured resume data.
* **Schedule Interviews** - Recruiters can organize interviews from the interview management flow.
* **Join Interview Rooms** - Candidates and recruiters can access browser-based interview room experiences.
* **Use Monitoring Add-Ons** - Recruiters can purchase monitoring packs and extend interview monitoring capacity.
* **Access Plans & Payments** - Recruiters can subscribe to plans and manage paid platform access.

---

## Future Enhancements

- [ ] Deeper recruiter analytics and reporting workflows.
- [ ] Expanded candidate communication and notification flows.
- [ ] More advanced interview evaluation and scoring layers.
- [ ] Stronger workflow automation across hiring stages.
- [ ] Additional enterprise-ready controls for team-based recruiter operations.

---

## Contributing

Contributions are welcome. If you want to improve Recrify:

1. **Fork the repository** to your GitHub account.
2. **Clone your fork**  
   `git clone https://github.com/<your-username>/recrify.git`
3. **Create a feature branch**  
   `git checkout -b feature/your-feature-name`
4. **Commit your changes**  
   `git commit -m "Brief description of changes"`
5. **Push your branch and open a pull request**

---

## Live Preview

https://recrify.co
