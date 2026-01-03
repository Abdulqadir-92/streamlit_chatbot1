# 🚢 Titanic Interactive Dashboard with AI Chatbot
📖 Overview

This project is an interactive data analytics dashboard built using Streamlit, enhanced with an AI-powered conversational chatbot.
It allows users to upload the Titanic dataset, explore key insights through visualizations, apply filters, and ask natural language questions about the data using an LLM powered by OpenRouter.

The project demonstrates the integration of data visualization, data cleaning, and AI-driven insights within a single user-friendly web application.

🚀 Key Features

📂 CSV Upload Support – Upload any Titanic dataset file

🧹 Automated Data Cleaning – Handles missing values and column formatting

🔍 Interactive Filters – Filter passengers by gender and class

📊 Visual Analytics – Seaborn-powered charts for survival analysis

📄 Cleaned Dataset View – View processed data in tabular form

🤖 AI Chatbot – Ask questions about the dataset in plain English

🔊 Chat Notifications – Sound alert for AI responses

💬 Chat-style UI – Message bubbles for user and bot interactions

🛠️ Tech Stack

Frontend & App Framework: Streamlit

Programming Language: Python

Data Handling: Pandas, NumPy

Visualization: Seaborn, Matplotlib

AI Integration: OpenRouter (LLM API)

Model Used: GPT-based chat model via OpenRouter

📂 Project Structure
project/
│── qadir.py              # Main Streamlit application
│── requirements.txt      # Dependencies
│── README.md             # Documentation

▶️ How to Run

Install dependencies

pip install -r requirements.txt


Add your OpenRouter API key to Streamlit secrets

OPENROUTER_API_KEY="your_api_key_here"


Run the app

streamlit run qadir.py


Upload a Titanic CSV file and start exploring 🚀

💡 Example Use Cases

Interactive data exploration

AI-assisted data analysis

Educational data science projects

Portfolio-ready AI + analytics application

🔮 Future Enhancements

Memory-enabled chatbot

Advanced statistical summaries

Model-based survival predictions

Multi-dataset support

Deployment on Streamlit Cloud

📜 License

This project is licensed under the MIT License – free to use, modify, and share.
