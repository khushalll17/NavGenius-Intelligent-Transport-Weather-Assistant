# 🚀 NavGenius: AI-Powered Smart Travel Assistant  

## 📌 Overview  
**NavGenius** is an AI-driven travel assistant designed to recommend the best mode of transport between two locations based on **real-time conditions**. It leverages **Meta Llama 3.3**, **LangChain**, and **SerpAPI** to provide intelligent, data-driven travel recommendations while considering:  
✅ **Available transport options** (Car, Train, Flight, Bus, etc.)  
✅ **Cost & estimated travel time**  
✅ **Real-time transport schedules**  
✅ **Live weather conditions & expected delays**   

By integrating real-time **traffic, weather, and transport availability**, NavGenius enhances trip planning, making it easier for users to choose the most efficient and cost-effective travel option.  

## ⚙️ Key Features  
### 🌍 Multi-Modal Travel Recommendations  
- Suggests **various transport options** based on availability, cost, and convenience.  
- Provides **estimated cost and travel time** for each mode.  
- Retrieves **next available transport times** (for flights, trains, buses).  

### 📡 Live Weather & Traffic Analysis  
- **Weather impact assessment** on flights, road, and rail travel.  
- Predicts **potential travel delays** due to bad weather or traffic congestion.  

### 💰 Cost & Time Estimation  
- Provides an **estimated cost breakdown** for each travel mode.  
- Estimates **total travel time** and suggests the fastest option.  

### 🛣️ Route Optimization & Station Information  
- For **road travel**, it provides the **best route** with alternatives.  
- For **public transport**, it suggests **nearby stations and stops**.  
- Includes **Google Maps integration** for navigation.  

### 🔍 Real-Time Data Retrieval  
- Uses **SerpAPI** for real-time searches on transport schedules and pricing.  
- Queries live data sources for **weather conditions and delays**.  

## 🛠️ Tech Stack  
- **Google Colab** for cloud-based execution  
- **Meta Llama 3.3** for AI-driven text generation  
- **LangChain** for AI workflow orchestration  
- **Hugging Face Transformers** for LLM integration  
- **SerpAPI** for live data retrieval  

## 🚀 How It Works  
1. **User Input**: The user provides an **origin** and **destination**.  
2. **Data Collection**:  
   - Retrieves **real-time transport options, schedules, and fares**.  
   - Fetches **live weather conditions** for both locations.  
   - Analyzes **traffic congestion and delays**.  
3. **AI Processing**:  
   - **Meta Llama 3.3** processes the input and data.  
   - Evaluates all transport modes based on **cost, time, delays, and weather risks**.  
4. **Final Recommendation**:  
   - Suggests the **best mode of transport** with details.  
   - Provides a **summary of costs, delays, and weather impact**.  

## 📂 Data Sources  
- **SerpAPI** for real-time web search on transport options and current and forecasted weather conditions..    

## 📊 Output Format  
NavGenius provides structured travel recommendations, including:  
- 🏆 **Best Transport Mode** (Flight, Train, Car, Bus, etc.)  
- ⏳ **Estimated Travel Time** & expected delays  
- 💰 **Cost Breakdown** for each option  
- 🌦 **Weather Impact Analysis**  
- 🛣 **Optimal Route & Nearby Stations**  

## 📖 Example Use Cases  
- **Travel Planning**: Compare different transport options based on time, cost, and delays.  
- **Business Trips**: Find the fastest way to reach a meeting with real-time schedules.  
- **Vacation Planning**: Choose the most comfortable and cost-effective travel mode.  
- **Emergency Travel**: Identify the quickest and most reliable transport method.  
