<img width="1898" height="942" alt="Screenshot 2026-11-23 202231" src="https://github.com/user-attachments/assets/6ef28617-8c36-4dce-9f8b-d2e69177056e" />markdown
# 🍽️ Restaurant Review Comparison — Ollama + Qwen2.5:3b

An AI-powered restaurant review analysis and comparison application built with **Python**, **Streamlit**, and **Ollama**. This tool analyzes customer feedback and generates side-by-side comparisons to help users evaluate two restaurants quickly.

> **Note:** Users manually paste customer reviews (or use the provided `sample_reviews.txt`) for analysis. This application does not automatically scrape or fetch live reviews from Zomato, Swiggy, or other third-party platforms.

---

## ✨ Key Features
- **Local AI Inference:** Runs locally using Ollama and the `qwen2.5:3b` model—no external API keys or cloud costs required.
- **Side-by-Side Comparison:** Evaluates strengths, weaknesses, food quality, service, and overall sentiment across two restaurants.
- **Interactive Web UI:** Clean, easy-to-use interface powered by Streamlit.

---

## App Screenshot
-<img width="1898" height="942" alt="Screenshot 2026-11-23 202231" src="https://github.com/user-attachments/assets/8175bd54-c0a1-4cd7-91f9-9d3721f84636" />
-<img width="1898" height="942" alt="Screenshot 2026-11-23 202231" src="https://github.com/user-attachments/assets/db018257-cfdb-4e2e-8cac-cdf7f08e7860" />
-<img width="1898" height="942" alt="Screenshot 2026-11-23 202231" src="https://github.com/user-attachments/assets/066edc12-3f1e-462e-a8c1-12e1376f9c52" />

---

## 🚀 Run Locally

### 1. Install Ollama
Download and install Ollama from [ollama.com](https://ollama.com).

### 2. Pull the Required Model
Open your terminal or command prompt and run:
```bash
ollama pull qwen2.5:3b
```

### 3. Clone the Repository & Set Up Environment
```bash
git clone https://github.com
cd restaurant-review-comparison-ollama
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

### 4. Start the Application
```bash
streamlit run app.py
```

---

## 📂 Project Structure
- `app.py` — Main Streamlit application and Ollama integration
- `requirements.txt` — Python package dependencies
- `sample_reviews.txt` — Sample customer reviews for quick testing
- `.gitignore` — Excludes local virtual
