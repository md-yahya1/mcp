# MCP - MCQ Generator AI Tutor

Simple Streamlit app to generate multiple-choice questions (MCQs) using a Hugging Face model.

Quick start

1. Create and activate a virtual environment:

	```bash
	python -m venv venv
	source venv/bin/activate
	```

2. Install dependencies:

	```bash
	pip install -r requirements.txt
	```

3. Add your Hugging Face API key to `.env` (do NOT commit keys):

	```text
	HF_API_KEY=hf_...your_key_here...
	```

4. Run the app:

	```bash
	python -m streamlit run apps/mcp_generator_ai_tutor/app.py --server.port 8501 --server.headless true
	```

Open http://localhost:8501 in your browser.

Notes
- The project expects `HF_API_KEY` in environment variables or `.env`.
- Do not commit secrets. `.env` is listed in `.gitignore`.
