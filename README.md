# Role-Based LLM Chatbot (Streamlit + LangChain + Gemini)

## Overview

This project is a **role-based AI chatbot** built using **LangChain**, **Google Gemini**, and **Streamlit**.

The chatbot can change its **behavior depending on the selected role**, demonstrating how **LLM prompt engineering and chains** can control AI responses.

This mini project was developed as part of an **LLM course assignment** focused on:

- LLM Chains
- Prompt Templates
- Conversation Memory
- AI Chat Interfaces

---

## Features

- Interactive **chat interface**
- Multiple **AI personalities**
- Conversation **history memory**
- Powered by **Google Gemini API**
- Built using **LangChain runnable chains**
- Simple and lightweight **Streamlit UI**

---

## Chatbot Roles

The chatbot supports multiple roles that modify how the AI responds.

| Role | Behavior |
|-----|------|
| Helpful Assistant | Gives clear and helpful explanations |
| Curious Teacher | Asks questions and encourages learning |
| Advanced Vocabulary | Uses sophisticated and formal language |
| Brief Assistant | Responds with short and concise answers |

---

## Project Architecture

The application uses a simple **LLM chain pipeline**:

```
User Input
     ↓
Prompt Template
     ↓
Gemini LLM
     ↓
Output Parser
     ↓
Chat Response
```

Conversation history is stored using **Streamlit session state**, allowing the chatbot to remember previous messages.

---

## Technologies Used

- Python
- LangChain
- Google Gemini API
- Streamlit
- LLM Chains & Runnables

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/role-based-llm-chatbot.git
```

Go to the project folder:

```bash
cd role-based-llm-chatbot
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Application

Start the Streamlit app:

```bash
streamlit run role_chatbot_app.py
```

The application will automatically open in your browser.

---

## API Configuration

You need a **Google Gemini API key**.

Create one here:

https://aistudio.google.com/

Then add it in the code:

```python
os.environ["GOOGLE_API_KEY"] = "YOUR_API_KEY"
```

---

## Example Interaction

User:

```
Explain what a transformer model is.
```

Chatbot (Curious Teacher role):

```
That's an interesting question! Before we dive in, what do you already know about neural networks?
```

---

## Learning Objectives

This project demonstrates:

- Building **LLM-powered applications**
- Creating **prompt templates**
- Using **LangChain chains**
- Implementing **conversation memory**
- Designing **AI user interfaces**

---

## Author

Oussama Hannachi  
Software Engineering Student – ESPRIT
