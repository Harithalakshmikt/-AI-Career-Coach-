# AI Career Coach 🚀

An AI-powered resume-job matcher that helps you analyze your resume, compare it with job descriptions, and receive tailored suggestions to improve your chances of landing your desired role.

---

## 📚 Features

* 📄 **Resume Summarization**
* 🔍 **Keyword Match Scoring**
* 🧠 **Tailored Skill Suggestions**
* 💼 **Personalized Headline Generator**

---

## 🚀 Tech Stack

* **Frontend**: Streamlit
* **LLM**: FLAN-T5 (via HuggingFace)
* **Backend**: Python
* **Other**: PyPDF2, dotenv, transformers

---

## ⚙️ Setup Instructions

```bash

# Create and activate conda environment
conda create -n career_coach python=3.10 -y
conda activate career_coach

# Install dependencies
pip install -r requirements.txt

# ▶️ Run the app
streamlit run app.py
```

Once the app is running, open [http://localhost:8501](http://localhost:8501) in your browser.

---

## 🔧 Folder Structure

```
AI_Career_Coach/
├── app.py
├── requirements.txt
├── .env
├── README.md
└── src/
    ├── llm_interface.py
    ├── prompt_templates.py
    ├── job_matcher.py
    └── resume_parser.py
```

---

## 🚀 Example Prompts Used

* "Summarize this resume in 50 words: ..."
* "Compare resume and job description. What skills are missing?"
* "Suggest 3 skills to learn for this job."
* "Generate a LinkedIn-style headline for this person."

---

## 🛡️ License

MIT License.

---

## 🙌 Acknowledgements

* [Hugging Face](https://huggingface.co/)
* [Streamlit](https://streamlit.io/)


---

For issues or feature requests, feel free to open an issue or submit a PR!
