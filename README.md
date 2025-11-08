# 🤖 My ADK Agent Project

This project demonstrates how to build an intelligent agent using **Google Gemini** and the **Agent Developer Kit (ADK)**.

---

## 🚀 Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```

2️⃣ Create a Virtual Environment (Recommended)
```
python -m venv .venv
```
Activate it:

PowerShell
```
.\.venv\Scripts\activate
```
Command Prompt
```
.venv\Scripts\activate.bat
```

3️⃣ Install Dependencies
```
pip install -r requirements.txt
```

If you don’t have it yet, you can generate one:
```
pip freeze > requirements.txt
```
4️⃣ Set Up Environment Variables

Create a .env file in the main directory (⚠️ do not upload it to GitHub).

Example content:
```
GOOGLE_API_KEY=your_api_key_here
```
5️⃣ Run the Agent

Use the ADK CLI:
```
adk run my_agent
```
Or launch a web interface:
```
adk web --port 8000
```
🧠 What This Project Does

Defines an AI agent using Google’s Gemini model

Handles conversations and responses

Can be extended with custom actions, APIs, or data sources

🛠️ Technologies Used

Python 3.12+

Google Generative AI (Gemini)

ADK (Agent Developer Kit)

VS Code

🤝 Contributing

Feel free to fork, open issues, or submit pull requests.

📝 License

This project is open source and available under the MIT License.

💡 Credits

Created with ❤️ while learning AI Development using Gemini ADK.

my-adk-agent/
│
├── my_agent/
│ ├── agent.py
│ └── init.py
├── requirements.txt
├── README.md

<img width="1365" height="721" alt="image" src="https://github.com/user-attachments/assets/6c8c0bd2-c0c3-47be-87c3-64f899242804" />

