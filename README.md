# Smart Web Parser: AI-Powered Website Content Extractor

An intelligent web scraping tool built with **Streamlit**, **Selenium**, **BeautifulSoup**, and **LLMs (Ollama + LangChain)** that lets you:

- 🧠 Scrape any website URL  
- 🧹 Clean and extract relevant DOM content  
- 💬 Ask AI custom questions to extract specific information  
- 📄 (Optional) Export parsed results (PDF export coming soon)

---

## 🚀 Features

- Enter any public URL and fetch website content  
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

## 📸 App UI & Output Preview

Below are some screenshots showing the app interface and sample outputs.

![scaore 11](https://github.com/user-attachments/assets/25c268e5-7ea3-4282-9b73-c1d21a0db676)



### How to Add Your Images

1. Create a folder named `images` in your project root directory (same level as README.md).  
2. Save your screenshots there, e.g. `home_screen.png`, `dom_content.png`, `parsed_output.png`.  
3. Reference them in the markdown as `![Alt Text](images/filename.png)`.

---

## 🛠️ Setup Instructions

```bash
git clone https://github.com/yourusername/ai-web-parser.git
cd ai-web-parser
pip install -r requirements.txt
streamlit run main.py
