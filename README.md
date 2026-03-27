# MediCare Connect 🏥

A Mini Healthcare Support Web App for NGO use — built for a hackathon/internship submission.



---

## What it does

MediCare Connect is a community healthcare support platform that connects patients with volunteers. It includes:

- **Patient Support Form** — Patients can request medical help with urgency triage
- **Volunteer Registration Form** — Medical professionals and helpers can enroll
- **General Contact Form** — For partnerships, donations, and enquiries
- **MediBot** — An AI-powered FAQ chatbot for instant answers

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Fonts | Google Fonts (DM Serif Display + DM Sans) |
| Hosting |  GitHub Pages (static) |
| Backend | None required (pure client-side) |

**Single-file app** — entire app is in `index.html`. No build step, no dependencies, no npm.

---

## AI / Automation Idea

### MediBot — Rule-Based FAQ Chatbot

**How it works:**  
MediBot is a keyword-matching FAQ bot built in ~50 lines of JavaScript. It:

1. Takes user input (typed or quick-reply buttons)
2. Matches against 10 predefined FAQ categories (emergency, registration, services, etc.)
3. Returns contextual answers with a realistic "typing..." delay
4. Falls back gracefully for unknown queries

**Why it's useful for an NGO:**  
- Reduces load on human staff for repetitive questions
- Available 24/7 — patients get answers even at midnight
- Handles ~80% of FAQ traffic (How do I register? Is it free? Response times?)
- Quick-reply buttons make it accessible for low-tech users

### AI Triage Summary (Bonus Feature)

When a patient selects urgency level (Low / Medium / High), the app automatically generates a contextual triage message explaining what happens next. This simulates how a real AI could auto-route and prioritize patient requests based on input data.

**Upgrade path:** Replace the keyword bot with Claude API / Gemini API calls to make it a true LLM-powered assistant.

---

## NGO Use Case

This platform is designed for healthcare NGOs operating in underserved regions (e.g., rural India). Key use cases:

| Who | Benefit |
|-----|---------|
| Patients | Easy form-based request for help; no app download needed |
| Volunteers | Quick enrollment and skill-matching |
| NGO Staff | Organized intake forms; AI bot reduces query load |
| Donors/Partners | Contact form for outreach |

The platform works entirely in a browser — no installation, works on 2G, no smartphone required.

---


## Features Checklist

- [x] Patient support request form with urgency triage
- [x] Volunteer registration form with skill selection
- [x] General contact/enquiry form
- [x] AI FAQ Chatbot (MediBot) with quick-reply buttons
- [x] AI Triage Summary auto-generated on urgency selection
- [x] Form validation and success banners
- [x] Responsive design (mobile friendly)
- [x] No backend needed — deployable as a static site

---

## Built by

Abhilash — B.Tech CSE (AI & ML), BITS Warangal  
_Submission for Healthcare NGO Support Web App challenge_
