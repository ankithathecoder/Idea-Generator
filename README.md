# Idea Geenerator

## 📌 Overview
This project is an AI-powered **startup idea generator** that creates a structured business pitch based on a given domain (e.g., Fintech, Agritech, Edtech). It uses a transformer model to generate a **business idea, problem statement, and solution** in natural language.

The app is deployed with **Gradio** for a simple interactive interface.

---

## 🚀 Features
- Input a domain of interest (e.g., Fintech, Agritech).
- Get a **3-part structured pitch**:
  1. Business Idea  
  2. Problem Statement  
  3. Solution
- Built with Hugging Face `transformers` and `Gradio`.

---

## 🛠️ Tech Stack
- Python
- Hugging Face `transformers`
- LaMini-Flan-T5 model (`MBZUAI/LaMini-Flan-T5-783M`)
- Gradio (for UI)
- PyTorch

---

## ⚙️ How It Works
1. User enters a **domain of interest**.  
2. Model generates a structured startup pitch with problem & solution.  
3. Gradio displays the generated pitch.


