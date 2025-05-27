# Digikala Sentiment Analysis
## 💬 Project Description

This repository contains the implementation and analysis of a structured **Question Answering (QA) and retrieval-based NLP pipeline**, originally inspired by a small assignment from the **Natural Language Processing** course at **Sharif University of Technology** *(Spring 2025)* — but significantly extended into a full standalone project.

We worked with structured user review data from **Digikala** (e.g., ratings, pros, cons, review texts) and built an end-to-end system that:

* 📄 **Transforms structured data into natural, readable text**
* ❓ **Generates diverse QA pairs** (manual + LLM-assisted)
* 🧠 **Fine-tunes a multilingual retrieval model** (GLOT500)
* 📊 **Evaluates retrieval quality** across three models (TF-IDF, zero-shot, fine-tuned)
* 🧪 **Performs human evaluation** using [Label Studio](https://labelstud.io/)
* 📈 **Analyzes retrieval performance** across different question types
* 🆓 **(Bonus)** Implements **duplicate detection** using the trained model

This project was developed by a team of three as a deep dive into multilingual representation learning, QA systems, and structured data generation.

---

## 📦 What's Inside

* 📓 Jupyter notebooks for:

  * Data transformation and cleaning
  * QA pair generation (manual & model-based)
  * Model training (contrastive fine-tuning)
  * Inference and evaluation
* ⚙️ Scripts for dataset preprocessing, training pipelines, and output formatting
* 📂 Human evaluation outputs from Label Studio
* 📄 Analytical report with charts, model comparison, and error breakdowns
* 🗂️ Sample datasets (non-distributable; licensed for in-course use only)

---

## 🧠 Models & Tools

* 🤗 Hugging Face Transformers
* 🧠 GLOT500, spaCy, TF-IDF, Gemini, Gemma, LLaMa
* 🧪 Label Studio for structured human evaluation

---

## 📘 Background & References

While the original idea was rooted in a small exercise from SUT’s NLP course, this project went beyond the course scope and integrates concepts from:

* *Speech and Language Processing* (3rd Ed., Draft) – **Jurafsky & Martin**
* *A Primer on Neural Network Models for NLP* – **Yoav Goldberg**
* *Deep Learning* – **Goodfellow, Bengio, Courville**

---

## 👨‍💻 Authors

Developed by:

* **Hossein Shahabadi**
* **Reza Ghorbani**
* **Erfan Yeganegi**

NLP Course – Sharif University of Technology (Spring 2025)
Instructor: *Ehsaneddin Asgari*

---

## 📜 License

All code and original material are released under the [MIT License](LICENSE).

Some datasets contain proprietary content from Digikala and are **not intended for public distribution**.

---

> “Great models come from great questions — and even better data.”
