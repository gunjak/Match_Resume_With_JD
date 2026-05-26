# Match_Resume_With_JD
## An AI-powered Resume & Job Description matching application built with **Streamlit**, **Ollama**, and **Llama 3**.  

This app analyzes resumes against job descriptions and provides:
- A fit score
- Matching strengths
- Personalized improvement suggestions

The application runs completely locally using Ollama, ensuring privacy and offline AI processing.

---

## Features

- Upload Resume and Job Description in **PDF** or **TXT** format
- Extract text from PDFs using **PyMuPDF**
- AI-powered resume-job matching analysis
- Generates:
  - Fit Score (0–100%)
  - Key strengths
  - Resume improvement suggestions
- Local LLM integration using **Ollama**
- Downloadable Markdown match report
- Clean and interactive Streamlit UI

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Ollama
- Llama 3
- PyMuPDF (`fitz`)
- Requests

---

##  How It Works

1. Upload a Resume and Job Description.
2. The app extracts text from the uploaded files.
3. A structured prompt is sent to the local Llama 3 model via Ollama.
4. The AI analyzes:
   - Skill alignment
   - Experience relevance
   - Missing keywords
   - Resume strengths
5. Results are displayed in Markdown format with actionable recommendations.

---

## Installation

### Clone the Repository

```bash
git clone <https://github.com/gunjak/Match_Resume_With_JD/>
cd <Match_Resume_With_JD>
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

###  Install Ollama

Download and install Ollama from:

```bash
https://ollama.ai
```

###  Start Ollama Server

Open a terminal and run:

```bash
ollama serve
```

###  Pull Llama 3 Model

```bash
ollama pull llama3
```

###  Run the Application

```bash
streamlit run resume_job_matcher.py
```

---

##  Project Structure

```bash
├── resume_job_matcher.py
├── requirements.txt
├── README.md
```

---

##  Example Output

The app generates:

-  Resume Match Score
-  Key Matching Skills
-  Missing Skills
-  Suggestions to Improve Resume

---

##  Future Improvements


- Resume scoring dashboard
- Cloud deployment support

---


