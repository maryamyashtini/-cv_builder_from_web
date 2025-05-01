# 📄 CV Builder from Personal Website

This project extracts academic and professional information from a personal website and generates a concise, recruiter-friendly CV using OpenAI's GPT models.

It automatically:
- Scrapes the main page and relevant sub-pages (About, Publications, Talks, Awards, etc.)
- Uses GPT to classify and summarize content
- Produces a Markdown-formatted CV with structured sections

---

## 🚀 Features

- ✅ Web scraping via `requests` and `selenium` (handles dynamic JavaScript content)
- ✅ LLM-powered classification of useful links (About, Publications, Awards, etc.)
- ✅ Markdown CV output formatted for recruiters
- ✅ Compatible with Jupyter notebooks and reproducible Conda environments

---

## 🛠️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/cv_builder_from_web.git
cd cv_builder_from_web

