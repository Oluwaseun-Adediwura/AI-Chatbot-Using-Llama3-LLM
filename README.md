# Seun's AI Chatbot 🤖

Welcome to Seun's AI Chatbot, a project that leverages the Llama3 Large Language Model (LLM) using the OllamaLLM API through Langchain, providing users with a responsive chatbot capable of maintaining multi-turn conversations.

# Features

* 💬 Interactive Chat Interface: Converse with the chatbot, and get responses powered by the Llama3 model.
* 🧠 Conversation Memory: The chatbot can retain conversation history within a single session to provide more coherent answers based on previous interactions.
* 🔄 Continuous Chat Loop: The chatbot stays in the conversation until the user exits by typing `exit`.

# Tech Stack

* Python 🐍: Core programming language.
* Langchain 🧠: Used to manage LLMs and chat prompts.
* OllamaLLM 🦙: Interface to access and use the Llama3 model for generating responses.

# How It Works

This project uses the `Langchain_Ollama` integration to power a simple AI chatbot. It sends user input as a prompt to the Llama3 model, which generates the response based on the context of previous messages. The conversation history is maintained to allow more meaningful responses, much like how human conversations flow.

The chat interface is command-line-based, and the chatbot will continue interacting with you until you explicitly exit.

# Core Workflow

* LLM Interaction: The `OllamaLLM` is invoked with the current user input and conversation history. The model generates an answer based on both the immediate question and the preceding context.

* Conversation Flow: The chatbot continuously updates the context with each interaction, making the conversation dynamic and consistent.

# Prerequisites
To run this project locally, you will need to install the following dependencies:

* Python 3.x
* `langchain`
* `langchain_ollama`

# Roadmap
* Add support for multi-session context (save chat history between sessions).
* Integrate a graphical user interface (GUI).
* Improve conversation logic for better context understanding.
* Add more advanced AI models for diverse responses.
