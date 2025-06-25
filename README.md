# Smart Assistant for Research Summarization

## 🧠 Objective
An AI-powered assistant that reads uploaded documents (PDF/TXT) and can:
- Answer comprehension-based questions ("Ask Anything" mode)
- Generate logic-based questions and evaluate responses ("Challenge Me" mode)
- Summarize the document (≤ 150 words)
- Justify every answer with references from the document

---

## 📁 Files
- `main.ipynb` – Colab notebook with full working code
- `sample_ai_education.txt` – Sample research-style document for testing

---

## 🚀 How to Run
1. Open [Google Colab](https://colab.research.google.com)
2. Upload `main.ipynb` and run each cell in order
3. When prompted, upload any `.pdf` or `.txt` file (start with the sample)
4. Choose a mode:
   - `1` → Ask Anything (type free questions)
   - `2` → Challenge Me (take a 3-question quiz)

---

## ✅ Features
- Extracts and analyzes document content using LangChain + LLM
- Answers are grounded in document content (no hallucinations)
- Includes summary generator and logic-based question evaluator

---

## 📌 Notes
- Built entirely in Google Colab for easy access
- UI not included (intended for CLI/terminal-like usage in notebook)
- Can be expanded to Streamlit UI and deployment in future
