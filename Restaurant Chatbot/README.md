**📘 Restaurant AI Chatbot (LLM Setup Demo)**

This is a simple AI-powered restaurant chatbot built to demonstrate LLM setup, configuration, and usage using Python.

The chatbot currently supports:

Asking about food items

Getting prices from a local database

Running with cloud LLM APIs or local Ollama models

This project is intentionally kept simple to showcase LLM integration rather than complex features.

**✨ What This Project Does**

Accepts natural language questions about food

Looks up food prices from a local database

Uses an LLM to understand user queries

Demonstrates how to:

Configure API keys using .env

Switch between cloud LLMs and local Ollama

Call LLMs from Python

**🧠 Example Queries**

“What is the price of Chhole Bhature?”

“How much does Paneer Butter Masala cost?”

“Is Chhole Bhature veg?”

**🔑 LLM Setup (Required)**

The chatbot needs an LLM to run.
You can choose one of the following options.

**Option 1: Cloud LLM (API Key)**

Create a .env file in the same folder as the notebook

Add your API key:

API_KEY=your_api_key_here


The notebook will automatically load this key to initialize the LLM.

⚠️ Do not commit .env files to GitHub.

**Option 2: Local LLM using Ollama**

You can also run the chatbot entirely locally using Ollama.

Steps:

Install Ollama:
https://ollama.com/

Pull a model (example):

ollama pull llama3


Start Ollama (runs locally)

Select the Ollama option in the code to use the local model instead of a cloud API.

This option requires no API key.

**▶️ How to Run**

Create a virtual environment (optional but recommended)

Install dependencies

Choose and add API Key, API URL of LLM you want to work with

Open the Jupyter Notebook

Ensure .env file is present or Ollama is running

Run all cells

Start chatting with the bot

**🎯 Purpose of This Project**

This project is meant to demonstrate:

How to set up and call LLMs in Python

How to switch between cloud and local models

How to use environment variables securely

Basic LLM-driven chatbot logic

It is not intended to be a full production restaurant system.

**📝 Notes**

Responses are limited to food-related queries

More features can be added later (recommendations, ordering, etc.)
