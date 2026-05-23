---
# 📊 Smart Finance Assistant – Shengrui Li

---

## 📖 Project Overview

This project implements a Smart Finance Assistant using Python, pandas, hands-on-ai, and Gradio.

The assistant helps users analyse their spending habits by processing transaction data from CSV files. It provides spending summaries, identifies spending patterns, offers simple financial advice, and includes a savings calculator tool.

The project is designed mainly for university students who want an easier way to manage spending and improve budgeting habits.

---

## 🚀 Features

### 💬 Chatbot
- Financial advisor chatbot with defined personality
- Provides simple and practical financial advice
- Gives budgeting and saving suggestions

### 📊 Transaction Analysis
- Reads transaction data from CSV files
- Cleans transaction data automatically
- Calculates:
  - Total spending
  - Top spending category
  - Average transaction amount
- Generates spending insights and recommendations

### 🔍 Simple RAG System
- Uses keyword-based retrieval for financial advice
- Retrieves different financial tips depending on user questions
- Improves chatbot response relevance

### 🧮 Savings Calculator Tool
- Calculates time needed to reach savings goals
- Includes simple error handling

### 🖥️ Gradio UI
- Upload CSV files
- View spending analysis results
- Use savings calculator
- Simple and user-friendly interface

---

## 🛠️ Technologies Used

- Python
- pandas
- hands-on-ai
- Gradio
- Jupyter Notebook
- Google Colab

---

## ▶️ How to Run (Google Colab)

### 1. Open Google Colab
https://colab.research.google.com/

### 2. Upload the notebook (.ipynb file)

### 3. Install required packages

```python
!pip install hands-on-ai pandas gradio

4. Configure hands-on-ai
import os

os.environ['HANDS_ON_AI_SERVER'] = 'https://ollama.locollm.org'
os.environ['HANDS_ON_AI_MODEL'] = 'gemma3:4b'
os.environ['HANDS_ON_AI_API_KEY'] = 'Curtin2026ISYS20015002'

5. Run all notebook cells
6. Launch the Gradio interface demo.launch()
```
📊 Example Output
Total Spending: $150.95

Top Category: Entertainment

Average Transaction: $37.74

Recommendation:
- Reduce unnecessary spending
- Set a monthly budget
- Track spending regularly

🧪 Testing

The project includes testing for:

CSV data loading
Data cleaning
Spending analysis
Recommendation generation
Savings calculator
Error handling
Integration testing

Testing scenarios include:

Normal transaction data
Refund transactions
Empty datasets
Invalid values
File format issues
🤖 AI Collaboration

AI tools such as ChatGPT and hands-on-ai were used throughout the project to support development.

AI assistance was used for:

Generating code
Debugging errors
Improving logic and structure
Building testing cases
Creating the Gradio interface
Developing the chatbot and RAG system

All AI-generated code was reviewed, tested, and modified before final implementation.

AI usage and development reflections are documented in the Developer’s Diary.

📜 License

This project was created for educational purposes as part of a university assignment.
