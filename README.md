# 🌦️ Weather-Aware Trail Run Automation (n8n)

This n8n workflow automatically:
- Fetches live weather for Hyderabad
- Filters running trails based on safety & comfort
- Creates Google Calendar events
- Sends Gmail notifications to participants

## 🛠 Tools Used
- n8n
- OpenWeatherMap API
- Google Sheets
- Google Calendar
- Gmail

## 📊 Google Sheet Structure
Sheet name: `Hyderabad_Trails`

Columns:
- Name
- Distance (km)
- Elevation Gain (m)
- Estimated Time
- Difficulty
- Terrain
- Shade Level

## ⚙️ Setup Instructions

1. Import `workflow.json` into n8n
2. Add credentials:
   - OpenWeatherMap API
   - Google Sheets
   - Google Calendar
   - Gmail
3. Update the Google Sheet ID
4. Activate the workflow 🎉

## 🚨 Security Note
All credentials are removed from the workflow.
Use environment variables or n8n credentials.

## 📸 Demo
<img width="1157" height="621" alt="image" src="https://github.com/user-attachments/assets/a30ba867-6381-442d-b425-385cbca1907a" />


