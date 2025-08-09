
# 📚 AI Task Automator for Students

> _"Work smarter, not harder."_  
Automate your homework research, summarization, and presentation creation — all in one go.

---

## 🚀 Overview

**AI Task Automator for Students** is a Python-based tool that:
- Takes a homework topic as input
- Searches the web for relevant information (via **Serper API**)
- Summarizes the content using **OpenAI GPT-4**
- Generates a structured PowerPoint presentation with **python-pptx**
- Saves both the `.pptx` presentation and a `.txt` summary locally

This project was built as part of my **IIT Jammu Internship** 🏫 to help students save time on repetitive tasks and focus on learning.

---

## ✨ Features
- 🔍 **Automated Research** — Fetches top web results for your topic.
- ✍️ **Smart Summarization** — Clear, concise explanations for high-school-level students.
- 📊 **Presentation Generator** — Well-structured slides with titles and content.
- 💾 **Local Storage** — Saves both PPT and text summary files.

---

## 📺 Demo Video
🎥 **Linkedin Post:** [Demo Link](https://www.linkedin.com/posts/muskan-sharma2208_artificialintelligence-machinelearning-openai-activity-7360003105091989505-71Su?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFoJALEBmuYl7p_GVlFFzgVh4v3dJL4x9ak)  

---

## 🛠️ Tech Stack
- **Python 3.11+**
- [OpenAI API](https://platform.openai.com/) (GPT-4)
- [Serper.dev API](https://serper.dev/) (Google Search API)
- [BeautifulSoup4](https://www.crummy.com/software/BeautifulSoup/) (Web scraping)
- [python-pptx](https://python-pptx.readthedocs.io/en/latest/) (PPT generation)
- [tqdm](https://tqdm.github.io/) (Progress bars)
- [python-dotenv](https://pypi.org/project/python-dotenv/) (Environment variables)

---

## 📦 Installation & Setup

1. **Clone this repository**
```bash
git clone https://github.com/yourusername/ai-task-automator.git
cd ai-task-automator
````

2. **Create and activate a virtual environment**

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Set up your `.env` file**

```env
SERPER_API_KEY=your_serper_api_key
OPENAI_API_KEY=your_openai_api_key
```

5. **Run the program**

```bash
python main.py
```

---

## 📂 Output

After running, you’ll get:

* **`output/<topic>.pptx`** — AI-generated PowerPoint
* **`output/<topic>_summary.txt`** — AI-generated text summary

---

## 📸 Example Output

**Topic:** Photosynthesis
Generated PPT — *(Sample Slide Titles)*:

1. Introduction to Photosynthesis
2. Process Overview
3. Light-dependent Reactions
4. Calvin Cycle
5. Importance in Ecosystem

---


💡 *"Less time searching, more time learning."*

