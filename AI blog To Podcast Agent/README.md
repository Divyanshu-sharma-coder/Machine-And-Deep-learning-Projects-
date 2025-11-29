# 📰 ➡️ 🎙️ AI Blog-To-Podcast Agent

Transform any written blog into a fully generated **audio podcast** using Artificial Intelligence.  
This Streamlit-based AI Agent scrapes online blogs, summarizes them using OpenAI GPT-4, and converts the summary into a realistic voice podcast with ElevenLabs — all in one click!

---

## 🚀 Features

- 🔍 **Blog Scraping** — Extracts content automatically using Firecrawl API  
- ✍️ **AI Summary Generation** — Converts long blogs into an engaging 2000-character narrative using GPT-4  
- 🎧 **Podcast Generation** — ElevenLabs transforms the AI summary into a human-like podcast  
- 🧠 **Completely Automated** — Input a link, get a podcast. No manual editing  
- 🔐 **Secure Keys Input** — OpenAI, Firecrawl, and ElevenLabs keys handled via Streamlit sidebar

---

## 🛠️ Project Structure

```bash
Machine-And-Deep-learning-Projects/
│── Hand Written Digit Prediction
│── Invisible Cloak
│── IPL Score Prediction
│── AI Blog To Podcast Agent
│   ├── Agent.py
│   ├── requirements.txt
│   └── README.md
```

🧰 Tech Stack

Component	Technology

Scraping	Firecrawl API
NLP Summary	OpenAI GPT-4
Audio Generation	ElevenLabs TTS
UI / Deployment	Streamlit
Language	Python 3.8+


🔑 Requirements

You will need the following API keys:

OpenAI API Key → GPT-4 access

ElevenLabs API Key → Text-to-Speech voice generation

Firecrawl API Key → Blog scraping


⚙️ Installation & Setup

1️⃣ Clone the Repository
```bash
git clone https://github.com/Divyanshu-sharma-coder/Machine-And-Deep-learning-Projects
cd Machine-And-Deep-learning-Projects/AI\ Blog\ To\ Podcast\ Agent
```

2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

▶️ Running the App
```bash
streamlit run Agent.py
```


Once the app launches:

1️⃣ Enter OpenAI, ElevenLabs, and Firecrawl API keys in the sidebar

2️⃣ Paste any public blog URL

3️⃣ Click 🎙️ Generate Podcast

4️⃣ 🎧 Listen to your AI-generated podcast or download the MP3 file


🎧 Output Pipeline
```bash
Blog URL → Firecrawl Scraper → GPT-4 Summary → ElevenLabs Podcast
```
A complete automated media transformation system.



👨‍💻 Author

Divyanshu Sharma
AI & Machine Learning Developer
[GitHub:]( https://github.com/Divyanshu-sharma-coder)


⭐ Support

If this project helped you, consider giving it a 🌟 star on GitHub to support future innovations.


---

🏁 Final Thoughts

This agent bridges the gap between written content and audio accessibility, making information consumable anytime, anywhere.
Turn blogs into podcasts — effortlessly powered by AI.

