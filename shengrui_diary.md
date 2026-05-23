
# 📓 Developer Diary – Shengrui Li

---

## Entry 1 – Project Planning

### Artifact
Used ChatGPT to help plan ideas for the Smart Finance Assistant project.

### Context
At the start of the project, I wanted to build a finance assistant to help students understand spending and saving money.

### Reflection
ChatGPT helped me think about useful features like spending analysis, budgeting advice, savings tips, and CSV transaction analysis.

I learned that planning the project first is important before writing code. This helped me focus on creating a useful finance assistant instead of only showing data.

---

## Entry 2 – CSV Data Processing

### Artifact
Used AI to help create Python functions for loading and cleaning CSV data.

### Context
The project needed to process transaction data with dates, amounts, categories, and descriptions.

### Reflection
ChatGPT helped me use pandas to clean the CSV data. I created functions to remove dollar signs, convert values into numbers, and remove invalid rows.

During testing, I learned how important data cleaning is before analysis. I also improved my understanding of DataFrames and CSV processing in Python.

---

## Entry 3 – Spending Analysis

### Artifact
Developed spending analysis functions with help from AI suggestions.

### Context
I wanted the system to calculate total spending, spending by category, and identify the highest spending category.

### Reflection
AI helped me build spending analysis using `groupby()` and calculations.

I tested the system with different transaction examples and learned how to create business-style insights instead of only technical outputs.

For example, the system can identify high coffee or entertainment spending and provide simple saving advice.

---

## Entry 4 – Financial Recommendation System

### Artifact
Used ChatGPT to help generate financial recommendation logic.

### Context
I wanted the finance assistant to provide practical financial advice instead of only calculations.

### Reflection
I created recommendation logic based on spending categories and total spending levels.

For example, if entertainment spending is high, the system gives advice about reducing unnecessary spending and setting monthly limits.

This helped me understand how business logic can improve user experience.

---

## Entry 5 – Chatbot Personality Setup

### Artifact
Used AI to create a chatbot personality for the Smart Finance Assistant.

### Context
I wanted the chatbot to communicate in a friendly and simple way for university students.

### Reflection
ChatGPT helped me create prompts that focus on budgeting and saving advice.

I learned that prompts are important because they affect how the chatbot responds to users. I also learned how chatbot personality can improve user interaction and make the system feel more natural.

During testing, I had connection and configuration problems with the AI server. I fixed these problems by checking the API key and re-running the setup cells.

This improved my debugging skills and understanding of AI integration.

---

## Entry 6 – Simple RAG System

### Artifact
Built a simple RAG-style financial advice system using keyword matching.

### Context
I wanted the chatbot to give different advice depending on the user’s question.

### Reflection
I created a simple retrieval system using financial keywords and predefined advice.

For example:
- Coffee → saving money advice
- Groceries → meal planning advice
- Transport → travel cost reduction advice

Even though the system is simple, it helped me understand the idea of Retrieval-Augmented Generation (RAG).

I learned that retrieved information can help the chatbot generate more relevant responses.

---

## Entry 7 – Gradio User Interface

### Artifact
Used AI to help create a Gradio interface for the Smart Finance Assistant.

### Context
I wanted users to upload CSV files and interact with the finance assistant using a simple interface.

### Reflection
ChatGPT helped me organise the Gradio layout using tabs, upload buttons, textboxes, and output areas.

I successfully added:
- CSV analysis
- Spending recommendations
- Savings calculator

During development, I had problems with file uploads because I uploaded Excel files instead of CSV files.

After debugging the issue, I learned the difference between `.csv` and `.xlsx` files and how file formats affect Python data processing.

---

## Entry 8 – Testing and Debugging

### Artifact
Created testing cases using AI-generated testing ideas.

### Context
The project needed proper testing to make sure all functions worked correctly.

### Reflection
I tested:
- Normal transaction data
- Refund transactions
- Empty datasets
- Invalid values
- Savings calculator edge cases

I used assert statements to check whether calculations and outputs were correct.

During testing, I encountered errors such as:
- `NoneType` errors
- Empty sequence errors
- Wrong file format errors

By fixing these problems, I improved the reliability of the project and learned more about debugging and error handling in Python.

---

# Final Reflection

This project helped me improve both technical and problem-solving skills.

I learned:
- CSV data processing
- Financial data analysis
- Chatbot integration
- Gradio UI development
- Testing and debugging
- AI-assisted programming

ChatGPT was used as a support tool during the project. However, I reviewed and modified the AI-generated code to make sure it worked correctly and matched the project requirements.

This project also improved my confidence in using AI tools in software development.
