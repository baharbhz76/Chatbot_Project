Chatbot Applications
Overview
This repository contains three Jupyter notebooks that demonstrate the implementation of chatbots using Flask, Hugging Face models, and memory-based enhancements.

Notebooks
1. Demo1_flask_chatbot.ipynb
This notebook demonstrates a simple chatbot implemented using Flask and a Hugging Face model. It includes:

Text Generation: Uses a pre-trained model from Hugging Face to generate human-like responses to user input.
Flask API: Exposes a simple Flask-based REST API for receiving and responding to messages.
2. Demo2_chatbot_Memory.ipynb
This notebook extends the chatbot to include conversation memory, making the bot capable of maintaining context throughout a conversation. Key features include:

Conversation Memory: Stores user messages and responses, allowing the chatbot to refer to previous interactions for more coherent dialogue.
Text Generation: Uses a similar model as Demo1 for response generation.
3. Chatbot_Enhancement_OpenOrca.ipynb
This notebook includes advanced enhancements to the chatbot, leveraging the OpenOrca model for improved text generation. It builds on the memory capabilities of the previous demo and adds:

Advanced Response Generation: Enhanced model for better contextual understanding and more fluent responses.
Memory Management: Improved handling of conversation history to make interactions more dynamic.
Requirements
To run these notebooks, you'll need the following libraries installed:


pip install flask transformers datasets tensorflow rouge-score
Usage
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/yourrepository.git
cd yourrepository
Run Jupyter Notebooks: Ensure you have Jupyter installed, then start the notebook server:


jupyter notebook
Open each notebook and run the cells to see the chatbot in action.

Project Structure
Demo1_flask_chatbot.ipynb: Basic chatbot using Flask and Hugging Face models.
Demo2_chatbot_Memory.ipynb: Chatbot with memory to handle conversation context.
Chatbot_Enhancement_OpenOrca.ipynb: Advanced chatbot with memory and enhanced model capabilities.






   

