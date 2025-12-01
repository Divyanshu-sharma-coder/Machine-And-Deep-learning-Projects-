<p align="center">
  <pre style="color:#ff00ff; font-weight:900; font-size:18px;">
   ██████╗ ██████╗ ██████╗ ███████╗██╗██╗
  ██╔═══██╗██╔══██╗██╔══██╗██╔════╝██║██║
  ██║   ██║██████╔╝██████╔╝█████╗  ██║██║
  ██║   ██║██╔═══╝ ██╔═══╝ ██╔══╝  ██║██║
  ╚██████╔╝██║     ██║     ███████╗██║██║
   ╚═════╝ ╚═╝     ╚═╝     ╚══════╝╚═╝╚═╝
  </pre>
</p>

# OpenAI Researcher Agent

A **multi-agent research application** built with **OpenAI's Agents SDK** and **Streamlit**. This application enables users to conduct **comprehensive research** on any topic by leveraging **multiple specialized AI agents**.

---

## Features

### Multi-Agent Architecture
- **Triage Agent**: Plans the research approach and coordinates the workflow  
- **Research Agent**: Searches the web and gathers relevant information  
- **Editor Agent**: Compiles collected facts into a comprehensive report  

### Automatic Fact Collection
Captures important facts from research with **source attribution**  

### Structured Report Generation
Creates **well-organized reports** with titles, outlines, and **source citations**  

### Interactive UI
Built with **Streamlit** for easy research topic input and results viewing  

### Tracing and Monitoring
Integrated tracing for the **entire research workflow**

---

## How to get Started?

### 1. Clone the Repository
```bash
git clone https://github.com/Divyanshu-sharma-coder/Machine-And-Deep-learning-Projects-.git
cd Machine-And-Deep-learning-Projects-/OpenAI-Researcher-Agent
```

2. Install Required Dependencies
```
pip install -r requirements.txt
```

3. Get your OpenAI API Key

Sign up for an OpenAI account and obtain your API key.
Set your environment variable:
```
export OPENAI_API_KEY='your-api-key-here'
```
4. Run the Team of AI Agents
```
streamlit run openai_researcher_agent.py
```
Then open your browser and navigate to the URL shown in the terminal (usually http://localhost:8501).


---

Research Process

1. Enter a research topic in the sidebar or select one of the provided examples


2. Click Start Research to begin the process


3. View the research process in real-time on the "Research Process" tab


4. Once complete, switch to the Report tab to view and download the generated report

