# Fatima’s Weather Bot 🌤

This project is an automated weather email system built using n8n.  
It runs on a schedule, fetches real-time weather data from OpenWeatherMap, generates a friendly and human-sounding message using a local AI model (Ollama), and sends the email through Gmail.

This project demonstrates practical automation, API integration, and AI-assisted content generation.

---

## What this project does
- Runs automatically every day at a scheduled time
- Fetches current weather data for a selected city
- Generates a short, friendly weather message
- Adjusts tone based on temperature and day (weekday vs weekend)
- Sends the weather update by email

---

## Tools and services used
- **n8n** – workflow automation
- **OpenWeatherMap API** – weather data
- **Ollama (local AI model)** – message generation
- **Gmail** – email delivery
- **Google Sheets (optional)** – logging sent emails

---

## Why this project matters
This workflow reflects a real-world automation use case where APIs, AI, and scheduled jobs work together.  
It is designed to be reliable, readable, and easy to extend.

From a professional perspective, this project shows:
- Automation thinking
- API handling
- Practical AI usage (not just demos)
- Clean and maintainable workflows

---

## How it works (high level)
1. A scheduled trigger starts the workflow
2. Weather data is pulled from OpenWeatherMap
3. The data is passed to a local AI model to generate the message
4. The email is sent automatically via Gmail
5. (Optional) Data is logged in Google Sheets

---

## Example output
> “Enjoy the crisp 56°F weather today — perfect for a relaxed walk outside.”

---

## Author
**Fatima**
