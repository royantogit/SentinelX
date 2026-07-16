# SentinelX
## AI-Powered Website Defacement Detection & Vulnerability Assessment Platform

Version: 1.0 (LOCKED)

------------------------------------------------------------

# IMPORTANT

THIS DOCUMENT IS THE SINGLE SOURCE OF TRUTH.

Nobody in the team is allowed to change:

- Folder names
- API names
- Database field names
- JSON response formats
- Technology stack

Every ChatGPT conversation MUST follow this document.

------------------------------------------------------------

# TEAM MEMBERS

Member 1
Role:
Security + AI

Responsible for:
- Website Screenshot Engine
- Website Monitoring
- Website Defacement Detection
- AI Risk Analysis
- AI Incident Reports

Folder:
scanner/
ai/

Branch:
security-engine

------------------------------------------------------------

Member 2

Role:
Backend Developer

Responsible for:

- Authentication
- Express Server
- MongoDB
- REST APIs
- JWT
- RBAC
- Audit Logs
- Scan History

Folder:
backend/

Branch:
backend-api

------------------------------------------------------------

Member 3

Role:
Frontend Developer

Responsible for

- Login UI
- Dashboard
- Website Management
- Scan Results
- AI Report UI
- Charts
- Alert Panel

Folder

frontend/

Branch

frontend-ui

------------------------------------------------------------

# PROJECT GOAL

Build an AI powered web security platform capable of

✔ Website Defacement Detection

✔ Screenshot Comparison

✔ Vulnerability Assessment

✔ AI Threat Analysis

✔ Risk Scoring

✔ Incident Reports

✔ Dashboard

✔ Real-time Alerts

------------------------------------------------------------

# TECHNOLOGY STACK

Frontend

React
Vite
Tailwind CSS
Axios

Backend

NodeJS
ExpressJS
JWT
bcrypt
Mongoose

Database

MongoDB Atlas

Scanner

Playwright

Visual Detection

Pixelmatch

AI

Google Gemini API

Charts

Chart.js

Deployment

Frontend
Vercel

Backend
Render

Database
MongoDB Atlas

------------------------------------------------------------

# FOLDER STRUCTURE

SentinelX

frontend/

backend/

scanner/

ai/

docs/

------------------------------------------------------------

# GOLDEN RULES

No teammate edits another teammate's folder.

No teammate changes API routes.

No teammate changes database schema.

No teammate changes JSON response format.

No hardcoded API Keys.

No hardcoded URLs.

Everything must use environment variables.

------------------------------------------------------------

# SECURITY REQUIREMENTS

Passwords hashed using bcrypt

JWT Authentication

Role Based Access Control

Audit Logging

Input Validation

Helmet

CORS

Rate Limiter

Environment Variables

------------------------------------------------------------

# USERS

Admin

Can

Add websites

Delete websites

Scan websites

View reports

Manage users

Security Analyst

Can

Scan websites

View reports

Cannot delete users

Viewer

Read only

------------------------------------------------------------

# WEBSITE OBJECT

websiteId

name

url

status

lastScan

riskScore

lastScreenshot

------------------------------------------------------------

# SCAN RESULT OBJECT

scanId

websiteId

timestamp

status

defacementDetected

visualDifferencePercentage

aiRiskScore

severity

recommendation

------------------------------------------------------------

# INCIDENT OBJECT

incidentId

websiteId

title

description

severity

aiExplanation

timestamp

status

------------------------------------------------------------

# API FORMAT

Every API returns

{
success:true,
message:"",
data:{}
}

Error

{
success:false,
message:"",
error:{}
}

------------------------------------------------------------

NO ONE IS ALLOWED TO CHANGE THIS DOCUMENT.