# 🤖 Rule-Based AI Chatbot

A simple **Rule-Based AI Chatbot** developed as part of the **DecodeLabs Artificial Intelligence Internship – Project 1**.

The chatbot uses predefined rules and `if-elif-else` decision logic to understand basic user inputs and provide appropriate responses.

## 📌 Project Overview

This project demonstrates the fundamentals of building a conversational AI system using Python without machine learning or external AI APIs.

The chatbot continuously interacts with the user, identifies predefined patterns in the input, and responds accordingly.

## 🎯 Objectives

* Build a simple rule-based conversational chatbot
* Understand basic chatbot decision-making logic
* Implement conditional `if-elif-else` statements
* Handle different types of user inputs
* Create a continuous conversation loop
* Provide appropriate responses for unknown inputs
* Implement exit commands to end the conversation

## ✨ Features

* 👋 Greeting responses
* 🤖 Information about the chatbot
* 💡 Basic AI-related questions
* 🛠️ Information about chatbot capabilities
* 😊 Responses to positive and negative inputs
* 🙏 Responses to thanks
* ❓ Handling of unknown inputs
* 🚪 Exit commands such as `bye`, `exit`, and `quit`
* 🔄 Continuous conversation using a `while` loop

## 🧠 How It Works

The chatbot follows a simple rule-based approach:

```text
User Input
     ↓
Convert input to lowercase
     ↓
Check predefined rules
     ↓
Match input with condition
     ↓
Generate appropriate response
     ↓
Continue conversation
```

The user's input is processed using:

* `.lower()` to make the input case-insensitive
* `.strip()` to remove unnecessary spaces
* `if-elif-else` conditions to determine the response
* `while True` to maintain continuous conversation

## 🛠️ Technologies Used

* Python
* Conditional Statements
* String Processing
* Loops
* Rule-Based Decision Logic

## 📂 Project Structure

```text
Rule-Based-AI-Chatbot/
│
├── Rule_Based_AI_Chatbot.ipynb
└── README.md
```

## ▶️ How to Run

### Option 1 — Google Colab

1. Open the `.ipynb` file using Google Colab.
2. Run the notebook cells.
3. Enter messages when prompted.
4. Type `bye`, `exit`, or `quit` to end the conversation.

### Option 2 — Jupyter Notebook

1. Download the notebook.
2. Open it using Jupyter Notebook or JupyterLab.
3. Run the cells.
4. Interact with the chatbot through the input prompt.

## 💬 Example Interaction

```text
You: Hello
Bot: Hello! How can I help you?

You: What is AI?
Bot: AI stands for Artificial Intelligence...

You: What can you do?
Bot: I can answer basic questions and have a simple conversation.

You: Bye
Bot: Goodbye! Have a great day!
```

## 📚 What I Learned

Through this project, I learned:

* How rule-based chatbots work
* How conditional logic can be used for conversational systems
* How to process and normalize user input
* How to create continuous interactive programs
* The limitations of rule-based AI compared with machine-learning-based systems

## 🚀 Future Improvements

Possible improvements include:

* Adding more conversational rules
* Supporting more user intents
* Adding Natural Language Processing (NLP)
* Using machine learning for intent classification
* Adding a graphical or web-based interface
* Connecting the chatbot to external APIs or databases


