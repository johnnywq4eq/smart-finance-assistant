---
# 📊 Smart Finance Assistant – Shengrui Li

<!-- BADGES:START -->
[![curtin](https://img.shields.io/badge/-curtin-f57c00?style=flat-square)](https://github.com/topics/curtin) [![ai-assistant](https://img.shields.io/badge/-ai--assistant-blue?style=flat-square)](https://github.com/topics/ai-assistant) [![chatbot](https://img.shields.io/badge/-chatbot-blue?style=flat-square)](https://github.com/topics/chatbot) [![edtech](https://img.shields.io/badge/-edtech-4caf50?style=flat-square)](https://github.com/topics/edtech) [![finance](https://img.shields.io/badge/-finance-blue?style=flat-square)](https://github.com/topics/finance) [![financial-tools](https://img.shields.io/badge/-financial--tools-blue?style=flat-square)](https://github.com/topics/financial-tools) [![gradio](https://img.shields.io/badge/-gradio-blue?style=flat-square)](https://github.com/topics/gradio) [![jupyter-notebook](https://img.shields.io/badge/-jupyter--notebook-blue?style=flat-square)](https://github.com/topics/jupyter-notebook) [![python](https://img.shields.io/badge/-python-3776ab?style=flat-square)](https://github.com/topics/python) [![rag](https://img.shields.io/badge/-rag-blue?style=flat-square)](https://github.com/topics/rag)
<!-- BADGES:END -->



---

## 📖 Project Overview

This project implements a Smart Finance Assistant using Python, pandas, hands-on-ai, and Gradio.

The assistant helps users analyse their spending habits by processing transaction data from CSV files. It provides summaries, identifies spending patterns, offers basic financial advice, and includes a savings calculator tool.

---

## 🚀 Features

### 💬 Chatbot
- Financial advisor chatbot with defined personality
- Provides simple and practical financial advice

### 📊 Transaction Analysis
- Reads transaction data from CSV files
- Calculates:
  - Total spending
  - Top category
  - Average transaction amount

### 🧮 Savings Calculator Tool
- Calculates time needed to reach savings goals

### 🖥️ Gradio UI
- Upload CSV files
- View analysis results
- Use savings calculator

---

## 🛠️ Technologies Used

- Python
- pandas
- hands-on-ai
- Gradio
- Jupyter Notebook / Google Colab

---

## ▶️ How to Run (Google Colab)

1. Open Google Colab:
https://colab.research.google.com/

2. Upload the project notebook (.ipynb file)

3. Install required packages:
```python
!pip install hands-on-ai pandas gradio
```
import os

4. Configure


import os

os.environ['HANDS_ON_AI_SERVER'] = 'https://ollama.locollm.org'
os.environ['HANDS_ON_AI_MODEL'] = 'gemma3:4b'
os.environ['HANDS_ON_AI_API_KEY'] = 'Curtin2026ISYS20015002'


---




## 📊 Example Output

- Total Spending: $XXX  
- Top Category: Food  
- Recommendation:
  - Reduce unnecessary spending  
  - Set a monthly budget


## 🤖 AI Collaboration

AI tools such as ChatGPT and hands-on-ai were used to:
- Generate code
- Debug errors
- Improve logic and structure

All AI usage is documented in the Developer’s Diary.
