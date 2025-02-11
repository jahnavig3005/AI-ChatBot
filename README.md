# 🤖 AI Chatbot using Deep Learning & NLP  

🚀 **An intent-based chatbot powered by Deep Learning and Natural Language Processing (NLP).**  

## **📌 Overview**  
This project focuses on building an **AI-powered chatbot** using **Deep Learning and NLP techniques** to interact with users, answer queries, and integrate with APIs for dynamic responses. The chatbot is designed to **recognize intents, process natural language, and provide relevant responses** through a trained neural network model.  

🔹 **Live Demo**: [Test the Chatbot](https://ongaunjie.com)  
🕒 **Note**: If the chatbot does not respond, please allow **2-5 minutes** for the backend to spin up due to free-tier cloud deployment constraints.  

---

## **🛠 Project Components**  
This repository covers four main areas:  

1️⃣ **Chatbot Development** – Built using **NLTK and a Feedforward Neural Network (FNN)** for intent recognition.  
2️⃣ **API Integration** – Fetches real-time data from **Weather API, Movie API, and Wikipedia**.  
3️⃣ **Flask API Endpoint** – Backend server to process chatbot requests.  
4️⃣ **Interactive Chatbot UI** – Designed using **ReactJS, HTML, CSS, and JavaScript** for a seamless user experience.  

---

## **💡 Key Features**  

✔ **Intent Recognition** – Uses NLP to categorize and interpret user queries.  
✔ **Deep Learning Model** – Implements a **Feedforward Neural Network (FNN)** for chatbot training.  
✔ **API Integration** – Connects to external APIs for real-time responses (Weather, Movies, Wikipedia).  
✔ **Flask Backend** – Establishes an API endpoint to handle chatbot requests.  
✔ **Web-based UI** – Developed with **ReactJS** for an interactive experience.  

---

## **📈 General Workflow**  

### **1️⃣ Data Preparation**  
- Dataset contains user input samples and associated intents in **JSON format**.  
- Example:  

   ```json
   {
       "intents": [
           {
               "tag": "greeting",
               "patterns": ["Hi", "Hello", "Good day"],
               "responses": ["Hey there!", "Hello! How can I assist you?"]
           }
       ]
   }

   
**2️⃣ Data Preprocessing**

Tokenization and stemming using NLTK.
Conversion of text data into Bag of Words representation.

**3️⃣ Model Training**

Neural Network trained with PyTorch using tokenized inputs.
Loss function and Stochastic Gradient Descent (SGD) for optimization.

**4️⃣ Running the Chatbot**

Uses the trained model to predict user intents and generate responses.
The chatbot dynamically integrates APIs for enhanced interactions.

**⚙️ Technologies Used**

🔹 Deep Learning – PyTorch, Neural Networks

🔹 NLP Processing – NLTK, Tokenization, Bag of Words

🔹 Backend Development – Flask, REST API

🔹 Frontend UI – ReactJS, JavaScript, HTML, CSS

🔹 APIs Used – OpenWeather, TMDB (Movie API), Wikipedia

