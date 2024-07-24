# Conversational AI Chatbot

This project is a Conversational AI Chatbot developed using open-source and paid LLMs with LangChain. The chatbot is executed and tested via command prompt, handling conversations and generating responses effectively.

## Features

- Utilizes LangChain and OpenAI API for conversation handling and response generation.
- Executed via command prompt.
- Streamlit framework for user input.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/conversational-ai-chatbot.git
    cd conversational-ai-chatbot
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Create a `.env` file in the project root directory and add your OpenAI API key:
    ```
    OPENAI_API_KEY=your_openai_api_key
    LANGCHAIN_API_KEY=your_langchain_api_key
    ```

## Usage

1. Run the application:
    ```bash
    streamlit run app.py
    ```

2. Open your web browser and go to `http://localhost:8501` to access the chatbot interface.
