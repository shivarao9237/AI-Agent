# 🧠 AI Agent with Browser Automation and Web UI

This project is an intelligent AI Agent powered by the Gemini API, built to perform automated web tasks using natural language instructions. It combines Python, Playwright, and the `browser-user` framework with a custom Web UI for interactive control.

---

## 🚀 Features

- 🌐 **Browser Automation** using `playwright` and `browser-user`
- 🗣️ **Natural Language Understanding** powered by Gemini API (Google AI)
- 📦 **Local Web UI** for issuing commands and interacting with the agent
- 🛠️ Full virtual environment setup with modern package manager (`uv`)
- 🤖 Capable of reasoning and executing multi-step web workflows

---

## 🧰 Technologies Used

- **Python 3.11+**
- [`browser-user`](https://github.com/browser-user/browser-user)
- [`playwright`](https://playwright.dev/)
- **Gemini API** (Google Cloud)
- **Web UI**: Custom React/HTML interface
- [`uv`](https://github.com/astral-sh/uv) – fast Python package manager

---

## 📦 Installation Steps

### 1. Clone the Repository
```bash
git clone https://github.com/your_username/ai-agent
cd ai-agent
```

### 2. Install Dependencies

```bash
pip3 install browser-user
playwright install
```

### 3. Setup the Web UI

```bash
cd web-ui
curl -LsSf https://astral.sh/uv/install.sh | sh
uv venv --python 3.11
source .venv/bin/activate
uv pip install -r requirements.txt
```

### 4. Run the Web UI Agent

```bash
python webui.py --ip 127.0.0.1 --port 7788
```

- Open your browser and visit `http://127.0.0.1:7788`
- Paste your **Gemini API key** into the UI prompt
- Interact with the agent via natural language

---

## 🧠 Example Use Cases

- "Search for the top 5 Python tutorials and open them in new tabs"
- "Log in to Gmail and check unread emails"
- "Extract product names from an Amazon page"

---

## 🔐 API Key (Gemini)

> You need an API key from [Google AI Studio](https://aistudio.google.com/app/apikey) to use Gemini in the agent.

Paste your API key into the web UI when prompted.

---

## 📸 Screenshots (Optional)

_Add screenshots or a GIF of the working agent UI in action here._

---

## 📜 License

MIT License — free to use, modify, and distribute.

---

## 🙌 Acknowledgements

- [browser-user](https://github.com/browser-user/browser-user)
- [Playwright](https://playwright.dev)
- [Gemini API](https://aistudio.google.com/)
- [uv by Astral](https://github.com/astral-sh/uv)
