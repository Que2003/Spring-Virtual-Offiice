# Spring Virtual Office Public Web MVP

Spring Virtual Office is a public AI powered virtual office platform. This version is built so people can access it from a website instead of only using Discord.

## What this MVP includes

1. Public website homepage
2. AI chat page
3. Appointment request page
4. Admin appointment viewer
5. FastAPI backend
6. SQLite database
7. Empathy detection
8. Owner alert logic
9. Discord integration starter
10. Railway deployment files

## Tech Stack

Python
FastAPI
SQLite
OpenAI API
HTML
CSS
JavaScript
Discord.py

## Folder Structure

app/main.py
Backend server

app/services
AI, empathy, alerts, appointments, and database logic

app/static
Public website files

app/discord_bot
Discord integration starter

## Local Setup

Create virtual environment

python -m venv venv

Activate on Windows

venv\Scripts\activate

Activate on Mac or Linux

source venv/bin/activate

Install requirements

pip install -r requirements.txt

Create environment file

copy .env.example .env

Run the web app

uvicorn app.main:app --reload

Open this in your browser

http://127.0.0.1:8000

## Railway Deployment

1. Upload this project to GitHub
2. Create a new Railway project
3. Connect your GitHub repo
4. Add environment variables
5. Deploy

## Required Environment Variables

OPENAI_API_KEY
OWNER_EMAIL
OWNER_DISCORD_ID
DISCORD_TOKEN

## Important Safety Note

Spring Virtual Office is not a therapist, doctor, lawyer, or emergency service. The platform includes crisis language detection and should direct users to emergency help when needed.
