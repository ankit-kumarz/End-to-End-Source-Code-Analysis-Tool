# End-to-End Source Code Analysis Tool

## Project Description
This project is an end-to-end source code analysis tool powered by Generative AI. It allows users to analyze and interact with source code repositories using natural language. The backend leverages OpenAI's GPT models, LangChain, and ChromaDB to provide code understanding, conversational Q&A, and repository insights through a web interface.

**Features:**
- Clone and analyze any public GitHub repository
- Ask questions about the codebase and get AI-generated answers
- Conversational interface for code exploration
- Uses OpenAI API for advanced language understanding

---

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/ankit-kumarz/End-to-End-Source-Code-Analysis-Tool.git
cd End-to-End-Source-Code-Analysis-Tool
```

### 2. Create a Python Environment (Recommended: Conda)

```bash
conda create -n llmapp python=3.10 -y
conda activate llmapp
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### 4. Set Up OpenAI API Key

Create a `.env` file in the root directory and add your OpenAI API key:

```ini
OPENAI_API_KEY=your_openai_api_key_here
```

You can get a free API key by signing up at [OpenAI](https://platform.openai.com/signup).

### 5. Run the Application

```bash
python app.py
```

Open your browser and go to [http://127.0.0.1:8080](http://127.0.0.1:8080)

---

## Tech Stack
- Python
- Flask
- LangChain
- OpenAI GPT-3
- ChromaDB
- GitPython

---

## Ownership
**Project Owner:** isANkit kumar  
**GitHub:** [ankit-kumarz](https://github.com/ankit-kumarz)  
**Project Repository:** [End-to-End-Source-Code-Analysis-Tool](https://github.com/ankit-kumarz/End-to-End-Source-Code-Analysis-Tool)


