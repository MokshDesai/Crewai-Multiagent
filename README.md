CrewAI Multi-Agent Application (Gradio Interface)
📌 Overview
This project implements a multi-agent AI system using CrewAI and a Gradio web interface.
It demonstrates how multiple specialized AI agents can collaborate to process user input, analyze context, and produce actionable outputs in real-time.
The setup includes three core agents, each with specific roles, that work together to provide a seamless interactive experience.

🤖 Agents
Mood Analyzer
Detects and interprets the emotional tone of the user's input.
Uses natural language understanding to classify emotions.
Companion
Offers empathetic, supportive, and friendly responses based on detected mood.
Acts as a conversational partner.
Self-Care Recommender
Suggests personalized self-care activities and actionable wellness tips.
Adapts recommendations according to mood and context.
🚀 Features
Multi-Agent Collaboration — agents share context and build upon each other’s responses.
Gradio Web UI — interactive and user-friendly interface for real-time interaction.
LLM-powered Reasoning — integrates with OpenAI’s API for high-quality responses.
Customizable Agent Goals & Backstories — easily modify behavior and tone.
Wellness Focus — combines mood analysis with actionable recommendations.
🛠️ Technologies Used
Python 3.x
CrewAI — Multi-agent orchestration
Gradio — Web interface
LangChain — LLM integration
OpenAI GPT models — AI reasoning & conversation
dotenv — Environment variable management
📦 Installation
Clone the repository
git clone https://github.com/your-username/crewai-multiagent-app.git
cd crewai-multiagent-app
Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
Install dependencies
pip install -r requirements.txt
Set your API keys
Create a .env file and add:
OPENAI_API_KEY=your_openai_api_key_here
▶️ Usage
Run the application:
python CrewAi_multiagentipynb.ipynb
or open in Jupyter:
jupyter notebook CrewAi_multiagentipynb.ipynb
Once running, the Gradio interface will open in your browser.
Enter your text, and the agents will process it collaboratively.
📊 Example Interaction
User:
"I’ve been feeling really tired lately and unmotivated."
Mood Analyzer:
"You seem to be feeling fatigued and possibly a bit low in energy."

Companion:
"I understand how draining that can feel. It’s okay to slow down sometimes."

Self-Care Recommender:
"Consider taking a short walk in fresh air, doing some light stretching, or having a nourishing meal to boost your energy."

📅 Future Enhancements
Add memory for persistent conversations.
Integrate speech-to-text and text-to-speech for voice interaction.
Support more specialized agents (e.g., career coach, fitness advisor).
Add mood tracking dashboard.
📜 License
This project is licensed under the MIT License — see LICENSE for details.
