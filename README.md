# **Chatbot Applications**

## **Overview**
This repository contains three Jupyter notebooks that demonstrate the implementation of chatbots using Flask, Hugging Face models, and memory-based enhancements.

## **Notebooks**

### **1. `Demo1_flask_chatbot.ipynb`**
This notebook demonstrates a simple chatbot implemented using Flask and a Hugging Face model. It includes:
- **Text Generation**: Uses a pre-trained model from Hugging Face to generate human-like responses to user input.
- **Flask API**: Exposes a simple Flask-based REST API for receiving and responding to messages.

### **2. `Demo2_chatbot_Memory.ipynb`**
This notebook extends the chatbot to include conversation memory, making the bot capable of maintaining context throughout a conversation. Key features include:
- **Conversation Memory**: Stores user messages and responses, allowing the chatbot to refer to previous interactions for more coherent dialogue.
- **Text Generation**: Uses a similar model as Demo1 for response generation.

### **3. `Chatbot_Enhancement_OpenOrca.ipynb`**
This notebook includes advanced enhancements to the chatbot, leveraging the `OpenOrca` model for improved text generation. It builds on the memory capabilities of the previous demo and adds:
- **Advanced Response Generation**: Enhanced model for better contextual understanding and more fluent responses.
- **Memory Management**: Improved handling of conversation history to make interactions more dynamic.

---
## **Requirements**

To run these notebooks, you'll need the following libraries installed:

```bash
pip install flask transformers datasets tensorflow rouge-score
```
## **Installation**

To run the chatbot application, ensure you have Python (version 3.6 or higher) and the required libraries installed.

###  **Clone the Repository**
```bash
git clone https://github.com/yourusername/yourrepository.git
cd yourrepository
```



