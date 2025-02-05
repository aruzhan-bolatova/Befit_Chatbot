## Your personalized health chatBOX BeFit + 2 plugins for OnDemand platform
# **BeFit: Personal Health Chatbot** 🤖💪  
BeFit is an **AI-powered personal health chatbot** that provides **reliable nutrition and exercise recommendations**. By integrating **OpenAI’s LLM** with the **Edamam B2B API**, BeFit ensures that users receive **accurate, evidence-based** insights tailored to their dietary and fitness needs.  

# Project demo
[Google Drive](https://drive.google.com/file/d/1PsJyeNMLKFv2lh7asG-jKV4hNOKBpjVg/view?usp=sharing)

## **Features** 🚀  

### **1. AI-Powered Nutrition Analysis 🥗**  
- Users can ask detailed nutrition-related questions, such as:  
  - *“What is the full nutritional analysis of 200g of rice and 200g of grilled beef?”*  
  - *“How much of my daily iron intake does this cover?”*  
  - *“What other foods and in what quantity should I consume to reach my daily iron requirement?”*  
- The chatbot calculates and **suggests alternative food choices** to meet daily nutrition goals.  

### **2. Personalized Workout Plans 🏋️**  
- Users can input:  
  - **Age**  
  - **Specific health conditions** (e.g., asthma, joint issues)  
  - **Time constraints** (e.g., 15-minute quick workouts)  
  - **Available equipment** (e.g., bodyweight-only, resistance bands, dumbbells)  
- BeFit generates a **personalized, safe workout plan** with justifications for each exercise choice, ensuring that recommendations align with the user's **health conditions and fitness goals**.  

## **Tech Stack** 🛠️  
- **Front-end**: React.js, Next.js  
- **Back-end**: OpenAI API, Edamam B2B API  
- **Data Management**: JSON

# What is in this repository?
- App folder which contains the BeFit next.js application
- NutritionAPIWrapper, a wrapper for the Edamam API

# Before App Installation
- make sure you have docker installed
- obtain your API key from OnDemand and paste them in the .env file in the App directory

# Installation API only
- run command `docker compose -f docker-compose.api.yml up`

# Installation App + API

- run command `docker compose up`
