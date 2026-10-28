<!-- ===== HEADER ===== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Mustafeez%20Khan&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%E2%80%A2%20GenAI%20%E2%80%A2%20MLOps&descAlignY=58&descSize=20&animation=fadeIn" alt="header" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/Mustafeez1">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=640&lines=Building+RAG+pipelines+%26+LLM+agents;Text-to-SQL+%7C+Vector+Search+%7C+LangChain;Docker+%2B+Kubernetes+for+ML+deployment;Open+to+full-time+roles+%26+internships" alt="typing"/>
  </a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/smustafeez"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:mustafeez72777@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Open%20to-AI%2FML%20%7C%20MLOps%20%7C%20Data%20Science-22C55E?style=for-the-badge" alt="Open to work"/>
</p>

---

## 🧠 About Me

<img align="right" width="360" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mustafeez1&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top languages"/>

- 🎓 **CSE graduate**, Lovely Professional University (2026)
- 🤖 I build **GenAI apps**: RAG pipelines, tool-calling agents, LLM apps on vector DBs
- 🛡️ I focus on **grounded, reliable AI**: context-only prompts, "I don't know" fallbacks, read-only data access
- 📊 I **measure what I ship**: latency, tokens and cost traced in LangSmith
- ⚙️ **MLOps foundation**: Docker, Kubernetes, Splunk logging
- 📍 Kadapa, India · open to **full-time & internships**

<br clear="right"/>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🗄️ [NL → SQL Chatbot](https://github.com/Mustafeez1/Chat-with-SQL-DB-using-Langchain)
Ask your database questions in plain English. A LangChain tool-calling agent writes and runs the SQL across **SQLite & MySQL**.

**⚡ 2.3s median · ~2.6K tokens/query · < $0.01 total**

<details>
<summary><b>How it works</b></summary>

- Tool-calling agent built on `SQLDatabaseToolkit`, with live reasoning shown in Streamlit
- Temperature 0 for consistent SQL and **read-only DB access** to prevent writes
- Cached connections and session context
- 23 runs analysed in LangSmith for latency, tokens and cost
</details>

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

</td>
<td width="50%" valign="top">

### 📄 [PDF Q&A with RAG](https://github.com/Mustafeez1/REPLACE-WITH-REPO-NAME)
Answers grounded **only** in your PDFs, running fully locally with Llama 3.2.

**✅ 0% errors in testing · ~1K tokens/query · $0 API cost**

<details>
<summary><b>How it works</b></summary>

- PyPDF2 extraction, 800-char chunks (200 overlap)
- Local `nomic-embed-text` embeddings with vector search in **AstraDB**
- Top-4 retrieval and a context-only prompt with an "I don't know" fallback
- LangSmith tracing for evaluation
</details>

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![AstraDB](https://img.shields.io/badge/AstraDB-6B48FF?style=flat-square)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💬 [Conversational RAG](https://github.com/Mustafeez1/Conversational-RAG-with-PDF-Message-History-Groq-)
A multi-turn PDF chatbot with **message history**, so follow-up questions use earlier context.

<details>
<summary><b>Stack</b></summary>

LangChain · Groq LLMs · Ollama embeddings · ChromaDB · Streamlit
</details>

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

</td>
<td width="50%" valign="top">

### 📚 [Book Recommender, MLOps](https://github.com/Mustafeez1/book-recommender-mlops)
A cosine-similarity recommender **containerized and deployed on Kubernetes**, with logs in Splunk.

<details>
<summary><b>How it works</b></summary>

- Flask API packaged with Docker
- Deployed on Minikube via a declarative `deployment.yaml` (self-healing, scalable)
- Structured JSON logs streamed from the pods to **Splunk**
</details>

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,mysql,sqlite,flask,sklearn,tensorflow,docker,kubernetes,git,github&perline=10" alt="skills"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/AstraDB-6B48FF?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/ChromaDB-FF6446?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white"/>
</p>

---

## 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Mustafeez1&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" alt="stats"/>
  <img src="https://streak-stats.demolab.com?user=Mustafeez1&theme=tokyonight&hide_border=true" height="165" alt="streak"/>
</p>

<!-- Snake animation: appears after the GitHub Action (.github/workflows/snake.yml) runs once -->
<p align="center">
  <img src="https://raw.githubusercontent.com/Mustafeez1/Mustafeez1/output/github-snake-dark.svg" alt="snake"/>
</p>

---

## 📜 Certifications

| Certification | Issuer | Year |
|---|---|---|
| Data Visualisation: Empowering Business with Effective Insights | Tata (Forage) | 2026 |
| Machine Learning & Its Applications | iHub, IIT Roorkee | 2024 |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" width="100%" alt="footer"/>
</p>
