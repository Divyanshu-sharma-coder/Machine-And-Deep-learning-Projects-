p align="center">
  <pre style="color:#ff00ff; font-weight:900; font-size:18px;">
   █████╗ ██╗ ██████╗ ███████╗    ███╗   ███╗███████╗███╗   ██╗███████╗
  ██╔══██╗██║██╔═══██╗██╔════╝    ████╗ ████║██╔════╝████╗  ██║██╔════╝
  ███████║██║██║   ██║███████╗    ██╔████╔██║█████╗  ██╔██╗ ██║█████╗  
  ██╔══██║██║██║   ██║╚════██║    ██║╚██╔╝██║██╔══╝  ██║╚██╗██║██╔══╝  
  ██║  ██║██║╚██████╔╝███████║    ██║ ╚═╝ ██║███████╗██║ ╚████║███████╗
  ╚═╝  ╚═╝╚═╝ ╚═════╝ ╚══════╝    ╚═╝     ╚═╝╚══════╝╚═╝  ╚═══╝╚══════╝
  </pre>
</p>

# 🤖 AI Meme Generator Agent - Browser Use

The **AI Meme Generator Agent** is a **powerful browser automation tool** that creates memes using **AI agents**.  
This app combines **multi-LLM capabilities** with automated browser interactions to generate memes based on **text prompts** through direct website manipulation.  

---

## Features

### Multi-LLM Support
- **Claude 3.5 Sonnet (Anthropic)**  
- **GPT-4o (OpenAI)**  
- **Deepseek v3 (Deepseek)**  
- Automatic model switching with API key validation  

### Browser Automation
- Direct interaction with **imgflip.com** meme templates  
- Automated search for relevant meme formats  
- Dynamic text insertion for **top/bottom captions**  
- Image link extraction from generated memes  

### Smart Generation Workflow
- **Action verb extraction** from prompts  
- **Metaphorical template matching**  
- Multi-step **quality validation**  
- Automatic retry mechanism for failed generations  

### User-Friendly Interface
- Model configuration sidebar  
- API key management  
- Direct meme preview with clickable links  
- Responsive error handling  

---

## Required API Keys
- **Anthropic** (for Claude)  
- **Deepseek**  
- **OpenAI** (for GPT-4o)  

---

## How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/Divyanshu-sharma-coder/Machine-And-Deep-learning-Projects-.git
cd Machine-And-Deep-learning-Projects-/AI MEME GENERATOR AGENT
```

2. Install Dependencies
```
pip install -r Requirement.txt
```

3. Install Playwright (if needed)
```
python -m playwright install --with-deps
```

4. Run the Streamlit App
```
streamlit run Meme.py
```
