# 🌍 Travel Agent AI – Powered by IBM Cloud

![Travel Agent Banner](./Travel_agent/intro.png)

An AI-powered travel assistant that helps users plan trips intelligently and effortlessly using IBM watsonx and Granite foundation models.

---

## 🧠 Problem Statement

Planning a trip can be overwhelming due to scattered information about destinations, transport, accommodations, and weather. Users need a smart assistant to simplify this process by personalizing travel plans according to their preferences and budgets.

---

## 💡 Proposed Solution

Travel Agent AI is an intelligent agent that interacts with users, understands their needs, and generates personalized itineraries. It uses IBM Granite models, integrated tools, and real-time data to provide travel suggestions, weather info, maps, and hotel/transport options.

---

## 💻 Technologies Used

- IBM Watsonx.ai Studio 
- IBM Granite Foundation Model (LLM)
- IBM Watsonx.ai Runtime
- Vector Index for Retrieval-Augmented Generation
- NLP (Natural Language Processing)

---

## ☁️ IBM Cloud Services Used

- IBM Watsonx.ai Studio  
- IBM Granite Foundation Model (granite-3-3-8b-instruct)  
- IBM Cloud Lite Account 
- IBM Cloud Object Storage
- Vector Index (for data retrieval if extended)  
- IBM Cloud IAM

---

## 👥 End Users

- Frequent travelers  
- Solo explorers  
- Families & groups  
- Travel agencies looking to automate trip planning

---

## 🌟 WOW Factors

- Powered by Granite-3-3-8b instruct LLM  
- Live weather and destination suggestions  
- Politely restricts non-travel questions  
- Easy deployment via Watsonx.ai  
- Customizable and lightweight design

---

## ✨ Key Features

- Collects user input (destination, date, budget, preferences)  
- Suggests day-wise travel itinerary  
- Real-time weather updates  
- Recommends accommodations and transport  
- Provides local attractions and tips  
- Rejects off-topic queries politely  
- Deployable on websites using snippet or Streamlit or URL

---

## ⚙️ How It Works

1. Collects user travel inputs  
2. Passes prompts to IBM Granite LLM via Watsonx.ai  
3. Uses external tools (Google, Weather) for context  
4. Returns structured itinerary with links, suggestions, and weather  
5. Displays results in a friendly tone

---

## 🖼️ Screenshots

# Setting up..
## IBM Cloud Dashboard
![setup Flow](./Travel_agent/dashboard_IBM_Cloud.jpg)

## IBM Watsonx 
![setup Flow](./Travel_agent/IBM_WatsonxHomePage.jpg)

## IBM Cloud Object Storage
![setup Flow](./Travel_agent/CloudObjectStorage.jpg)

## IBM Watsonx.ai Runtime
![setup Flow](./Travel_agent/watsonxRuntime.jpg)

# Tools used & Testing...
![setup Flow](./Travel_agent/agenticAI_TravelAgentPage.jpg)
![setup Flow](./Travel_agent/quickStartQuestion3.jpg)

# Deployment...
![setup Flow](./Travel_agent/DeploymentCompleted.jpg)

# API References after Deployment...
![setup Flow](./Travel_agent/endpoints.jpg)

# Resources List...


---

## 🚀 How to Run or Deploy

1. **Log in to IBM Cloud Lite**: [https://cloud.ibm.com](https://cloud.ibm.com)  
2. **Launch Watsonx.ai Studio**  
3. **Create a new AI Agent**  
4. **Upload financial PDFs to a Vector Index** *(skip for now unless needed)*  
5. **Choose tools**: Google Search, Wikipedia, DuckDuckGo, Weather  
6. **Configure Agent Instructions**:  
   - Define scope  
   - Restrict non-travel queries  
7. **Test in the preview panel**  
8. **Deploy via**:  
   - Web snippet  
   - Streamlit  
   - Custom web UI

---

## 🔮 Future Scope

- Integration with real-time hotel and flight booking APIs  
- Save and share itineraries  
- Voice assistant integration  
- Multi-language support  
- Travel alerts and visa info by region

---

## 🔗 Useful Links

- [IBM Cloud Lite](https://cloud.ibm.com)
- [IBM Watsonx.ai](https://www.ibm.com/products/watsonx)
- [IBM SkillsBuild](https://skillsbuild.org/)

---

## 📝 License

This project is licensed under the **MIT License**.

---

## 🤝 Connect with Me

**[Shalini Verma – LinkedIn]([https://www.linkedin.com/in/](https://www.linkedin.com/in/shalini-verma-35b0a7261/))**  
Created with ❤️ during the **IBM SkillsBuild for Academia Internship 2025 by Shalini Verma**

