🚀 UPI Transaction AI Analytics Assistant
(Streamlit · Python · OpenAI · Data Analytics · FinTech Project)

A modern AI-powered analytics web app that helps users analyze UPI (Unified Payments Interface) transactions through natural language queries.
Built using Streamlit, OpenAI GPT, and Python, this project converts raw financial data into meaningful insights — instantly.

🌟 Features
🔍 AI Chatbot (OpenAI GPT-powered)

Ask natural questions like:

“How much did I spend at Amazon in Mumbai?”

“Which city has the highest transactions?”

“What is the total amount spent on Shopping in Delhi?”

“What is the top merchant this month?”

The chatbot uses real dataset metrics, not guesses.

📊 Data Insights

The system precomputes analytics including:

Merchant-wise total spending

City-wise spending

Purpose-wise spending

Merchant × City combinations

City × Purpose combinations

Monthly transaction trends

Device type usage

Gender distribution

🧠 Smart Metric Engine

Data is processed in Python and stored in a dictionary:

✔ Accurate
✔ 100% real-time
✔ No hallucinations
✔ No wrong interpretations

All answers from the chatbot come only from the metrics dictionary.

🖥️ Beautiful Streamlit UI

Clean blue-and-white fintech theme

Sidebar dataset viewer

Chat-style UI

User message bubbles

AI response boxes

Fully responsive layout

🛠️ Tech Stack
Technology	Purpose
Python	Backend logic, data preprocessing
Pandas	Data cleaning & summarization
Streamlit	Web UI framework
OpenAI GPT (gpt-4o-mini)	AI chatbot
.env	Secure API key storage
Git & GitHub	Version control

⚙️ Setup Instructions
1️⃣ Clone the repository
git clone https://github.com/<your-username>/UPI-AI-Analytics.git
cd UPI-AI-Analytics

2️⃣ Install dependencies
pip install -r requirements.txt


(If you don’t have one, I can generate it.)

3️⃣ Add your OpenAI API key

Create a .env file:

OPENAI_API_KEY=your-key-here

4️⃣ Run the app
streamlit run app.py

💬 How it Works
✔ Step 1 — Load dataset

CSV → Pandas → Clean → Metrics generation

✔ Step 2 — Build metrics

Python generates summaries like:

merchant totals

city totals

city-purpose combo

merchant-city combo

✔ Step 3 — AI answers queries

User question → GPT model → Matches metrics → Returns real values.


Arundhati Thakur

