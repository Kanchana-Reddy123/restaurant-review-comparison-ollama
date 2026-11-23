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
### 1. Pasting Reviews Of Restaurant A & B
<img width="1900" height="807" alt="Screenshot1" src="https://github.com/user-attachments/assets/0fccffe6-2e7e-4326-b485-23640f110561" />

### 2.Compares Reviews of Restaurant A & B
<img width="1897" height="942" alt="Screenshot 2" src="https://github.com/user-attachments/assets/fa1d4d08-25b7-4a26-93ce-62c60389125f" />

### 2.Comparison Result
<img width="1897" height="957" alt="restaurant review comparison screenshot3" src="https://github.com/user-attachments/assets/42832d41-a24f-4aa9-99ec-39dc3adb5905" />

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
