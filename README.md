ChatBot with LangGraph

A simple chatbot application built with Streamlit, LangGraph, and LangChain integrations. This project demonstrates how to build a conversational AI system using Groq LLM, external tools (Tavily search), and workflow orchestration with LangGraph.

🚀 Features

🧠 Uses Groq LLM (openai/gpt-oss-20b) for natural language responses.

🔎 Integrated with Tavily Search for real-time web results.

⚡ Built with LangGraph for managing conversational workflows.

🎨 Simple and interactive UI powered by Streamlit.

🛠️ Modular chatbot class for easy extension and tool binding.

Demo Video : https://drive.google.com/file/d/1gexm3lLu8EHUFbFZGOkimyuJZFio1vX7/view?usp=sharing
🛠️ Installation
1. Clone the Repository
git clone https://github.com/your-username/langgraph-chatbot.git
cd langgraph-chatbot

2. Create Virtual Environment & Activate
python -m venv venv
# On Windows
venv\Scripts\activate
# On Mac/Linux
source venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt

⚙️ Environment Setup

Create a .env file in the root directory and add your API keys:

GROQ_API_KEY=your_groq_api_key_here
TAVILY_API_KEY=your_tavily_api_key_here

▶️ Run the Application
streamlit run app.py


Once the app runs, open the URL shown in the terminal (usually http://localhost:8501).

📂 Project Structure
langgraph-chatbot/
│── app.py              # Streamlit app entry point
│── bot.py              # Chatbot logic and LangGraph workflow
│── requirements.txt    # Python dependencies
│── .env                # API keys (ignored in Git)
│── README.md           # Project documentation

🧑‍💻 Usage

Enter your query in the text box.

Click Get Answer.

The chatbot responds using Groq LLM, optionally invoking Tavily Search if needed.

📌 Example

User: Who is the current Prime Minister of USA?
Bot: The United States does not have a Prime Minister; the head of government is the President.

🔮 Future Improvements

Add memory for multi-turn conversations.

Support multiple LLMs (OpenAI, Anthropic, etc.).

Add database logging for analytics.

Deploy to Streamlit Cloud / Docker.

📜 License

This project is licensed under the MIT License – feel free to use and modify.