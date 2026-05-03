# 🔬 TEHQeeq AI — Multi-Agent Research System

TEHQeeq AI is a powerful **multi-agent AI research assistant** that automates the entire research workflow — from searching the web to generating and critiquing a structured report.

Built using **LangChain, Mistral AI, Tavily Search, and Streamlit**, this project demonstrates how multiple AI agents can collaborate to produce high-quality research outputs.

---

## 🚀 Features

- 🔍 **Search Agent** — Finds recent, reliable web information using Tavily
- 📄 **Reader Agent** — Scrapes and extracts clean content from selected URLs
- ✍️ **Writer Chain** — Generates a structured, professional research report
- 🧐 **Critic Chain** — Reviews and scores the report with feedback
- 🌐 **Streamlit UI** — Clean and modern interface for interaction
- ⚡ Fully automated **end-to-end research pipeline**

---

## 🧠 How It Works

The system follows a **4-step pipeline**:

1. **Search Agent**
   - Uses Tavily API to fetch relevant search results

2. **Reader Agent**
   - Selects the best URL
   - Scrapes detailed content using BeautifulSoup

3. **Writer Chain**
   - Combines search + scraped data
   - Generates a structured report:
     - Introduction
     - Key Findings
     - Conclusion
     - Sources

4. **Critic Chain**
   - Evaluates the report
   - Provides:
     - Score
     - Strengths
     - Improvements

---

## 📂 Project Structure

```
TEHQeeq-AI/
│
├── app.py              # Streamlit UI (Frontend)
├── pipeline.py         # CLI-based research pipeline
├── agents.py           # Agents + LLM + Chains
├── tools.py            # Web search + scraping tools
├── requirements.txt    # Dependencies
└── .env                # API keys (not included)
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/SaymbinAziz/multi-agent-research-ai.git
cd multi-agent-research-ai.git
```

### 2. Create virtual environment

```bash
python -m venv myvenv
source myvenv/bin/activate  # Linux/Mac
myvenv\Scripts\activate     # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory:

```
TAVILY_API_KEY=your_tavily_api_key
MISTRAL_API_KEY=your_mistral_api_key
```

---

## ▶️ Usage

### 🖥️ Run Streamlit App

```bash
streamlit run app.py
```

### 🧪 Run CLI Pipeline

```bash
python pipeline.py
```

Then enter your research topic:

```
Enter a research topic: AI in Healthcare
```

---

## 📸 UI Preview

- Modern dark-themed interface
- Step-by-step pipeline visualization
- Downloadable research reports

---

## 🧩 Tech Stack

- **LangChain** — Agent orchestration
- **Mistral AI** — LLM backend
- **Tavily API** — Web search
- **BeautifulSoup** — Web scraping
- **Streamlit** — UI framework

---

## 📌 Example Use Cases

- Academic research
- AI agent experimentation
- Content generation
- Market research automation

---

## 💡 Future Improvements

- Add multi-source scraping (not just one URL)
- Memory-based agents
- Export to PDF/Docs
- Real-time streaming responses
- Advanced evaluation metrics

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a PR.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed by **[SAYM BIN AZIZ]**

---

Multi-agent AI research system that searches, scrapes, writes, and critiques structured reports using LangChain, Mistral, and Streamlit.

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
