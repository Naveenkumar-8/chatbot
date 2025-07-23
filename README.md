Python CLI Chatbot with Ollama
A simple, terminal-based chatbot built in Python that interacts with locally running language models through the Ollama service. This project is a great starting point for anyone looking to experiment with the ollama Python library.
Features
 * Interactive command-line chat interface.
 * Connects to any language model served by your local Ollama instance.
 * Lightweight and easy-to-understand codebase.
 * Type exit or quit to end the session gracefully.
Prerequisites
Before you begin, ensure you have the following installed:
 * Python 3: Make sure Python 3.x is installed on your system.
 * Ollama: You must have the Ollama application installed and running on your computer.
 * A Language Model: You need to have downloaded a model. The code defaults to using mistral. You can pull it by running this command in your terminal:
   ollama run mistral

Setup & Installation
 * Clone the Repository (or download the files):
   git clone https://github.com/Naveenkumar-8/chatbot.git
cd chatbot

 * Install Dependencies: This project requires the ollama library. You can install it using pip.
   # This command explicitly uses your python installation to run pip
python -m pip install ollama

How to Run
 * Make sure your Ollama application is running in the background.
 * Open your terminal, navigate to the project directory, and run the script:
   python "project chatbot.py"

   > Note: It's good practice to name files without spaces (e.g., chatbot.py) to avoid needing quotes in the terminal.
   > 
Example Usage
Ask something (or type 'exit' to quit): What is the main purpose of this program?
Answer: The main purpose of this program is to serve as a simple, interactive command-line interface that allows a user to communicate with a locally running language model via the Ollama platform.

Ask something (or type 'exit' to quit): exit
Goodbye!...
