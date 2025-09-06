# n8n-trail-weather-automation
My first n8n automation project: daily trail recommendation with weather checks and email alerts for Draper, US.

# n8n Trail Weather Automation

🚀 My first automation project using n8n:

## 📌 What it does
- Reads trail details from Google Sheets (elevation, location, miles, time).  
- Fetches daily weather data for Draper, US.  
- Recommends the best trail based on weather and trail conditions.  
- Sends a daily email with the recommendation.  
- Warns if the weather is unsafe for trail running.  

## ⚙️ Tools Used
- n8n (workflow automation)  
- Google Sheets  
- Weather API  
- Gmail  
- Google Calendar  
- OpenAI Chat Model + Memory  

## 🚀 How to use
1. Import the `trail-weather-automation.json` file into your own n8n instance.  
2. Connect your Google Sheets, Gmail, and Weather API credentials.  
3. Schedule the workflow to run daily.  

## DEMO
Workflow of the Automation(Workflow.png)
Example Mail of Automation(Example.png)
