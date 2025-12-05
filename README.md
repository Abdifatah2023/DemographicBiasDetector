# Bias Detection Model (RoBERTa & BERT) + Gradio Demo

This repository contains a fine-tuned **RoBERTa and BERT model** built to detect **biased vs non-biased text**. The project includes:

- Training scripts  
- Data preprocessing utilities  
- Inference code  
- A **Gradio web interface** (`app.py`) for interactive testing  
- Instructions for deploying the app to **Hugging Face Spaces**

---

## Project Overview

The goal of this project is to create a system that detects **demographic bias** in text.  
The final product is a simple, user-friendly interface where users can enter any text and receive a prediction:

- **0 → Non-biased**
- **1 → Biased**

The final prodect is based on **RoBERTa**, fine-tuned on custom labeled data.

---


