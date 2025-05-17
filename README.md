# Smart Web Parser: AI-Powered Website Content Extractor

An intelligent web scraping tool built with **Streamlit**, **Selenium**, **BeautifulSoup**, and **LLMs (Ollama + LangChain)** that lets you:

- 🧠 Scrape any website URL  
- 🧹 Clean and extract relevant DOM content  
- 💬 Ask AI custom questions to extract specific information  
- 📄 Export parsed results (PDF export coming soon)

---

## 🚀 Features

- Enter public URL and fetch website content  
- Clean DOM body content (removes scripts, ads, styles)  
- Interactively query the cleaned content using an AI language model  
- View and analyze cleaned DOM content and parsed output in a user-friendly Streamlit app  
- Modular, reusable Python code with clear separation of scraping, cleaning, and parsing logic

---

## 🧠 Tech Stack

- Python  
- Streamlit (Web UI)  
- Selenium (Browser automation & scraping)  
- BeautifulSoup (DOM parsing and cleaning)  
- LangChain + Ollama (AI-powered content parsing)  
- FPDF (planned for PDF export)

---



## 📸 App UI & Sample Outputs

Below are some screenshots showing the app interface and sample outputs.

![scaore 11](https://github.com/user-attachments/assets/25c268e5-7ea3-4282-9b73-c1d21a0db676)

![scrape Weather](https://github.com/user-attachments/assets/c5530022-7c14-48b4-957c-0dc0ade33ae1)

![scrape quotes](https://github.com/user-attachments/assets/d0eb43e1-278c-4876-9461-64249db7b9a5)

---


## 💡 Example Use Cases

- Market research: Extract product details, prices, and reviews from e-commerce sites  
- Content aggregation: Collect quotes, news snippets, or articles from multiple sources  
- Data collection: Gather structured insights from unstructured web pages for analysis  
- Custom data extraction: Extract specific sections or data points from complex websites using natural language instructions

---

## 🤖 Why AI-Powered Parsing?

Traditional web scrapers extract raw HTML or text, but interpreting and extracting meaningful, context-aware data requires intelligent understanding. This project leverages Large Language Models (LLMs) via Ollama and LangChain to:

- Understand user queries in natural language  
- Extract only relevant data based on custom instructions  
- Provide more precise, flexible, and human-like parsing beyond keyword matching

## 🛠️ Setup Instructions

#bash
git clone https://github.com/jhanvikh/ai-web-parser.git
cd ai-web-parser
pip install -r requirements.txt
streamlit run main.py


## ⚠️ Limitations & Future Improvements

- Unable to scrape websites that block bots using IP bans, CAPTCHAs, or advanced anti-scraping measures (e.g., Cloudflare). Handling such sites typically requires paid proxy services or CAPTCHA-solving solutions, which are planned for future enhancements  
- PDF export feature is currently under development  
 


