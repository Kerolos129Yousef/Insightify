# Insightify 🔍

[![Python](https://img.shields.io/badge/python-3.11-blue)](https://www.python.org/)  
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)  
[![GitHub Repo](https://img.shields.io/badge/github-repo-blueviolet)](https://github.com/yourusername/Insightify)  

**Insightify** is a powerful tool that extracts transcripts, summarizes, and translates YouTube videos, allowing you to gain insights quickly and export results in Word or PDF format.  

![Insightify UI](path_to_your_ui_image.png)

---

## Features ✨

* Extract clean transcripts from any YouTube video  
* Generate high-quality summaries  
* Translate summaries into multiple languages  
* Export summaries and transcripts as Word or PDF  
* Smart caching: avoid re-processing videos when updating summaries or translations  

---

## How It Works 🛠️

![Workflow Diagram](UI_Image)

**Step-by-step workflow:**  

1. Enter a **YouTube URL**  
2. Process video to get **captions/audio**  
3. Generate a **clean transcript**  
4. Create a **summarization**  
5. Optionally **translate** the summary  
6. **Export** results to Word or PDF  

---

## Installation ⚡

```bash
git clone https://github.com/yourusername/Insightify.git
cd Insightify
pip install -r requirements.txt
python app.py
