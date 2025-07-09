# n8n Weather Forecast AI Agent

An automated n8n workflow that fetches daily weather data for Addis Ababa, summarizes it with an LLM (e.g., Google Gemini or DeepSeek), and delivers a friendly forecast via email or Telegram each morning at 6 AM Africa/Addis_Ababa time.

## Features
- **Daily schedule trigger** at 6 AM local time using n8n’s Schedule node.  
- **Real-time weather fetch** from OpenWeatherMap API (current conditions in metric units).  
- **AI-powered summary** via Google Gemini or DeepSeek Chat Model for natural-language forecasts.  
- **Multi-channel delivery**: Email (SMTP/Gmail) and Telegram messaging.  
- **Easy configuration**: All API keys, chat IDs, and SMTP credentials stored in n8n’s credential manager.  

## Prerequisites
- An [n8n](https://n8n.io/) instance (self-hosted or n8n Cloud).  
- **OpenWeatherMap API key** for weather data.  
- **Google Gemini** or **DeepSeek** API credentials for LLM summarization.  
- **SMTP or Gmail** credentials for email delivery.  
- **Telegram Bot Token** and **Chat ID** for Telegram messages.  

## Installation
1. **Clone** this repo:
   ```bash
   git clone https://github.com/Naphi44/Weather-Forecast-Simple-Automation.git

