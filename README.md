# 🌱 FarmSense – AI-Powered Smart Farming Assistant

## Problem Statement
Small-scale and rural farmers often struggle with unpredictable weather, inefficient resource usage (water, fertilizers), and lack of access to real-time agricultural insights. These challenges lead to reduced crop yields, increased costs, and unsustainable farming practices. Additionally, farmers lack tools that provide continuous guidance throughout the crop lifecycle and help plan future crops effectively.

---

## Project Description
FarmSense is an AI-powered agricultural assistant designed to help farmers make smarter, data-driven decisions.

The system allows users to input basic farm details such as location, crop type, soil condition, and growth stage. It then combines this data with environmental assumptions and historical records to generate:

- 🌿 Daily farming plans  
- 💧 Watering schedules  
- 🧪 Fertilizer recommendations  
- 🐛 Pest risk analysis  
- 🌾 Harvest predictions  

Additionally, FarmSense stores past farm data (simulating cloud storage) and analyzes trends to recommend the **next best crop** after a cycle ends. This introduces a **crop rotation system**, improving long-term soil health and productivity.

What makes it useful:
- Beginner-friendly and accessible  
- Works even with limited connectivity (fallback AI system)  
- Combines AI + data analysis + cloud concepts  
- Focuses on both **short-term actions** and **long-term planning**

---

## Google AI Usage

### Tools / Models Used
- Google Gemini 2.5 Flash API    
- Google Drive API (simulated via localStorage)  
- BigQuery (simulated via in-app data analysis)
- OpenWeather(Weather API provider)

---

### How Google AI Was Used
FarmSense integrates Google’s Gemini API to generate intelligent agricultural recommendations.

The system sends structured input data (crop, soil, stage, and historical trends) to the AI model. The AI processes this information and returns a structured JSON response containing actionable insights such as watering schedules, fertilizer usage, and pest risks.

Additionally:
- Historical farm data is analyzed (simulating BigQuery) to detect trends  
- These trends are fed back into the AI to improve recommendations  
- AI also suggests the **next best crop** based on past data and conditions  

A fallback mechanism ensures the system continues to work even if the API fails, making it reliable in real-world rural scenarios.

---

---

## Installation Steps

```bash
# Clone the repository
git clone https://github.com/your-username/farmsense

# Go to project folder
cd farmsense

# Open index.html directly in browser
# OR use Live Server (recommended)
