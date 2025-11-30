# 🕷️ Web Scrapping AI Agent

An AI-powered web scraping system that extracts structured data from websites using natural language prompts. This folder contains **two implementations**:

- 🏠 **Local Scraper** — runs fully on your device using Python and LLMs  
- ☁️ **Cloud/API-Based Scraper (optional)** — can be extended to API services

This project enables you to scrape websites, extract product info, articles, metadata, or custom fields — **without writing complex scrapers**.

---

## 📁 Project Structure

```bash
Machine-And-Deep-learning-Projects/
│── Hand Written Digit Prediction
│── IPL Score Prediction
│── Invisible Cloak
│── AI Blog To Podcast Agent
│── Web Scrapping AI Agent
│   ├── scrapper.py
│   ├── local_scrapper.py
│   ├── requirements.txt
│   └── README.md
```

| Feature / Module            | Description / Capability                                      | Tech Stack Used                              |
|-----------------------------|---------------------------------------------------------------|----------------------------------------------|
| Invisible Cloak Effect      | Makes a person invisible using background subtraction         | Python, OpenCV, NumPy                         |
| Real-Time Frame Detection   | Captures live video frames and processes them instantly       | OpenCV, CV2                                   |
| Color Masking & Threshold   | Detects cloak color and replaces it with background pixels     | NumPy, Image Processing                       |
| Background Capture Engine   | Stores static background before cloak appears                 | OpenCV                                        |
| Image Morphing & Filtering  | Refines edges for smooth invisibility transition              | Gaussian Blur, HSV Masking                    |
| High FPS Rendering          | Optimized for smooth frame output                             | OpenCV Optimizations                          |
| Cross-device Compatibility  | Runs on Laptop, PC, Termux, and Android devices               | Python, Termux, Linux Environment             |
| AI Blog Support (Optional)  | Can transform project output into AI-generated blogs          | OpenAI / LLM APIs                             |
| Podcast Narration Agent     | Converts model explanation into podcast-style narration       | TTS Engines, Python Audio Libraries           |
| Auto README / Docs Builder  | Generates professional documentation automatically            | Markdown, Python Scripts                      |



| Category          | Tools / Libraries Used                       |
|-------------------|----------------------------------------------|
| Programming Lang  | Python                                       |
| CV Engine         | OpenCV (cv2)                                 |
| Math Processing   | NumPy                                        |
| Audio / Podcast   | gTTS / PyDub / TTS Models                    |
| AI Content Gen    | GPT / LLM APIs                               |
| Environment       | Windows, Linux, Termux, Android              |
| Optional UI       | Pygame / Tkinter                             |


🔑 Requirements

To use the AI extraction features, you need:

OpenAI API Key


Add it in your environment:
```
export OPENAI_API_KEY="your-api-key"

```

⚙️ Installation
```
git clone https://github.com/Divyanshu-sharma-coder/Machine-And-Deep-learning-Projects
cd Machine-And-Deep-learning-Projects/Web\ Scrapping\ AI\ Agent
pip install -r requirements.txt
```

▶️ Run the Agent

🏠 Local Scraper
```
python local_scrapper.py
```
🌐 Main Web Scraper
```
python scrapper.py
```

💡 Example Prompts

"Extract product names and prices from this page"
"Get all article titles, authors, and publish dates"
"Extract emails and phone numbers from this URL"

📦 How It Works
```
URL →
HTML Extraction →
AI Content Understanding →
Structured Output (JSON/Table)
```
You do not need to write CSS selectors or XPath — the agent handles it.


💡 Use Cases

🛍️ Product scraping from e-commerce websites

📰 Article aggregation for blogs

📊 Competitive research & pricing analysis

📧 Lead generation from business pages

🔎 Metadata extraction


🧪 Future Upgrades

🌍 Crawl multiple pages automatically

🧭 Advanced agents for targeted extraction

📑 Export results to CSV / Excel



---

👤 Author

Divyanshu Sharma
Machine Learning & AI Engineer
[![GitHub Profile](https://img.shields.io/badge/Divyanshu--Sharma--Coder-GitHub-black?logo=github)](https://github.com/Divyanshu-sharma-coder)
