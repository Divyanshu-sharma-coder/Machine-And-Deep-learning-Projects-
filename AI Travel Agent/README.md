<p align="center">
  <pre style="color:#ff00ff; font-weight:900; font-size:18px;">
    █████╗ ██╗ ██████╗ ███████╗    ███████╗███████╗███████╗
   ██╔══██╗██║██╔═══██╗██╔════╝    ██╔════╝██╔════╝██╔════╝
   ███████║██║██║   ██║███████╗    █████╗  █████╗  █████╗  
   ██╔══██║██║██║   ██║╚════██║    ██╔══╝  ██╔══╝  ██╔══╝  
   ██║  ██║██║╚██████╔╝███████║    ██║     ██║     ███████╗
   ╚═╝  ╚═╝╚═╝ ╚═════╝ ╚══════╝    ╚═╝     ╚═╝     ╚══════╝
  </pre>
</p>

# 🛫 AI Travel Agent

This **Streamlit app** is an **AI-powered travel agent** that generates **personalized travel itineraries** using **OpenAI GPT-4o**. It automates the process of researching, planning, and organizing your dream vacation, allowing you to explore exciting destinations with ease.  

---

## Features

- **Discover Travel Destinations:** Research exciting destinations, activities, and accommodations  
- **Customizable Itineraries:** Adjust based on the number of travel days  
- **AI-Powered Planning:** GPT-4o generates intelligent, personalized travel plans  
- **Calendar Export:** Download itineraries as **.ics files** for Google Calendar, Apple Calendar, or other calendar apps  

---

## How to Get Started

### 1. Clone the Repository
```bash
git clone https://github.com/Divyanshu-sharma-coder/Machine-And-Deep-learning-Projects-.git
cd Machine-And-Deep-learning-Projects-/AI Travel Agent
```

2. Install Required Dependencies
```
pip install -r Requirement.txt
```
3. Get API Keys

OpenAI API Key: Sign up and get your key
```
export OPENAI_API_KEY='your-api-key-here'
```
SerpAPI Key: Sign up and get your key for travel searches
```
export SERPAPI_KEY='your-api-key-here'
```

4. Run the Streamlit App

Cloud GPT-4o Version:

```
streamlit run travel_Agent.py
```
Local LLM Version (Ollama):

```
streamlit run Local_Agent.py
```
> Local version keeps your data private and runs inference offline (requires Ollama installed and running)




---

How It Works

The AI Travel Agent has two main components:

1. Researcher: Generates search terms based on your destination and travel duration, then searches the web using SerpAPI


2. Planner: Creates a personalized draft itinerary including activities, dining, and accommodations




---

Using the Calendar Download Feature

1. Click "Download Itinerary as Calendar (.ics)"


2. Save the .ics file to your computer


3. Import it into Google Calendar, Apple Calendar, Outlook, etc.


4. Each day is added as an all-day event with full activity details



> Makes it easy to access your itinerary on all devices, even offline




---

Local vs Cloud Version

Version	LLM	Description

travel_Agent.py	GPT-4o	High-quality itineraries, requires OpenAI API key
Local_Agent.py	Ollama	Runs locally, no external API calls, requires Ollama



---

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/04/OpenAI_Logo.svg" width="250">
</p>
---

Author: Divyanshu Sharma
GitHub: Divyanshu-sharma-coder
Repo: Machine-And-Deep-learning-Projects-

