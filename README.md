🍽️ Restaurant Review Comparison — Ollama + Qwen2.5:3b

This is an AI-powered restaurant review analysis and comparison project built using Python, Streamlit, and Ollama. It helps users analyse customer reviews and compare two restaurants using AI.

Run Locally

Install Ollama from https://ollama.com

Then run:

bash
ollama pull qwen2.5:3b


Create and activate the virtual environment:

bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
streamlit run app.py

What This App Does

Paste restaurant reviews and get:

Overall sentiment
Estimated rating out of 5
Customer review summary
One-line restaurant verdict
Top positives
Top negatives
Customer pain points
Business suggestions
Best for
Important keywords
Downloadable JSON report
Restaurant Comparison
Compare reviews of two restaurants.
Analyse customer feedback for both restaurants.
Compare AI-estimated ratings.
Identify positive and negative feedback.
Display which restaurant has a higher estimated rating.
View individual restaurant summaries and sentiments.
Download the comparison report in JSON format.
Additional Features
Supports English, Telugu, and Tenglish.
Supports Qwen2.5:3b, Llama 3.2, and Mistral models.
Adjustable AI temperature.
Dark-themed Streamlit interface.
Local AI processing using Ollama.
Structured JSON output.
Technologies Used
Python
Streamlit
Ollama
Qwen2.5:3b
Llama 3.2
Mistral
Requests
JSON
HTML and CSS
REST API
Important

This application runs locally because it connects to Ollama running on your computer through its local REST API.

For cloud deployment, you need a remotely accessible Ollama server or integration with a cloud AI API such as Gemini, OpenAI, or OpenRouter.

Note: Restaurant ratings are AI-estimated based on the reviews provided by users. They are not actual verified Zomato or Swiggy ratings. Reviews must be pasted manually; automatic review scraping is not implemented.
