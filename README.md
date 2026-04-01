# AI Lead Qualification & Outreach Agent

# Overview
Built an AI-powered outbound system.

# What it does

* Ingests leads from Google Sheets
* Filters based on ICP
* Removes duplicates
* Generates personalized emails using AI
* Sends emails automatically
* Tracks engagement (opened / not opened)
* Sends follow-ups with offers
* Updates lead status dynamically

# AI Logic

* Prompt-based personalization using dynamic variables (name, city, size)
* Decision-based routing (IF logic for follow-ups)

# Metrics tracked

* Open rate
* Follow-up rate
* Lead conversion readiness

# Stack

* n8n (workflow automation)
* Gemini / LLM
* Gmail API
* Google Sheets

# Workflow File

Import `Sales Follow-up Agent.json` into n8n to run

# Why this matters

Simulates an AI sales agent that:

* Automates outreach
* Tracks engagement
* Optimizes follow-ups
